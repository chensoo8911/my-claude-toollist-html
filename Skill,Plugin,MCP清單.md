# 本機 Claude 工具清單（Skill / Plugin / MCP / Agent）

> 盤點日期：2026-08-01　｜　由 toollist skill 自動產生（每次覆蓋＝永遠最新）
> 公開網頁：https://chensoo8911.github.io/my-claude-toollist-html/

## 🔑 觸發詞速查（35 個觸發詞 · 19 個 skill）

| 觸發詞 | 對應 Skill |
|---|---|
| `寫 AI 腳本` / `寫 jsx` / `Illustrator 自動化` | **adobe-illustrator-scripting** |
| `iOS 介面檢查` / `HIG 檢查` / `蘋果規範` | **apple-hig-expert** |
| `發版` | **claude-command-push** |
| `展開SVG` | **claude-figma-svg-expand** |
| `快照全md` | **claude-md-snapshot** |
| `claude通知音效` | **claude-notify-sounds** |
| `加入ob` / `新增ob` | **claude-obsidian-inbox** |
| `幹大事` | **claude-ops** |
| `做名片` | **claude-sv-card** |
| `大團出圖` | **claude-tnbt-export** |
| `部署三劍客` / `裝三劍客` | **claude-triple-brain** |
| `我誰` / `幫我寫 CLAUDE.md` | **claude-whoami** |
| `how do I do X` / `find a skill for X` | **find-skills**（推測） |
| `preflight` / `pre-press check` / `print check` / `submission check` | **illustrator-preflight**（推測） |
| `全域醫生` | **my-claude-doctor** |
| `收工` | **my-claude-handoff** |
| `開工` / `接手` | **my-claude-startup** |
| `列工具清單` / `更新工具清單` | **my-claude-toollist** |
| `加入詞彙` / `記知識庫` / `整理學習庫` / `X 是什麼？` | **my-claude-uiai-learn** |

## Skill · 自製（claude-＊／my-claude-＊，共 15 個）

| Skill | 觸發詞 | 用途 |
|---|---|---|
| **claude-command-push** | 發版 | git repo 發版自動化五步：CHANGELOG → commit → tag → push tag → GitHu |
| **claude-figma-svg-expand** | 展開SVG | 把 Figma 帶有 drop-shadow / 文字的 SVG「完全展開」成純幾何、可在 HTML 穩定顯示的 SVG |
| **claude-md-snapshot** | 快照全md | 把全域 CLAUDE.md 存一份日期快照（用 cp 複製，正本不動） |
| **claude-notify-sounds** | claude通知音效 | 安裝／設定／移除 Claude Code 的純音效 hook（「換你了」「需回應」兩個時機） |
| **claude-obsidian-inbox** | 加入ob / 新增ob | 把當下內容存成 .md 到 Obsidian 收件匣，對齊既有屬性 schema |
| **claude-ops** | 幹大事 | 一套讓 AI 助理「自己跑完複雜任務」的工作制度 |
| **claude-sv-card** | 做名片 | StreetVoice 街聲名片自動化 |
| **claude-tnbt-export** | 大團出圖 | TNBT 大團（開發場次）從 Figma 批次存圖到本地交付夾的標準流程 |
| **claude-triple-brain** | 部署三劍客 / 裝三劍客 | 部署「三劍客」終端機 AI 協作環境（小G Gemini ＋ 小L NotebookLM ＋ Claude 審查） |
| **claude-whoami** | 我誰 / 幫我寫 CLAUDE.md | 把一句話的「你是誰＋規則」轉成完整 CLAUDE.md，存進目前資料夾 |
| **my-claude-doctor** | 全域醫生 | 全域醫生・判斷層：質疑並強化使用者用 Claude 的方式，橫跨制度／工作流／工具適配／自動化四塊 |
| **my-claude-handoff** | 收工 | 專案收尾與交接的完整流程——把進度寫進專案 CLAUDE.md、派 handoff-checker 驗「下一個 sess |
| **my-claude-startup** | 開工 / 接手 | 開場 SOP |
| **my-claude-toollist** | 列工具清單 / 更新工具清單 | 盤點本機 skill／plugin／MCP 並更新工具清單網頁（GitHub Pages，僅供自用） |
| **my-claude-uiai-learn** | 加入詞彙 / 記知識庫 / 整理學習庫 / X 是什麼？ | UIAI 學習記錄工作流 |

## Skill · 第三方（外部安裝，共 4 個）

| Skill | 觸發詞 | 用途 |
|---|---|---|
| **adobe-illustrator-scripting** | 寫 AI 腳本 / 寫 jsx / Illustrator 自動化 | 'Write, debug, and optimize Adobe Illustrator automation scr |
| **apple-hig-expert** | iOS 介面檢查 / HIG 檢查 / 蘋果規範 | "Audits and designs iOS/macOS/watchOS/visionOS interfaces ag |
| **find-skills** | how do I do X / find a skill for X | Helps users discover and install agent skills when they ask  |
| **illustrator-preflight** | preflight / pre-press check / print check / submission check | Run comprehensive pre-press preflight checks on Adobe Illust |

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

| Plugin | 版本 | 來源 marketplace |
|---|---|---|
| **figma** | 2.2.87 | claude-plugins-official |
| **frontend-design** | unknown | claude-plugins-official |
| **ui-ux-pro-max** | 2.11.0 | ui-ux-pro-max-skill |

## MCP Server（共 9 個）

| MCP | 類型 | 狀態 |
|---|---|---|
| **claude.ai Google Drive** | claude.ai connector | — |
| **claude.ai Slack** | claude.ai connector | — |
| **claude.ai Gmail** | claude.ai connector | — |
| **claude.ai Notion** | claude.ai connector | — |
| **plugin:figma:figma** | plugin 內建 | Needs auth |
| **illustrator** | 本機 server | Connected |
| **playwright** | 本機 server | Connected |
| **firecrawl** | 本機 server | Connected |
| **illustrator-pro** | 本機 server | Connected |

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

---
> 🔒 本清單只含工具名稱與用途，不含任何密鑰、token 或 API 串接資訊。
