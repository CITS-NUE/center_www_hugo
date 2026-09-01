---
title: ネットワーク
toc: true
weight: 40
draft: false
summary: 学内における情報伝達のインフラを構成しています。学内ネットワークシステムが提供する各種サービスが利用できます。
---
鳴門教育大学と各附属校園を結ぶ情報ネットワークです。情報伝達のインフラを構成するとともに，提供する各種サービスの利用を可能にしています。

学内に設置の情報コンセントや無線LANを利用して，ネットワークに接続できます。

## 利用時の設定
### IPアドレスの設定
**「自動取得，DHCPより取得」** としてください。学内のDHCPサーバにより，接続のたびにIPアドレスが割り振られます。

> 固定IPアドレスの割り当てを希望される方は，[ネットワーク接続申請](https://forms.office.com/r/kQxFyj0NxS)してください。

### プロキシサーバの設定
**「自動検出」** としてください。自動検出に非対応の機種もあります。設定手順に従ってください。スマートフォンやタブレットを使用する場合も，プロキシサーバの設定が必要です。

[プロキシ設定方法(学内向けページ)](https://narutouacjp.sharepoint.com/:fl:/g/contentstorage/CSP_bef118a8-b283-4a15-9667-aef442911190/IQAZI6WAA_kLR6bbhVJNtaFcARsUYpwpPyEj0J38jEMaoK8?e=LfcrF9&nav=cz0lMkZjb250ZW50c3RvcmFnZSUyRkNTUF9iZWYxMThhOC1iMjgzLTRhMTUtOTY2Ny1hZWY0NDI5MTExOTAmZD1iJTIxcUJqeHZvT3lGVXFXWjY3MFFwRVJrQ2xuTVpyaU5rdEF2ZXlCeVljWTExSEtJcXVHaVgxQlFiRXZkenE4ME8xSCZmPTAxRFczSjVTSVpFT1NZQUE3WkJORDJOVzRGS0pHM0xJSzQmYz0lMkYmYT1Mb29wQXBwJnA9JTQwZmx1aWR4JTJGbG9vcC1wYWdlLWNvbnRhaW5lciZ4PSU3QiUyMnclMjIlM0ElMjJUMFJUVUh4dVlYSjFkRzkxWVdOcWNDNXphR0Z5WlhCdmFXNTBMbU52Ylh4aUlYRkNhbmgyYjA5NVJsVnhWMW8yTnpCUmNFVlNhME5zYmsxYWNtbE9hM1JCZG1WNVFubFpZMWt4TVVoTFNYRjFSMmxZTVVKUllrVjJaSHB4T0RCUE1VaDhNREZFVnpOS05WTkxOVTFhV0VGUVF6WlBRVlpFU2pkVlJVVldNazFTTTFwRk53JTNEJTNEJTIyJTJDJTIyaSUyMiUzQSUyMjRjNGRlYzAwLTRkMjctNDFjMC1iNTY2LTM0NmM4OWU4ZjUyZCUyMiU3RA%3D%3D)

プロキシサーバは，インターネット上のファイルやウェブページ等をユーザの代理（プロキシ）で取得してくれる機能を持つサーバです。適切なプロキシ（代理）サーバを設定することで，インターネットの接続が最適化され，ウイルスチェックも行われます。適切に設定されていないと，次のような症状が発生することがありますので，注意してください。

- 授業実践映像データベースの画像やYouTube，Netflixが見えない。
- 無線LAN利用時に学外もしくは学内のサイトへアクセスできない。

## 情報コンセントへの接続（有線LAN）
- 学内の各部屋や端末室に，情報コンセントを設置しています。
- LANケーブルを挿して接続してください。
- 認証はありません。

### 留意事項
- 情報コンセントへ接続する室内の配線や機器は，利用者において管理してください。
- 部屋の利用目的を変更する場合は，情報基盤センターへご相談ください。室内の LAN 配線の変更だけでは，正常に動作しない場合があります（例：事務用ネットワークから学術研究用ネットワークに変更する場合）。

## 無線LANへの接続 (Connect to Wireless LAN)
- 大学および附属学校園で利用できます。
- Wireless LAN is available on the university campus and the attached schools.

| SSID | 利用場所 | 補記 |
|:-----|:-----|:-----|
| INDIGO | 大学，附属学校園 | |
| GIGA | 附属学校園 | 生徒用 |
| eduroam | 大学 | [eduroamについて]({{< ref "gakunin#eduroam" >}}) |

### INDIGO，GIGA の仕様
- 規格：IEEE802.11a/ac/ax
- 認証方式：WPA2-Enterprise + PEAP(MSCHAPv2)
- 暗号化の種類：AES

### INDIGO，GIGA の設定情報
- ID：ユーザID（学籍番号／教職員番号）（@naruto-u.ac.jp不要 Domain name '@naruto-u.ac.jp' is Unnecessary）
- パスワード：ユーザIDのパスワード
- ドメイン：naruto-u.ac.jp
- CA証明書：システム証明書を使用 (Use system certificates)

> 一度設定すると，端末が認証情報を記憶しますので，次回からは入力する必要はありません。
>
> Once your device has authenticated successfully, it remembers your credentials, so you do not need to enter your user ID and password again.

### 留意事項
- アプリケーションの一部は通信制限があります。
- INDIGOはキャンパス内をあまねくカバーするシステムではありませんが，教員研究室や講義・ゼミ室などは優先して整備を行っています。必要な場所へ電波が届いていない場合は，情報基盤センターへご相談ください。
- 学内の研究室や院生室などに無線LANアクセスポイントを設置する場合は，情報基盤センターへご相談ください。電波資源は有限であり，電波を発信すれば一定の空間内に影響を与えます。例えば，情報基盤センターで整備した無線LANも，他者が設置した基地局（AP）の電波の影響を受け，チャンネルが隣接した場合は干渉などの影響を受けます。

### ゲスト用WiFi
1. 学会や研究会などの際，学外者が利用可能な無線LANを提供できます。
   - SSID：申請時に指定
   - 利用場所：B棟，F会議室，大学会館
   - 認証方式：WPA2
   - [ゲスト用WiFi 申請](https://forms.office.com/r/VPk9yiYniX)
2. プロキシを利用しないWiFiルータ貸出サービスを，試験的に提供しています。プロキシ対応しない機器や，INDIGOの認証方式に対応しない機器に利用可能です。大学および附属学校園の，有線LANコンセントがある場所で利用できます。情報基盤センターへご相談ください。

### DNS登録
naruto-u.ac.jp ドメインの A レコードに登録します。学内に設置するサーバに対して，naruto-u.ac.jp ドメインのホスト名を割り当てます。運用者が学生や外部業者の場合は，担当教職員が申請してください。

[DNS Aレコード登録](https://forms.office.com/r/UVP7XUG7Ar)

### 学外からの接続
学外から，学内に設置されたシステムやサーバにアクセスできます。学生が利用する場合は，担当教職員が申請してください。

[学外からの接続 申請](https://forms.office.com/Pages/ResponsePage.aspx?id=SA2VUq_p-EmxBHt7Ov-Vp7GrcYwHVXVDg3QqFGvLZXpUQjRDRDBZV05DU0NRUENIUTlWR0JCTkJXNC4u)
