# GSI-WMTS-metadata

国土地理院が実施している「地理院タイルの WMTS メタデータ提供実験」を ArcGIS for Desktop で参照するために作成した WMTS メタデータです。ArcMap にこちらの WMTS サーバーを追加すると、地理院タイルとして公開されているレイヤーを参照できるようになります。</br>
※詳細は以下のリンク先をご確認ください（Esri 製品 サポート サイトへのログインが必要です）。</br>
<https://esrij-esri-support.custhelp.com/app/answers/detail/a_id/6548/>

- 地理院タイル一覧
<http://portal.cyberjapan.jp/help/development/ichiran.html>
- 地理院タイルのWMTSメタデータ提供実験
<https://github.com/gsi-cyberjapan/experimental_wmts>

## 使用方法

1. ArcMap を開きます。
2. [カタログ] ウィンドウにある [GIS Servers] フォルダーを展開し、[WMTS サーバーの追加] をダブルクリックします。
3. [WMTS サーバーの追加] ウィンドウの [URL] に以下の URL を入力し（それ以外は空欄）、[OK] をクリックします。

 <span style="FONT-WEIGHT: bold">地図・空中写真</span></br>
 [http://esrijapan.github.io/gsiwtms/chizu_shashin.xml](./chizu_shashin.xml)

 <span style="FONT-WEIGHT: bold">防災関連</span></br>
 [http://esrijapan.github.io/gsiwtms/bousai.xml](./bousai.xml)

4. [カタログ] ウィンドウの [GIS Servers] フォルダーに追加された「esrijapan.github.io」を展開し、ドラッグ &amp; ドロップで ArcMap にレイヤーを追加します。

## 動作環境

* ArcGIS for Desktop バージョン 10.1 以降

## ライセンス
Copyright 2015 Esri Japan Corporation.

Apache License Version 2.0（「本ライセンス」）に基づいてライセンスされます。あなたがこのファイルを使用するためには、本ライセンスに従わなければなりません。本ライセンスのコピーは下記の場所から入手できます。

> http://www.apache.org/licenses/LICENSE-2.0

適用される法律または書面での同意によって命じられない限り、本ライセンスに基づいて頒布されるソフトウェアは、明示黙示を問わず、いかなる保証も条件もなしに「現状のまま」頒布されます。本ライセンスでの権利と制限を規定した文言については、本ライセンスを参照してください。

ライセンスのコピーは本リポジトリの[ライセンス ファイル](./LICENSE)で利用可能です。

[](EsriJapan Tags: <国土地理院 地理院タイル）>)
[](EsriJapan Language: <開発言語>)
