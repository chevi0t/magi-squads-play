# Magi-squads（試作）

魔法少女が街の上を飛び回って撃ち合う、ブラウザの試作ゲームです。

**遊ぶ：** https://chevi0t.github.io/magi-squads-play/

`index.html` 1つで動きます（ダウンロードしてダブルクリックでも開けます）。開発は非公開のリポジトリで行い、ここには遊ぶためのページだけを置いています。

## 操作

- マウス：向き（照準の近くの相手を自動でロックオン、Q で切り替え）
- W A S D：移動（いつも速く飛びます）／Space：上昇／Shift：クイックブースト
- Ctrl か C：急降下。地面やビルの近くでは Shift で蹴って、ゲージを使わずにクイックブースト
- 左クリック：主武器／右クリック：補助（膜など）／左右同時：合わせ技
- F（か真ん中ボタン）：副武器／E：特別／Esc：一時停止／R：初めから

## 出典・謝辞

地理データ：東京都・千代田区・台東区／国土交通省 Project PLATEAU（2025年度）の3D都市モデル、国土地理院の標高タイル、OpenStreetMap contributors。[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) に基づき、600m 四方へ切り出して形を単純化するなど加工しています。原典の利用条件は公共データ利用規約 1.0（CC BY 4.0 互換）。

- [PLATEAU 公開データ](https://www.mlit.go.jp/plateau/open-data/)（[3D都市モデル 千代田区](https://www.geospatial.jp/ckan/dataset/plateau-13101-chiyoda-ku-2025)・[台東区](https://www.geospatial.jp/ckan/dataset/plateau-13106-taito-ku-2025)）
- [国土地理院 標高タイル](https://maps.gsi.go.jp/development/demtile.html)

都市モデルと地理情報を整備・公開してくださった東京都、千代田区、台東区、国土交通省、国土地理院、OpenStreetMap contributors の皆さまに心より感謝します。

three.js r128 は MIT License です（全文は [THREE-LICENSE.txt](THREE-LICENSE.txt) と `index.html` の中）。

キャラクターと設定はオーナーの原案『星のない港』によるものです。
