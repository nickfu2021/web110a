# Ubontu教程

---

## 知識點

* 前置準備作業
* Oracle VirtualBox 中安裝 Ubuntu

## 前置準備作業

* 已下載 Ubuntu 安裝檔
* 本範例使用 [Ubuntu 18.04 64-bit PC (AMD64) desktop image](https://releases.ubuntu.com/18.04/ "Ubuntu desktop image")

## 實戰演練

**step1** 開啟 VirtualBox

![圖片介紹](./images/Ubontu教程/01.png)

**step2** 新增機器

![圖片介紹](./images/Ubontu教程/02.png)

**step3** 名稱與作業系統

![圖片介紹](./images/Ubontu教程/02.png)


sudo apt-key list | \
 grep "expired: " | \
 sed -ne 's|pub .*/\([^ ]*\) .*|\1|gp' | \
 xargs -n1 sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys
