# ADHSPK 組み立て説明書

## 内容物

まずは内容物の確認してください。  
足りない部品がある場合は、[お問い合わせ](https://bit-trade-one.co.jp/contactus/)ください。

### 内容物画像

[部品一覧画像]

### 部品表

| シルク              | 数量 | 部品                          |
|:-------------------  |:---:|:-----------------------------  |
| R1, R4, R5           |  3  | 10KΩ抵抗                       |
| R2, R6, R7, R10, R11 |  5  | 1KΩ抵抗                        |
| R3, R8, R9           |  3  | 1MΩ抵抗                        |
| C1, C2, C3           |  3  | 0.1uFセラミックコンデンサ       |
| Q1                   |  1  | 8550トランジスタ                |
| Q2, Q3, Q4           |  3  | 9013トランジスタ                |
| D1, D2, D3, D4       |  4  | LED発光ダイオード 赤、緑、青、黄 |
| SW                   |  1  | タクトスイッチ                  |
| BT1, BT2             |  2  | CR927ボタン電池ホルダー         |
||||
| -        |  1 | 基板  |
| -        |  2 | ケース 上下  |
| -        |  1 | ベアリング  |
| -        |  2 | ベアリングキャップ(持ち手)上下 |
| -        |  4 | タッピングネジ  |
| -        |  2 | CR927テスト電池 |


## はんだ付け

### 準備
- はんだこて、はんだこて台、スポンジ等のコテ先クリーナーを用意します。  
    はんだこては温度調節のあるものがオススメです。

- はんだを用意します。  
    0.8～1.0mmのはんだを使用します。近年では100円ショップでも手に入ります。  


### はんだ付け方法

![picture 2](../images/0871b5fa9714a0ada4cdef88f4b45fbd01df6736e91afb3d8dd41afc9b599def.png)  


1. ランドの予熱  
    基板側のはんだ付け箇所(上図では金色の部分)をランドと呼びます。
    ランドと部品の足にをはんだこてで軽く触れ(数秒)、予熱します。これにより、はんだがスムーズに流れるようになります。

2. はんだの供給  
    予熱したランドにはんだこての先を当てたまま、はんだをランドと部品の足に触れさせます。はんだが溶けて流れるのを確認しながら、適量を供給します。はんだこてに直接当てないことによりはんだに含まれるフラックス(はんだ付けを助ける接合助剤)の揮発を抑えられます。

3. 冷却  
    はんだがランドにしっかりと流れたら、はんだこてを離し、はんだが冷え固まるのを待ちます。

4. 確認  
    はんだ付けが完了したら、はんだの盛り上がりが適切であるか、部品の足とランドがしっかりと接合されているかを確認します。不十分な場合は、再度熱してください。 余分な長さの部品の足はニッパ等で切り落とします。

![picture 4](../images/411a115596765eb2d57d8e4ba4ae86dbf10240de6ae0be5d4d2ae86811ada949.png)  
富士山のような形のはんだ付けが正しいです。

### 注意点
- はんだ付け作業中は高温になるため、やけどに注意してください。
- はんだ煙は有害なので、換気を良くするか、煙を吸い込まないように注意してください。



## 部品実装

### 抵抗 1kΩ
基板上のシルクR2, R6, R7, R10, R11 に抵抗の足を折り曲げて差し込みます。
![picture 8](../images/d11b3c1725fdbef3b95f8823be5188eecd16c6e50a80f99b76a85867bd6548f3.png)  
ラジペン等で足を直角に曲げるとキレイに仕上がります。
![picture 5](../images/3c6eeaf53d1ad4e6d83c0ff1d388f4d45b82be2fd481ee426c7a0efc1cd72a9a.png)  

反対側は足を少し開き落ちないようにします。

![picture 6](../images/48fc1550910c005ff3ee720e3a30402b49fe9832ef56a8c8a23c7f35e3c751ce.png)  

片側づつはんだ付けを行い、部品が基板から浮いていないか確認しながらはんだ付けを行うと良いです。
はんだ付けが完了したら余分な部品の足は切り離してください。
これで1kΩ抵抗のはんだ付けは完了です。


### 抵抗 10kΩ

![picture 9](../images/f6d4eb6b8a4fd5528b5af48851fa944a746a70f1140954c4b3c034bc9d0b727e.png)  
基板上のシルクR1, R4, R5 に抵抗の足を折り曲げて差し込みます。

### 抵抗 1MΩ
基板上のシルクR3, R8, R9 に抵抗の足を折り曲げて差し込みます。
![picture 10](../images/c611625e43f4010e3e62efa5fae099a8c00b9b3eb5fc2f10246213405aabbe69.png)  


### 0.1uFセラミックコンデンサ (DIPコンデンサ 104)  

基板上のシルクC1, C2, C3 に本体を倒して差し込みます。

![picture 11](../images/4ba7d3084cf6cf5c224244c1510b58a9b1234e77b70187c8d56bdb7662af2259.png)  
このコンデンサは、表面に「104」と記載されています。これは容量を示しており、10という数字に後ろの4つのゼロを加えたもので、100000pF、つまり0.1uF（マイクロファラッド）の容量を意味します。セラミックコンデンサは極性がないため、どちら向きに挿しても問題ありません。

### 8550トランジスタ  
基板上のシルク Q1 に本体を倒して差し込みます。
部品表面に型番が書いてあるので9013とよく見て見分けてください。

![picture 13](../images/9d87bc02b6463417a2f034fdca6e1f3e9df79da4d61dedee429494a0d6fdf524.png)  


### 9013トランジスタ 
基板上のシルク Q2, Q3, Q4 に本体を倒して差し込みます。

![picture 14](../images/3e8db38446222a97b600ce95a04f5ac2ec6a219e8e7a52d4e9ecea9804b0b832.png)  


### CR927ボタン電池ホルダ
基板上のシルク BT1, BT2 に差し込みます。
とても傾きやすいので片側づつはんだ付けを行い、部品が基板から浮いていないか確認しながらはんだ付けを行うと良いです。
![picture 16](../images/6ff5f2e25346dfc3847783a76ecaf4e2aa91812b3387e9aa837292521b0dd7b8.png)  



### タクトスイッチ
SW(裏面)
![picture 18](../images/7223add66293c64d78a1be6dbc1da71a7459240d61e25806a9840d2d2382bf59.png)  

表面実装に挑戦！
これまでの組み立てでは、主にDIP (Dual In-line Package) 部品を実装してきました。DIPは部品の足を基板の穴に通して裏側からはんだ付けする方法で、初心者にも扱いやすく、基板上での位置決めがしやすい特徴があります。

しかし、本項のタクトスイッチを通じて、SMD (Surface-Mount Device) という実装方法にも触れます。SMDは部品を基板の表面に直接載せてはんだ付けする技術で、小型の部品を密集させることができますが、はんだ付けの際にはピンセットで部品を正確に配置し、慎重にはんだ付けする必要があります。


部品の取り扱いやはんだ付けに注意しながらSMD実装の挑戦してみましょう。

#### 表面実装方法
①4つの内1つのランドに若干ハンダを盛ります。 これを予備はんだと呼びます。  
②予備はんだを再度熱しつつ、ピンセットで掴んだスイッチをスライドさせてはんだ付けを行います。曲がってしまった場合ははんだを再度熱し角度を調節してください。  
③位置が決まったら空いてるランドにもはんだ付けを行い完了です。 必要に応じて予備はんだした箇所にもはんだを足してください。 
![picture 17](../images/90d1b653b1ec3058f648c5757a65d3bc99a9a46f3117851064c41b887e884caf.jpg)  


### LED
基板上のシルクD1, D2, D3, D4にLEDを差し込みます。
![picture 20](../images/1fa601a4b87c981004e2c86568ef7353480d51d403c7f1fe427e6a5cc3f3a4ff.png)  

LEDはダイオードという部品のため極性があります。
長い足がプラス側(アノード)、短い足がマイナス側(カソード)です。**基板に印刷されている+記号に注意して、正しい向きに挿入してください。**

また、点灯しないと色がわからないため、本体にテスト電池を挿入し、裏面SWを押し導通された状態にしてLEDをD1～D4いずれかのランドに当ててみることにより発光し色がわかります。D1～D4どこに何色を差しても問題ないので好きな順番ではんだ付けを行ってください。

![picture 19](../images/0d3a1646dcf2ca8447a528dfd3c810d3960d04b7adbf592e22e447fcb1680863.png)  

電池が入った状態でSWを押すたびにLEDの点灯・消灯が切り替われば回路は完成です。  
うまく動かない場合はハンダ不良等が無いか再度確認してください。

## 組み立て
下記画像のように差し込んでゆき、組み立てを行います。  
基板のスイッチ面とケースのスイッチ箇所が正しいか注意してください。
![picture 22](../images/ce6ac699ea4ea9ea463306cb62afcde2306dd5ba5d5db28f53ffc053ce908806.png)  

うまくハマったら完成です。  
付属のタッピングネジを取り付けると剛性が上がりますが、電池交換が難しくなるのでタイミングを見てネジの取り付けを行ってください。
![picture 21](../images/5ead0d33c7f66795402f509dd0820f51a7edd9898e7805dbe45a195c0c56ebc4.jpg)  

**これでハンドスピナーは完成です。お疲れ様でした。**  
回転させていないとただの点灯に見えたLEDですが、回転すると光が点滅していることがわかります。  
このLEDの点滅はこれまではんだ付けしていた「非安定マルチバイブレータ」という回路で実現しています。

## 回路について

![picture 23](../images/f246ef0debfeca26395abf9104df622cf1832947e3c5b6cacc8680c100d47f3f.png)  

### 使用電子部品

#### トランジスタ

- 電流を増幅したり、スイッチとして動作したりする半導体素子です。
- 非安定マルチバイブレータでは、2つのトランジスタが交互にオン/オフを繰り返すことで、パルス信号を生成します。
- トランジスタには、ベース、コレクタ、エミッタの3つの端子があり、ベースに流れる小さな電流で、コレクタとエミッタ間の大きな電流を制御できます。

- トランジスタにはNPN型とPNP型の2種類があります。

    - **NPN型トランジスタ**は、ベースに正の電圧を加えることでコレクタからエミッタへ電流が流れるようになります。

    - **PNP型トランジスタ**は、NPN型とは逆に、ベースに負の電圧を加えることでエミッタからコレクタへ電流が流れます。


#### 抵抗
- 電流を制限したり、電圧を分圧したりする受動素子です。
- 非安定マルチバイブレータでは、トランジスタのベースに接続された抵抗は、ベース電流を制限し、コレクタに接続された抵抗は、コレクタ電圧を決定します。抵抗値を変えることで、パルス幅を調整できます。

#### コンデンサ
- 電荷を蓄えたり、放出したりする受動素子です。
- 非安定マルチバイブレータでは、コンデンサは、トランジスタのベースとコレクタの間に接続され、充電と放電を繰り返すことで、パルス信号の時間を制御します。コンデンサの容量を変えることで、パルス幅を調整できます。

#### LED (発光ダイオード)
- 電流が流れると発光する半導体素子です。
- LEDは、順方向電流によって発光し、逆方向電流では発光しません。
- 非安定マルチバイブレータの出力をLEDに接続することで、パルス信号に同期して点滅させることができます。

#### 電池
- 回路に電力を供給する直流電源です。
- 非安定マルチバイブレータを動作させるために、適切な電圧の電池を使用します。
- 電池の電圧は、トランジスタの動作電圧や他の部品の定格電圧に合わせて選択する必要があります。容量は、回路の消費電力と動作時間に応じて選択します。

### 点灯・消灯回路の簡易説明

![picture 26](../images/94966cfc1960d9eb66f8237f73ab7d8109099fdbb02d4b27b4cf8bc1722f5181.png)  

この回路は、ボタン（S1）を押すごとにLEDの点灯・消灯を切り替えます。トランジスタQ1（PNP型）とQ2（NPN型）は、このトグル動作を実現するために使用されています。

#### 回路の動作の詳細な説明
- **ボタンS1を押したとき:**
  - S1を押すと、Q2のベースに電圧がかかり、Q2が飽和状態になります（オン）。Q2がオンになると、Q1のベースにも電圧がかかり、Q1も飽和状態になります（オン）。これにより、LEDに電流が流れ、点灯します。
- **ボタンS1をもう一度押したとき:**
  - S1を再度押すと、Q2のベースから電圧が取り除かれ、Q2はカットオフ状態になります（オフ）。これにより、Q1のベースからも電圧が取り除かれ、Q1もカットオフ状態になります（オフ）。結果として、LEDへ電流が流れなくなり、消灯します。



### 非安定マルチバイブレータ回路

![picture 27](../images/d0e88910cb57590f26824b302ce17690d5435bec9c327419e3e77aef26616956.png)  

右側の非安定マルチバイブレータは、トランジスタのスイッチング動作とコンデンサの充電・放電を利用して、一定の幅のパルスを生成する回路です。

#### 回路の動作
- **初期状態:** 電源投入時、トランジスタの特性のばらつきやノイズの影響で、左右のトランジスタに流れる電流が異なります。これにより、一方のトランジスタがオン状態になり、もう一方がオフ状態になります。
- **スイッチング動作:** オン状態のトランジスタがコンデンサを通じて充電を開始し、そのコンデンサの電圧がトランジスタのベース・エミッタ間の閾値電圧を超えると、トランジスタのオン/オフ状態が切り替わります。これにより、反対側のトランジスタがオンになり、先にオンだったトランジスタがオフになります。
- **パルス生成:** このスイッチング動作が繰り返されることで、トランジスタのコレクタで互い違いのパルス波形が得られます。パルス幅は、抵抗とコンデンサの値によって決まりますが、部品の誤差や温度の影響を受けます。

#### 部品の性能のばらつきについて
- **性能のばらつき:** トランジスタ、抵抗、コンデンサの性能は製造上の理由から完全に同じではありません。これが回路の動作に影響を与え、パルスの幅が設計した値からずれることがあります。
- **温度の影響:** 温度が変化すると、特にトランジスタの性能が影響を受け、パルスの幅が変化することがあります。
- **対策:** これらのずれを最小限に抑えるために、性能のばらつきが少ない高精度の部品を使用したり、回路を設計する際にずれの影響を考慮したりすることが重要です。必要に応じて、温度の影響を補正する回路を追加することもあります。