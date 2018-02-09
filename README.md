# React 使用 React Router v4，React Helmet和CSS模塊伺服器渲染(SSR) 範例

我們如何高效地為JavaScript應用程序提供快速內容交付和解決搜索引擎優化問題。答案是 - 服務器端渲染或稱之為SSR

## 我們需要什麼？

 1. React.js
 2. React Router v4  // 路由器 v4 版本
 3. React Helmet  // 可重用的React組件，可管理對文檔頭的更改
 4. CSS Modules
 5. Webpack 2
 6. Babel
 7. Express.js  // Node.js Web 應用程式架構
 8. PM2  // 管理 Node.js process 的工具
 9. Node.js（最好是版本6）

參考文件網址：
 1. https://reactjs.org/ (React.js)
 2. https://reacttraining.com/react-router/ (React Router v4)
 3. https://github.com/nfl/react-helmet (React Helmet)
 4. https://github.com/gajus/react-css-modules (CSS Modules)
 5. https://webpack.js.org/ (Webpack)
 6. https://babeljs.io/ (Babel)
 7. https://github.com/expressjs/express (Express.js)
 8. http://pm2.keymetrics.io/ (PM2)
 9. https://nodejs.org/en/ (Node.js)


## 建立專案資料夾與複製
```bash
$ git clone git@github.com:akayhu/react-ssr-exercise.git
```

## Install 安裝
```bash
$ npm install
```

## 執行本機專案
```bash
$ npm run dev
```

## 執行production打包
```bash
$ npm run production
```