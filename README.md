# 釗&均 電子喜帖

2024-10-19 喜宴用的單頁電子喜帖（靜態網站，GitHub Pages 部署），現作為紀念保存。

## 目錄結構

```
index.html          頁面本體
booking.ics         Apple 行事曆事件檔（「Apple」按鈕下載）
css/                各區塊樣式（top / info / remind / hall / contacts / album）
  font.css          Google 字型的 class
  bird.css          行事曆小鳥按鈕（第三方，見下方授權）
img/                背景照片
lib/bootstrap-5.3.3 Bootstrap CSS（僅使用 bootstrap.min.css）
```

## 外部資源

- Google Fonts：Dancing Script、Inter、LXGW WenKai Mono TC、Noto Sans TC
- [Add to Calendar Button](https://add-to-calendar-button.com/)（Google / Outlook 按鈕）
- Google 地圖嵌入、MyAlbum 相簿封面

## 小技巧

LINE 內建瀏覽器開啟時，在網址後加上 `?openExternalBrowser=1` 可改用手機預設瀏覽器開啟（行事曆按鈕才能正常運作）：

```
https://<帳號>.github.io/<repo>/?openExternalBrowser=1
```

## 第三方授權

`css/bird.css` 改寫自 CodePen「すやすやなボタン」
https://codepen.io/ash_creator/pen/zYaZXLJ

```
The MIT License (MIT)

Copyright (c) 2023 あしざわ - Webクリエイター (https://codepen.io/ash_creator/pen/zYaZXLJ)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Bootstrap 5.3.3 © The Bootstrap Authors，MIT License。
