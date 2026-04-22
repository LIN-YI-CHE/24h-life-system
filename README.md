# 24H Life System

個人用 24 小時人生系統 · Gaming HUD 風格

六階段：前夜清障 → 早晨開局 → 深度執行 → 下午推進 → 晚間複盤，附 30 日連線熱圖。

## Stack

- **Frontend**: 單檔 HTML (vanilla JS + CSS)
- **Host**: GitHub Pages
- **Auth**: Supabase Magic Link（Email 登入、無密碼）
- **Data**: Supabase Postgres (`life_states` table, JSONB + RLS)
- **Offline**: localStorage 當 cache、網路恢復自動補同步

## Live

`https://lin-yi-che.github.io/24h-life-system/`

## Dev loop

編輯 `index.html` → `git add index.html && git commit -m "..." && git push` → GitHub Pages 自動重新部署（~1-2 分鐘）。
