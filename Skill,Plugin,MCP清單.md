# 本機 Claude 工具清單（Skill / Plugin / MCP / Agent / 排程）

> 盤點日期：2026-08-02　｜　由 toollist skill 自動產生（每次覆蓋＝永遠最新）
> 公開網頁：https://chensoo8911.github.io/my-claude-toollist-html/

## 🔑 觸發詞速查（35 個觸發詞 · 19 個 skill）

| 觸發詞 | 對應 Skill |
|---|---|
| `全域醫生` | **claude-doctor** |
| `幹大事` | **claude-ops** |
| `部署三劍客` / `裝三劍客` | **claude-triple-brain** |
| `我誰` / `幫我寫 CLAUDE.md` | **claude-whoami** |
| `開工` / `接手` | **claude-startup** |
| `收工` | **claude-handoff** |
| `發版` | **claude-command-push** |
| `加入ob` / `新增ob` | **claude-obsidian-inbox** |
| `加入詞彙` / `記知識庫` / `整理學習庫` / `X 是什麼？` | **my-claude-uiai-learn** |
| `列工具清單` / `更新工具清單` | **my-claude-toollist** |
| `做名片` | **claude-sv-card** |
| `展開SVG` | **claude-figma-svg-expand** |
| `大團出圖` | **claude-tnbt-export** |
| `how do I do X` / `find a skill for X` | **find-skills**（推測） |
| `preflight` / `pre-press check` / `print check` / `submission check` | **illustrator-preflight**（推測） |
| `寫 AI 腳本` / `寫 jsx` / `Illustrator 自動化` | **adobe-illustrator-scripting** |
| `iOS 介面檢查` / `HIG 檢查` / `蘋果規範` | **apple-hig-expert** |
| `快照全md` | **claude-md-snapshot** |
| `claude通知音效` | **claude-notify-sounds** |

## Skill · 自製（claude-＊／my-claude-＊，共 15 個）

| Skill | 觸發詞 | 用途 |
|---|---|---|
| **claude-doctor** | 全域醫生 | 健檢我用 Claude 的方式，挑毛病給建議（唯讀，要改會先問） |
| **claude-ops** | 幹大事 | 複雜任務的工作制度：自己跑循環、派工、驗收，不用我盯 |
| **claude-triple-brain** | 部署三劍客 / 裝三劍客 | 裝終端機的 AI 助手三人組（小G 量產、小L 讀文件、Claude 審查） |
| **claude-whoami** | 我誰 / 幫我寫 CLAUDE.md | 一句話變成完整 CLAUDE.md 角色設定，存進目前資料夾 |
| **claude-startup** | 開工 / 接手 | 開場用：判斷這是新專案還接手舊的，決定先做什麼 |
| **claude-handoff** | 收工 | 收工用：把進度寫進專案文件，並驗「明天的我接不接得住」 |
| **claude-command-push** | 發版 | 發版五步一次跑完：CHANGELOG→commit→tag→push→Release |
| **claude-obsidian-inbox** | 加入ob / 新增ob | 把當下的內容存成 .md 丟進 Obsidian 收件匣 |
| **my-claude-uiai-learn** | 加入詞彙 / 記知識庫 / 整理學習庫 / X 是什麼？ | 學到的新詞、新知識記進 UIAI 學習庫並自動歸類、同步 Obsidian |
| **my-claude-toollist** | 列工具清單 / 更新工具清單 | 盤點本機裝了哪些工具，更新這一頁 |
| **claude-sv-card** | 做名片 | 公司名片自動化：丟簽呈進來，自動分版型出完稿 |
| **claude-figma-svg-expand** | 展開SVG | Figma 的 SVG 展成純幾何，貼進網頁陰影不糊、文字不跑版 |
| **claude-tnbt-export** | 大團出圖 | 活動視覺批次出圖：Figma 一次匯完 1x/2x、GIF、印刷檔 |
| **claude-md-snapshot** | 快照全md | 把全域 CLAUDE.md 存一份日期快照（正本不動） |
| **claude-notify-sounds** | claude通知音效 | 裝 Claude 的提示音（「換你了」「需回應」兩種時機） |

## Skill · 第三方（外部安裝，共 4 個）

