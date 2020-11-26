# middleware
偵測伺服器收到請求的狀態

# features
伺服器收到任何來自瀏覽器的 request 時，都會自動把資訊紀錄到 server log 裡，包括：
* 時間戳記 (time-stamps) - 以當地時間 (台北) 顯示
* 請求的 HTTP 方法
* URL

# installation and execution
  1. 打開終端機(Terminal)，Clone 此專案至本地電腦
  ```
  git clone https://github.com/yun856839/middleware.git
  ```

  2. 開啟終端機，進入專案資料夾
  ```
  cd middleware
  ```

  3. 安裝 npm 套件
  ```
  npm install
  ```
  
  4. 執行 server
  ```
  npm run dev
  ```

  5. 開啟任一瀏覽器瀏覽器，輸入網址
  ```
  http://localhost:3000
  ```
