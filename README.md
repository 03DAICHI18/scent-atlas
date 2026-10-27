# KAORINK（カオリンク）

香りを知る。香りとつながる。

公式情報とAIによる解釈を区別するフレグランス図鑑。

## URL

公開URL：https://scent-atlas-preview.vercel.app/
リポジトリ：https://github.com/03DAICHI18/scent-atlas

KAORINK版を公開済み。Vercelプロジェクト scent-atlas-preview は本リポジトリに接続済み。main更新時の自動デプロイを利用します。

## 開発

`SITE_URL=https://公開先ドメイン python3 build.py`

`python3 -m http.server 8000 --directory dist`

`data/products.json`が新しい正本。旧`data/perfumes.json`と9シーン・用語集を保持。publishedのみHTMLを生成し、pendingは非公開。出典と公式ノートを検証してから公開する。

登録基準：EDITORIAL.md
進捗と未完了事項：STATUS.md

商品写真は利用条件を確認できたものだけ掲載します。画像ごとの出典・撮影者・ライセンスはdata/products.jsonと画面内に記載します。
