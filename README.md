# 調査・会議整理アシスタント

調査結果を出典付きの短い提案資料にまとめ、会議記録から決定事項と次のアクションを整理するAgentです。

## 含まれるもの

- `identity.md` — Agentの役割と進め方
- `knowledge/report-format.md` — 資料の書き方（要点・根拠・次のアクション）
- `.agents/skills/research-brief` — 調査を短い提案資料にまとめるSkill
- `.agents/skills/meeting-summary` — 会議記録から決定事項と次のアクションを整理するSkill

## セットアップ

外部サービスの接続、APIキー、環境変数は不要です。
読み手・予算・納品先などの前提は、依頼のたびにAgentへ伝えてください。
