# いまミル！

ボタンひとつで、現在地か指定した駅から歩いて行ける映画館を近い順に出し、各劇場の公式上映スケジュールへ直通する Web アプリ。

- 公開URL: https://nekirom-gh.github.io/imamiru/
- 静的ファイルだけで動きます（`index.html` と `stations.json`）。サーバー不要。
- 位置情報を使うため HTTPS で配信してください（GitHub Pages は HTTPS）。

## データの出典

- 駅の位置: [駅データ.jp](https://ekidata.jp/)（加工して `stations.json` に同梱）
- 映画館の位置: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors（Overpass API）
- 上映スケジュール: 載せていません。各劇場の公式サイトへリンクします。
