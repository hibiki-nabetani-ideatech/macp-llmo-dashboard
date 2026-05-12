# M&Aキャピタルパートナーズ LLMO 分析ダッシュボード

GitHub Pages 公開ダッシュボード（手動更新版・URL限定公開）。

- **公開URL**: `https://<your-github-username>.github.io/<repo-name>/`
- **公開範囲**: URL を知っている人のみ（`<meta robots="noindex">` および `robots.txt` で検索エンジン除外）
- **集計対象**: M&Aキャピタルパートナーズ vs 日本M&Aセンター / ストライク / M&A総合研究所
- **データソース**: Ahrefs Brand Radar（カスタムプロンプト62件 × ChatGPT・Gemini・Copilot・Perplexity）

## ファイル構成

- `index.html` — ダッシュボード本体（単一ファイル、外部依存なし）
- `robots.txt` — 検索エンジン除外
- `README.md` — このファイル

## タブ構成

- **① 自社指標**：①-1 指名プロンプト言及状況
- **② 全体把握**：②-1 推奨状況 一覧 / ②-2 推奨状況詳細
- **③ ペルソナA（中堅企業オーナー）**：③-1 LLMの推薦基準と推薦企業 / ③-2 AI認知マッピング
- **④ ペルソナB（調剤薬局オーナー）**：④-1 / ④-2
- **⑤ ペルソナC（飲食店オーナー）**：⑤-1 / ⑤-2

## 更新方法

`index.html` を上書きして `git push` するだけで反映されます。
