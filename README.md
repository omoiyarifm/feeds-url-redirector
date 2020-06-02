# 概要
jekyll-redirect-from プラグインを使って、 FeedBurner の URL にリダイレクトするだけのもの。

# 背景
かつて、 #omoiyarifm では `http://feeds.lean-agile.fm/omoiyarifm` を Podcast Feed URL として利用していたが、 Feed Burner のカスタムドメインサービスが終了したことに伴って、 Podcast Feed URL を Feed Burner ドメインの URL に変更した。
ただし、世の中には、lean-agile.fm ドメインの Podcast Feed URL をしている事も多いと思われるため、 Feed Burner ドメインの URL へリダイレクトするように設定をする。（HTTP ステータスコードでのリダイレクトがより望ましいが、GitHub Pages ではそれができないため、jekyll-redirect-from プラグインを使って、meta タグでのリダイレクトを行う）