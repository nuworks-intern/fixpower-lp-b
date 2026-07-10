# fixpower-lp-b

Fix Power 高圧電力 固定料金プラン LP（B：市場連動リスク訴求版 / 新電力強化版）

A/Bテストのうち **LP-B**。コスト削減・安定訴求の **LP-A** は別リポジトリ [`nuworks-intern/fixpower-lp-a`](https://github.com/nuworks-intern/fixpower-lp-a)。

## ファイル構成
- `index.html` — LP-B（市場連動型プランからの脱出訴求）。Netlify のトップ表示。

## デプロイ
Netlify（GitHub `nuworks-intern/fixpower-lp-b` 連携）で公開。

## メモ
- HTMLは自己完結型（CSS埋め込み・外部CDNフォントのみ、相対参照なし）。
- フォーム送信先は `<form id="leadForm">` / `<form id="heroForm">` の `data-endpoint` を差し替え（現状デモ動作・`REPLACE_WITH_LP_A_ENDPOINT` のまま未設定）。
- GA4 / 広告計測タグは `</head>` 直前・`</body>` 直前に貼付。

## 更新履歴
- 2026-07-10 受領：更新版に差し替え。プライバシーポリシー全文をオーバーレイで追加（フォーム同意文・フッターから導線）。「解約違約金0円」「リスクは当社が吸収」等の断定表現をトーンダウン。CASE/VOICE の訴求元を「市場連動」→「大手電力会社」に変更。所在地を東池袋二丁目60番2号に変更。
- 2026-06-24 受領：初版
