# Github 教程

---

## 建立本機 SSH 金鑰

為了不用每次使用 VS Code Github 功能都要登入，因此可先建立 ssh 憑證，之後就一勞永逸

1.首先輸入指令來產生 key

```bash
 ssh-keygen
```

2.接著會詢問產生的 ssh key 要存放的位置，這時選擇要放的位置 預設為 /home/username/.ssh/id_rsa

```bash
(若用預設位置，直接鍵入Enter)
```

3.接著會詢問要不要設定 passphrase，空白表示不設定，如果有設定 passphrase，則每次用此 key 登入都需要輸入這個密碼 (安全性較高，可依個人需求設定)

```bash
(若用預設位置，直接鍵入Enter)
```

## 為一個專案建立 Github 版本控管

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

## 如何修改 GitHub 上已存在之 Repo 名稱

### 修改遠端 Repo 名稱

> `https://github.com/<github 帳號>/<repo 名稱>/settings`

參考網站：<https://frannn.dev/posts/27fd8f25/>
