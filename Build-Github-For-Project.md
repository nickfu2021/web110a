# 為一個專案建立 Github 版本控管

## 實戰演練

1.VS Code 可安裝 gitignore 套件 _by_ CodeZombie

2.在 d 槽建立一個 project 資料夾，並將您的專案(例：web110a)複製到 project 內

> D:\project\web110a

3.用 VS Code 開啟 D:\project\web110a 並對專案資料夾初始化，產生 git 所需要的內容

```bash
 git init
```

4.登入 Github 並建立一個 repository (範例:web110a Public)。

5.在 VS Code 上 原始檔控制 對要上傳到 Github 按符號 "+" (暫存的變更)，還沒做"許可"&"上傳"。

6.選擇完所有暫存的變更後，按符號 "√ 提交" 並留下版本訊息(此時本機已完成版本更新，但 "尚未"上傳到"Github")。

7.將本機版控資料夾與 Github repository 做連線(首次)

```bash
git remote add origin https://github.com/NoahFu09/web110a.git
```

8.選擇要推送的 Git 分支(首次)

```bash
 git branch -M master
```

9.推送(PUSH)

```bash
 git push -u origin master
```

複製現有 github 上專案資料

```bash
git clone https://github.com/NoahFu09/NoahFu09.github.io
```
