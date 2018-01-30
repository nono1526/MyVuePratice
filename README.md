VueJS 環境建構
============
## 使用 Vue-Cli - 自動產生 Vue 開發的 boilerplate  
可以自動建構 Vue.js 的開發環境
* 安裝 vue-cli
`npm install -g vue-cli` 
* `vue list` 來查看 vue-cli 支援哪幾種 template
若發生 `/usr/bin/env: ‘node’: 沒有此一檔案或目錄`
執行 `ln -s /usr/bin/nodejs /usr/bin/node`
若發生錯誤將 nodejs 更新到 6.0.0 版本以上 
* `vue init webpack-simple [專案名稱]` 建立新的專案
* `cd 新的專案`
* `npm install` 安裝需要的套件
* `npm run dev` 發布網站 http://localhost:8080/

