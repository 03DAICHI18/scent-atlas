# KAORINK（カオリンク）

香りを知る。香りとつながる。

公式情報とAIによる解釈を区別するフレグランス図鑑。

## URL

既存プレビュー：https://scent-atlas-preview.vercel.app/
リポジトリ：https://github.com/03DAICHI18/scent-atlas

KAORINK版は開発中。旧プレビューへの反映とGit連携は未完了。

## 開発

`SITE_URL=https://公開先ドメイン python3 build.py`

`python3 -m http.server 8000 --directory dist`

`data/products.json`が新しい正本。旧`data/perfumes.json`と9シーン・用語集を保持。publishedのみHTMLを生成し、pendingは非公開。出典と公式ノートを検証してから公開する。

登録基準：EDITORIAL.md
進捗と未完了事項：STATUS.md

画像は利用許諾未確認のため未掲載。写真の代わりの文字表示は実商品の画像ではない。
