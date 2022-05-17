# test12
# 專案介紹
#### 【 寧蒙咖啡 】是一間在台南灣裡自家烘焙咖啡豆的實體店，以銷售咖啡豆為主，另外有咖啡豆磨粉及耳掛商品。
#### 依目前所學技術，嘗試將實體店銷售的商品，以網路平台販售的概念來呈現。
![image](https://user-images.githubusercontent.com/77562017/168759829-9dd354bc-f24f-43dd-9022-92910102ab97.png)


## 主要用途
#### 讓業者及消費者可在網路上進行銷售及購買，為彼此增加便利性。


## 專案連結
https://c711cat.github.io/lemon_coffee/


## 功能介紹
### 業者
 * 登入帳號需有「業者」的權限才可以檢視、操作以下功能
 * 可以新增、編輯、刪除咖啡豆
 * 可在後台利用拖曳功能，調整顯示在首頁的咖啡豆排列順序
 * 可以管理消費者訂單進度
   * 可以檢視消費者訂單
   * 訂單狀態
   * 付款狀態
   * 物流狀態
 * 可以修改上述訂單狀態

### 消費者
 * 可以註冊會員或登入會員 
 * 非會員亦可瀏覽豆單及商品詳細資訊
 * 登入後即可購買咖啡豆     
 * 可選購同一支咖啡豆，並可依據不同需求設定原豆、磨粉或耳掛
 * 可在購物車查看、修改品項
 * 可在購物車查看目前購買金額
 * 可以在購物車查看折扣、免運等等資訊
 * 若消費者填寫過收件人資料，則系統會自動代入相關資訊
 * 可以查看自己的訂單資訊，譬如訂單狀態、付款狀態、物流狀態

## 技術資訊
 * 使用 Vue.js 3 框架
 * 利用 Vue Cli 建置環境
 * 引入 Vue Router 管理路由
 * 套用 Vue Axios 串接 API ( [API 文件](https://kakas.github.io/lemon_coffee_documents/#introduction) )
 * 選用 PrimeVue 編排 UI 及相關功能
 * 以 Cookie 存取及移除管理權限
 * 參考[步昂網站](https://www.buoncaffe.com.tw/pages/product-list) : 設計豆單及商品頁面及相關功能

## 開發流程
 * 使用 Git 開新分支製作功能 
 * 確認後即 merge 回主支線，並進行下一回的開發


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
