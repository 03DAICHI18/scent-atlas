# SCENT ATLAS

静的な香水ガイド。`data/perfumes.json` に香水情報（27件）、`data/scenes.json` にシーン別セレクト、`data/glossary.json` に用語集を保存。

## 更新方法
1. `data/perfumes.json` の配列に既存の形式で新しい香水を追加。`id` は重複しない値を使用。
2. JSONの構文と重複を検証。
3. GitHubへコミットし、VercelのGit連携があれば自動デプロイ。

## ローカル表示
`python3 -m http.server 8000` を起動し、`http://localhost:8000` を開く。`file://` 直開きではfetch制限が発生する場合あり。

## データ品質
既存の香調・ノート・説明は会話を元にした編集上の暫定情報。`source_status: editorial_unverified` は未検証を示し、公式発表と区別する。
