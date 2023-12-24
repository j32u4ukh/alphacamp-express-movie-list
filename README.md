# alphacamp-express-movie-list
使用 Express 框架的電影列表

## 初始化專案

### 1. npm init

建立 package.json 檔

```
$ npm init -y
```

### 2. 修改 scripts

修改 package.json，分別設定關鍵字 `start` 和 `dev` 對應的指令

```
"scripts": {  
    "start": "node app.js",
    "dev": "nodemon app.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

### 3. 安裝 Express

npm install: 安裝所需套件

```
$ npm i express
```

透過 npm install 之後，資料夾中還多了一支 package-lock.json 的檔案。這支檔案會詳細記錄每一次我們使用 npm 安裝的檔案，主要是讓 npm 在執行時參考用的，多數時候你並不需要留意這支檔案。