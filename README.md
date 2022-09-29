# 🐐 GOAT51 🐐

<img src="https://github.com/takashicompany/goat51/blob/master/images/01.jpg?raw=true" width="600px" />

GOAT51は51キーのキーボードです。  
特徴的な放射状のキーレイアウトは指を自然に置くことができ、効率的な入力が可能です。  
MX互換のキースイッチとChoc v1キースイッチの取り付けに対応しております。  
またPCBにキースイッチソケットを取り付けることが可能で、容易にキースイッチの交換ができます。  
キーボードの中央にはお気に入りのキーキャップを取り付ける専用スペースがあり、アルチザンキーキャップやお気に入りのキーキャップを飾ることができます。  

---

GOAT51 is a 51-key keyboard.  
The distinctive radial key layout allows the fingers to be placed naturally for efficient typing.  
It supports the installation of MX compatible key switches and Choc v1 key switches.  
A key switch socket can also be installed on the PCB for easy keyswitch replacement.  
There is a dedicated space in the center of the keyboard for mounting your favorite keycaps, allowing you to display Artisan keycaps or your favorite keycaps.  

## キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|キースイッチプレート|1|5mm厚の場合は、Cherry MX互換キースイッチのみ取付可能|
|ボトムプレート|1||
|中央トッププレート|1||
|中央積層プレート|1||
|ダイオード|51||
|m2スペーサー(シルバー4mm)|8||
|m2トラスネジ(シルバー3mm)|8||
|m2ネジ(ゴールド）(8mm)|4||
|m2ネジ(ゴールド)18mm)|4||
|リセットスイッチ|1||
|MXソケット|1||
|滑り止めシール|6||

### 別途用意するもの
|部品|個数|備考|
|:--|:--|:--|
|キースイッチ|51|Cherry MX互換のもの。|
|キーキャップ|51|全て1uで取付可能。一部キーのみ、1.25u、1.5uがあると望ましい。|
|Pro Micro|1||
|USBケーブル|1|Pro MicroとPCを接続します。|

### オプション
|部品|個数|備考|
|:--|:--|:--|
|コンスルー|2|12pin、13pinに対応しておりますのでMCU(Pro Micro)にあわせて選択が可能です。|
|MXソケット|50|中央のキー以外は、キースイッチのはんだ付け/MXソケットによる挿し込みの両方に対応。|
|LED(SK6812MINI-E)|1|中央のキーとキーボード手前側の穴をバックライトで光らせることができます。|
|LED(WS2812B)|10|アンダーグロウライトとしてキーボードの底面を光らせることができます。|

## 組み立て方

### 1. PCBの表裏を確認する

#### 表
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1692.jpg?raw=true" width="600px"/>

#### 裏
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1694.jpg?raw=true" width="600px"/>

### 2. ダイオードをはんだ付けする

PCBの表面にハンダが漏れないようにマスキングテープを貼ります。  
ハンダがPCB表面に漏れてしまうと、キースイッチプレートを安定して取り付けられなくなる可能性があります。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1695.jpg?raw=true" width="600px"/>

ダイオードの取り付け位置と向きを確認します。  
下記の写真と同様にダイオードの線と`▷|`の向きが合うように配置してください。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1697.jpg?raw=true" width="600px"/>

ハンダ付け位置の片方にハンダを盛っておきます(予備ハンダ)。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1699.jpg?raw=true" width="600px"/>

ピンセットでダイオードを持ちながら予備ハンダを溶かしながらダイオードをハンダ付けします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1700.jpg?raw=true" width="600px"/>

もう片方もハンダ付けをします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1701.jpg?raw=true" width="600px"/>

Rev1 PCBの中央のキースイッチだけ向きが逆なのでご注意ください。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1702.jpg?raw=true" width="600px"/>

全部で51個のダイオードを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1703.jpg?raw=true" width="600px"/>

PCBの表面にハンダが漏れて盛り上がっていないことを確認します。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1704.jpg?raw=true" width="600px"/>

### 3. リセットスイッチの取り付け

リセットスイッチの取り付け位置を確認します。  
位置は基盤の裏側中央手前側です。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1705.jpg?raw=true" width="600px"/>

リセットスイッチを差し込みます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1706.jpg?raw=true" width="600px"/>

PCB表側からリセットスイッチの足が出ていることを確認します。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1707.jpg?raw=true" width="600px"/>

リセットスイッチの足をハンダ付けします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1708.jpg?raw=true" width="600px"/>

### 3. Pro Microの取り付け

Pro Microを取り付けます。  
PCBはコンスルーに対応しております。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1709.jpg?raw=true" width="600px"/>

