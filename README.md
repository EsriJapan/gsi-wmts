# gsi-wmts

地理院地図の layers.txt に含まれるレイヤーのうち、WMTS で配信可能なレイヤーのみを取得したメタデータです。「地理院タイル目録」より情報が取得可能なレイヤーには範囲を指定するエクステント情報を付加しています。

## 使用方法

WMTS の URL を ArcGIS 製品に接続すると各レイヤーをマップに追加することができます。

WMTS の URL は https://esrijapan.github.io/gsi-wmts/{XML ファイル名} です。{XML ファイル名} は本ページ掲載の XML ファイル名です。
例：https://esrijapan.github.io/gsi-wmts/layers0.xml

各 XML に含まれる内容は、それぞれの URL ページをご確認ください。レイヤーのタイトルは以下のタグで囲まれています。
<Layer><ows:Title>タイトル</ows:Title></Layer>

ArcGIS Desktop への接続方法については以下のページをご覧ください。
※Esri 製品サポート サイトへのログインが必要です。
https://esrij-esri-support.custhelp.com/app/answers/detail/a_id/6548

## 注意

地理院地図の layers.txt に掲載されているレイヤーのうち、WMTS で配信可能なレイヤーのみを取得したメタデータです。地理院地図掲載のすべてのレイヤーが参照できるわけではありません。また、この WMTS のメタデータは定期的に更新しておりますが、地理院地図の最新の情報が反映されていない場合がありますのでご了承ください。

## 動作環境

* ArcGIS Desktop バージョン 10.1 以降

## ライセンス
Copyright 2015 Esri Japan Corporation.

Apache License Version 2.0（「本ライセンス」）に基づいてライセンスされます。あなたがこのファイルを使用するためには、本ライセンスに従わなければなりません。本ライセンスのコピーは下記の場所から入手できます。

> http://www.apache.org/licenses/LICENSE-2.0

適用される法律または書面での同意によって命じられない限り、本ライセンスに基づいて頒布されるソフトウェアは、明示黙示を問わず、いかなる保証も条件もなしに「現状のまま」頒布されます。本ライセンスでの権利と制限を規定した文言については、本ライセンスを参照してください。

ライセンスのコピーは本リポジトリの[ライセンス ファイル](./LICENSE)で利用可能です。

[](EsriJapan Tags: <国土地理院 地理院タイル）>)
[](EsriJapan Language: <開発言語>)
