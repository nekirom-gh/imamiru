# いまミル！

ボタンひとつで、現在地か指定した駅から歩いて行けるラーメン・軽食・コンビニ・ATM・本屋・映画館を近い順に出す Web アプリ。営業時間が登録されているお店は「営業中」を表示し、映画館は公式上映スケジュールへ直通します。

- 公開URL: https://nekirom-gh.github.io/imamiru/
- 静的ファイルだけで動きます（`index.html` と `stations.json`）。サーバー不要。
- 位置情報を使うため HTTPS で配信してください（GitHub Pages は HTTPS）。

## データの出典

- 駅の位置: [駅データ.jp](https://ekidata.jp/)（加工して `stations.json` に同梱）
- お店の位置・営業時間・公式サイト: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors（Overpass API）
- 上映スケジュール: 載せていません。各劇場の公式サイトへリンクします。
