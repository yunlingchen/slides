# 簡報集

用 `html-slide-builder` skill 產生的 Reveal.js 互動簡報，一個資料夾一份簡報。

## 結構

```
slides/
├── index.html          # 簡報目錄首頁
├── <簡報資料夾>/
│   └── index.html      # 簡報本體
└── ...
```

## 線上網址

部署到 GitHub Pages 後：

- 目錄首頁：`https://<帳號>.github.io/slides/`
- 單份簡報：`https://<帳號>.github.io/slides/<簡報資料夾>/`

## 新增一份簡報

在 Claude Code 對話中說「幫我把這份教材做成 HTML 互動簡報」，
完成後把新資料夾加進 `index.html` 的清單。

## 注意

互動元件（文字雲、投票）預設使用 skill 作者的**共用示範 Firebase 專案**，
資料為公開共用。正式課堂使用前請改成自己的 Firebase 專案。