| Skill | 觸發詞 | 用途 | 原連結 |
|---|---|---|---|
| **find-skills** | how do I do X / find a skill for X | 不知道有沒有工具能做某件事時，幫我找還能裝什麼 skill | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| **illustrator-preflight** | preflight / pre-press check / print check / submission check | Illustrator 檔入稿前檢查：RGB、斷連結、低解析、文字沒外框 | [ie3jp/illustrator-mcp-server](https://github.com/ie3jp/illustrator-mcp-server) |
| **adobe-illustrator-scripting** | 寫 AI 腳本 / 寫 jsx / Illustrator 自動化 | 寫 Illustrator 自動化腳本（ExtendScript/jsx）的參考書 | [github/awesome-copilot](https://github.com/github/awesome-copilot) |
| **apple-hig-expert** | iOS 介面檢查 / HIG 檢查 / 蘋果規範 | iOS／macOS 介面照蘋果官方規範（HIG）檢查與設計 | [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) |

## 🌐 中文入口（26 個中文詞 · 9 個工具）

> 這些工具的 description 是英文，用中文講常常路由不到；中文詞寫在全域 CLAUDE.md 的路由表，
> **不改第三方檔案**（plugin 更新會換版本夾、改了會被蓋掉）。

### Skill（2 項）

| 我可能會說 | 對應 Skill |
|---|---|
| `iOS 介面檢查` / `HIG 檢查` / `蘋果規範` | **apple-hig-expert** |
| `寫 AI 腳本` / `寫 jsx` / `Illustrator 自動化` | **adobe-illustrator-scripting** |

### Plugin skill（7 項）

| 我可能會說 | 對應 Plugin skill |
|---|---|
| `做網頁` / `做前端` / `切版` | **frontend-design:frontend-design** |
| `做圖表` / `畫圖表` / `做儀表板` | **dataviz** |
| `配色` / `找字體` / `UI 參考` / `查設計風格` | **ui-ux-pro-max:ui-ux-pro-max** |
| `做 banner` / `做橫幅` / `做社群圖` | **ui-ux-pro-max:banner-design** |
| `做 logo` / `做 CIP` / `品牌識別` | **ui-ux-pro-max:design** |
| `做簡報` / `做投影片` | **ui-ux-pro-max:slides** |
| `Figma 轉程式碼` / `把設計做成網頁` | **figma:figma-design-to-code** |

## Plugin（已啟用，共 3 個）

| Plugin | 版本 | 來源 marketplace | 原連結 |
|---|---|---|---|
| **figma** | 2.2.87 | claude-plugins-official | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) |
| **frontend-design** | unknown | claude-plugins-official | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) |
| **ui-ux-pro-max** | 2.11.0 | ui-ux-pro-max-skill | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) |

## MCP Server（共 9 個）

| MCP | 類型 | 狀態 | 原連結 |
|---|---|---|---|
| **claude.ai Google Drive** | claude.ai connector | — | — |
| **claude.ai Slack** | claude.ai connector | — | — |
| **claude.ai Gmail** | claude.ai connector | — | — |
| **claude.ai Notion** | claude.ai connector | — | — |
| **plugin:figma:figma** | plugin 內建 | Needs auth | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) |
| **illustrator** | 本機 server | Connected | [spencerhhubert/illustrator-mcp-server](https://github.com/spencerhhubert/illustrator-mcp-server) |
| **playwright** | 本機 server | Connected | [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) |
| **firecrawl** | 本機 server | Connected | [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) |
| **illustrator-pro** | 本機 server | Connected | [ie3jp/illustrator-mcp-server](https://github.com/ie3jp/illustrator-mcp-server) |

## Agent（自製 5 個＋內建 6 個）

| Agent | 來源 | 用途 | 工具權限 |
|---|---|---|---|
| **handoff-checker** | 自製 | Fresh-context 交接驗收員（＝「明天的 session」模擬器） | Read, Glob, Grep, Bash |
| **publish-safety-checker** | 自製 | Fresh-context 發版安檢員 | Read, Glob, Grep, Bash |
| **system-critic** | 自製 | Fresh-context 制度質疑者（唱反調的那個） | Read, Glob, Grep, Bash, WebSearch, WebFetch |
| **uiai-recorder** | 自製 | UIAI 學習庫記錄員 | Read, Edit, Write, Glob, Grep, Bash |
| **verifier** | 自製 | Fresh-context 驗收員（Maker-Checker 的 Checker） | Read, Glob, Grep, Bash |
| **general-purpose** | 內建 | 萬用型：研究、找程式碼、多步驟雜活 | — |
| **Explore** | 內建 | 唯讀搜索型：大範圍掃檔案，只回結論 | — |
| **Plan** | 內建 | 架構規劃型：設計實作計畫、評估取捨 | — |
| **claude** | 內建 | FleetView 預設萬用款 | — |
| **claude-code-guide** | 內建 | Claude Code／API 問題專家 | — |
| **statusline-setup** | 內建 | 設定終端機狀態列專用 | — |

## 終端機工具（共 4 項）

| 工具 | 呼叫方式 | 用途 |
|---|---|---|
| **小G** | 小G 問題 ／ 小G：問題 | 量產苦力（Gemini）：草稿、翻譯、清單擴寫、格式轉換；產出自動落檔 |
| **小L** | 小L 加入／摘要／：問題 | 文件圖書館員（NotebookLM）：吞 PDF／網址，給有出處的問答與規格摘要 |
| **審查協議** | 對話打 .  | Claude 讀雜工落檔做漏洞審查＋修正定稿（三劍客的主廚環節） |
| **mole** | mo clean（預覽加 --dry-run） | Mac 深度清快取／釋放磁碟空間（Homebrew 安裝）；純手動、無自動排程 |

## 排程（共 4 支）

> 每天凌晨自動跑的工作（macOS launchd）。「未載入」代表那支今天不會跑，且不會有人通知你。

| 排程 | label | 時間 | 引擎 | 狀態 |
|---|---|---|---|---|
| **晨報** | `uai-morning` | 每天 04:30 | agy | 運行中 |
| **活動雷達** | `uai-events` | 每天 04:40 | agy | 運行中 |
| **全域醫生** | `uai-doctor` | 每天 04:45 | agy | 運行中 |
| **使用洞察** | `uai-insights` | 每週五 04:55 | insights | 運行中 |

---
> 🔒 本清單只含工具名稱與用途，不含任何密鑰、token 或 API 串接資訊。
