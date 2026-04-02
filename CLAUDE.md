# CLAUDE.md

## Localization

### Source of truth
- `en/` is the **sole source of truth** for all documentation
- All content changes must be made in `en/` first
- Chinese translations (`zh-Hans/`, `zh-Hant/`) and Japanese translations (`ja/`) must be derived from the English source — never written independently

### Translation rules
- **Never use direct/literal translations.** Word-for-word translation produces unnatural Chinese that feels foreign and robotic.
- Write as a native Chinese speaker would naturally explain a technical product — use the phrasing, rhythm, and vocabulary that everyday users in China (zh-Hans) or Taiwan/HK (zh-Hant) actually use in documentation, tutorials, and product guides.
- Prefer common everyday expressions over formal or academic phrasing. Chinese tech users tend to read docs that feel approachable, not stiff.
- For zh-Hans: follow mainland China conventions (e.g. 模板, 设置, 文档, 点击)
- For zh-Hant: follow Taiwan/HK conventions (e.g. 範本, 設定, 文件, 點選)
- Headings and UI labels should be concise — Chinese is information-dense, so shorter is better
- When a product name, feature name, or proper noun has no established Chinese equivalent, keep it in English (e.g. "Notion", "Rhino")

### Japanese translation rules (`ja/`)
- **Never use direct/literal translations.** Write as a native Japanese speaker would explain a tech product — use the phrasing, rhythm, and vocabulary found in Japanese documentation, tutorials, and product guides.
- Use です/ます form throughout for a friendly, approachable tone
- Prefer established loanwords where natural (e.g. テンプレート, ワークスペース, ダッシュボード, タスク)
- Headings should be concise — Japanese is information-dense
- When a product name, feature name, or proper noun has no natural Japanese equivalent, keep it in English (e.g. "Notion", "Rhino", "Epic")
