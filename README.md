# 精靈紀元：本命修行大師 V1.0

原創單人網頁 RPG 原型。直接開啟 `index.html` 即可遊玩，無需安裝套件。

## 遊玩
- 開局選擇焰尾狐、潮靈蜥或青芽鹿。
- 使用 WASD、方向鍵或畫面方向鍵移動。
- 草叢隨機遭遇靈獸；對戰可攻擊、捕捉、用藥、撤退。
- 驛站 🏠 回復隊伍；右上角 🏆 挑戰首領。
- 右側「修行系統」使用修行點數升級與突破資質。
- 進度保存在瀏覽器 localStorage，清除瀏覽器資料會失去進度。

## 部署到 GitHub Pages
1. 在 GitHub 建立公開 repository，例如 `spirit-era`。
2. 將 `index.html` 上傳至 repository 根目錄並 Commit。
3. 開啟 Settings → Pages → Build and deployment → Deploy from a branch。
4. 選擇 `main` 與 `/(root)`，按 Save。
5. 等待部署後，網址通常是 `https://你的帳號.github.io/spirit-era/`。

## 已知限制
- 此版採 CSS 場景及 emoji 作為原創角色/靈獸的暫用圖示，尚未加入正式動漫立繪、動畫與音效。
- 地圖為單一 11×9 原型區域；有六種靈獸、六屬性簡易克制、隊伍上限六隻。
- 暫無雲端同步、多人、精靈進化、完整 NPC 對話與大型劇情。
- 本機存檔僅在同瀏覽器同網站來源有效。