### 4. ファームウェアの書き込み

[Remap用のファームウェア](https://remap-keys.app/catalog/eEYpy3syWDyEpwthc8kC/firmware)を用意しております。
QMKへのプルリクエストは[こちら](https://github.com/qmk/qmk_firmware/pull/18220)です。

### 5. LEDの取り付け

LEDの取り付けは後回しにしても大丈夫です。  
SK6812MINI-Eを中央のキースイッチ部分に取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1787.jpg?raw=true" width="600px"/>
   
SK6812MINI-Eの足が一部欠けている部分が白線がついているハンダ付け箇所に来るように向きを調整してください。  
SK6812MINI-Eの発光部分がPCB表側に来るように置きます。
SK6812MINI-Eのハンダ付け箇所の一つに予備ハンダをします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1789.jpg?raw=true" width="600px"/>

予備ハンダを溶かしながら、SK6812MINI-Eの足をハンダ付けしていきます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1790.jpg?raw=true" width="600px"/>

残りの箇所も順次ハンダ付けを行います。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1793.jpg?raw=true" width="600px"/>

USBを繋いでSK6812MINI-Eが点灯するかを確認します。  
点灯しない場合は`RGB_TOG`キーを押してみてください。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1799.jpg?raw=true" width="600px"/>

WS2812BをLED2番から11番に取り付けます。  
WS2812Bの角の欠けた部分がLEDの印刷箇所と合うように向きを調整します。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1792.jpg?raw=true" width="600px"/>

WS2812Bのハンダ付け箇所の一つに予備ハンダをします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1794.jpg?raw=true" width="600px"/>

予備ハンダを溶かしながらWS2812Bを取り付けます。  
残りの箇所もハンダ付けをします。一つのWS2812Bにつき4箇所ハンダ付けします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1796.jpg?raw=true" width="600px"/>

全てのLEDを付け終わったらUSBを繋いで点灯するかを確認してください。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1800.jpg?raw=true" width="600px"/>

### 6. キースイッチの取り付け

GOAT51は、キースイッチの取り付けは

- PCBに直にキースイッチをハンダ付けする
- PCBにキースイッチソケットを取り付けて、キースイッチソケットにキースイッチを挿す

の二通りに対応しております。

(スイッチプレートが5mm厚の場合はMX互換のキースイッチのみ取付可能。)

中央のキースイッチのみ、MX用のキースイッチソケットを取り付ける必要があります。

キースイッチソケットの印刷とキースイッチソケットの向きが合うことを確認します。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1801.jpg?raw=true" width="600px"/>

キースイッチソケットのハンダ付け箇所の片側に予備ハンダを行います。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1802.jpg?raw=true" width="600px"/>

予備ハンダを溶かしながらキースイッチソケットをハンダ付けします。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1803.jpg?raw=true" width="600px"/>

もう片方もハンダ付けを行います。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1804.jpg?raw=true" width="600px"/>

全部で51個のキースイッチを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1805.jpg?raw=true" width="600px"/>

### 7. キースイッチプレートの取り付け

キースイッチプレートを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1806.jpg?raw=true" width="600px"/>

保護シートを剥がして、PCBの表側にキースイッチプレートを置きます。  
左右対称なので、お好きな面を表にしてください。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1812.jpg?raw=true" width="600px"/>

### 8. キースイッチの取り付け

キースイッチをキースイッチプレートに取り付けます。  
全部で51箇所になります。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1815.jpg?raw=true" width="600px"/>

### 9. ボトムプレートの取り付け

ボトムプレートを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1808.jpg?raw=true" width="600px"/>

取り付けには4mmのスペーサーと4mmのネジを使います。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1817.jpg?raw=true" width="600px"/>

ボトムプレートにスペーサーとネジを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1819.jpg?raw=true" width="600px"/>

保護シートを剥がして、中央プレートを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1811.jpg?raw=true" width="600px"/>

中央プレートは18mmのネジで固定します。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1822.jpg?raw=true" width="600px"/>

その他の箇所は8mmのネジでキースイッチプレートとスペーサーを取り付けます。
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1821.jpg?raw=true" width="600px"/>

下図のようにキースイッチプレートとボトムプレートをスペーサーで固定できれば完成です。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1825.jpg?raw=true" width="600px"/>

### 10.　キーキャップの取り付け

キーキャップを取り付けます。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1827.jpg?raw=true" width="600px"/>

### 11. ゴム足シールの取り付け

ボトムプレートにゴム足シールを取り付けて完成です。  
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1828.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
<img src = "https://github.com/takashicompany/goat51/blob/master/images/build/IMG_1.jpg?raw=true" width="600px"/>
