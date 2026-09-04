# vibe-slop：10 個狗血 vibe-code 風格的桃園天氣重設計

2026-09-04 以 `index.html` 為題材做的戲仿設計探索，刻意模仿最常見的 vibe-code 視覺套路。
每頁都是完整的天氣頁（即時、逐時、七天、十三區、空氣品質、日出日落），資料為寫死的示範資料。

| 檔案 | 流派 | Artifact |
|---|---|---|
| 01-glass.html | 紫藍漸層 Glassmorphism | https://claude.ai/code/artifact/22b6841c-1d83-4bb3-a658-9f4896fff086 |
| 02-saas.html | Tailwind SaaS 落地頁 | https://claude.ai/code/artifact/c71f6f4c-317d-4b2f-b687-78260f6219c0 |
| 03-neon.html | 賽博龐克霓虹 HUD | https://claude.ai/code/artifact/bdff545a-5b45-416d-b555-4bca0b1452c0 |
| 04-bento.html | Apple 便當格 | https://claude.ai/code/artifact/365debd9-3812-46d2-b1f2-12580c9b1355 |
| 05-brutal.html | Neubrutalism | https://claude.ai/code/artifact/331a9811-5db2-4621-a34b-a89911c52029 |
| 06-terminal.html | 駭客終端機 | https://claude.ai/code/artifact/90bed36c-ecaa-4f44-aede-4560da120e06 |
| 07-admin.html | 管理後台模板 | https://claude.ai/code/artifact/7b373c51-ad9f-47a0-accf-113ccd371579 |
| 08-kawaii.html | 粉彩可愛風 | https://claude.ai/code/artifact/d3239a23-d88e-4942-a3b1-767c1c8c5c57 |
| 09-nimbus.html | Vercel／Linear 純黑開發者頁 | https://claude.ai/code/artifact/422aa252-22e3-4500-89e3-3f8369b12372 |
| 10-pixel.html | 8-bit RPG 像素風 | https://claude.ai/code/artifact/ce5a6e1d-83f0-4206-b0d2-1fcba03494f0 |

注意：這些檔案是 Claude Artifact 的頁面片段，沒有 `<!doctype>`、`<html>`、`<head>`、`<body>` 外層；
直接用瀏覽器開啟仍可正常顯示，但若要獨立部署，請自行補上外層與 viewport meta。

這十頁為什麼是 slop、本專案該怎麼做，見 `docs/agents/design-slop.md`。
