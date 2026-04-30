# 小小圖書管理員：分類大挑戰

一個給小學生玩的互動式網頁遊戲。  
玩家要在倒數時間內，把左側書本拖曳到右側正確的分類櫃，挑戰分類速度與準確度。

## 線上展示（GitHub Pages）

- [https://logandev-lkc.github.io/yhbookgame/](https://logandev-lkc.github.io/yhbookgame/)

## 遊戲特色

- 60 秒倒數挑戰
- 拖曳互動（支援滑鼠與觸控）
- 分數與連擊加成系統
- 難度會隨分數提高
- 手機 / 平板 / 桌機 RWD 版面

## 玩法說明

1. 點擊「開始遊戲」進入挑戰。
2. 把左側書本拖到右側對應分類櫃。
3. 分類正確可得分，連續答對有額外加分。
4. 倒數結束後顯示結算成績與歷史最高分。

## 難度機制

- 0 ~ 49 分：書本會顯示分類提示色與分類標籤。
- 50 ~ 100 分：書本改為統一顏色，提示減少。
- 100 分以上：只顯示書名，挑戰更高。

## 技術說明

- 純前端：`HTML + CSS + JavaScript`
- 繪圖：`Canvas 2D API`
- 無外部套件，單檔即可執行

## 本機執行

在專案資料夾執行任一方式：

- 直接用瀏覽器開啟 `index.html`
- 或使用簡易伺服器（建議）

```bash
python3 -m http.server 8000
```

再打開：

- [http://localhost:8000/index.html](http://localhost:8000/index.html)

## 專案結構

```text
yhbookgmae/
├── index.html
└── README.md
```

## 授權

本專案目前未特別標註授權條款，若要公開分享，建議補上 LICENSE（例如 MIT）。
