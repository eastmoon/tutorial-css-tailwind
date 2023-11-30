# tutorial-css-tailwind
Cascading Style Sheets ( CSS ) framework Tailwind training and demo.

## Introduction

## Develop CLI

### 啟動與關閉測試環境

+ ```cli up```：啟動測試環境
+ ```cli down```：關閉測試環境

測試環境是一個 Nginx 容器，並將 ```src/html``` 與 ```cache/dist``` 目錄掛載於 ```/usr/share/nginx/html``` 下方，以便於開啟網址驗證輸出結果：

+ 主頁面：http://localhost:8080/
+ CDN 測試主頁：http://localhost:8080/cdn.html
+ CLI 測試主頁：http://localhost:8080/cli.html

### 編譯 Twailwind CSS 檔案

+ ```cli dev```：啟動編譯環境
    - ```npm run build```：執行編譯 CSS 檔案，其輸出會放置在 ```cache/dist```

不同於 CDN 是將整份 Twailwind CSS 檔案抓取，編譯是將 HTML、JavaScript 檔案有參考的類別彙整於一個輸出 CSS 檔案，並提供給頁面引用。

## Style Framework design

+ Layout
    - Wireframe
        + Theme

### Layout

+ Structure
+ Position
    - Coordinates
### Wireframe style

+ Position
    - Width and Height
+ Box
    - Align
    - vAlign
    - Justify
+ Multi-Columns
    - Grid

### Theme

+ Color
+ Background
+ Border

## 文獻

+ [TailwindCSS](https://tailwindcss.com/)
    - [Get started with Tailwind CSS](https://tailwindcss.com/docs/installation)
+ 教學文章與範例專案
    - [2023 Top 5 CSS Frameworks for Developers and Designers](https://www.browserstack.com/guide/top-css-frameworks)
    - [還在跟複雜的 CSS 的設定奮鬥嗎？用 Tailwind 來幫你實現真正的高效整潔！](https://5xcampus.com/posts/tailwind-css-plugin)
    - [淺談 Atomic CSS 的發展背景與 Tailwind CSS](https://blog.huli.tw/2022/05/23/atomic-css-and-tailwind-css/)
    - [Tailwind CSS 大全](https://powerkaifu.github.io/2020/09/24/lesson-tailwind-css/)
