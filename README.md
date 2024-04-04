# ADHSPK 組み立て説明書
<!-- 編集の際はこちらのREADME.mdを編集してもらえると勝手にデプロイされます。 -->

## 必要な道具
- はんだこて
- はんだ（0.8～1.0mm推奨）
- ニッパー

## あると便利なもの
- はんだこて台
- スポンジまたはコテ先クリーナー
- ラジオペンチ
- ピンセット
- テスター

## 内容物

まずは内容物の確認してください。  
足りない部品がある場合は、[お問い合わせ](https://bit-trade-one.co.jp/contactus/)ください。

### 内容物画像

<!-- ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/8c739fff-fc55-4297-8bd1-ce66be1bb7ab) -->!


<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/8c739fff-fc55-4297-8bd1-ce66be1bb7ab"  width="600" >


### 部品表

| シルク              | 数量 | 部品                          |
|:-------------------  |:---:|:-----------------------------  |
| R1, R4, R5           |  3  | 10KΩ抵抗 (茶黒橙金)             |
| R2, R6, R7, R10, R11 |  5  | 1KΩ抵抗  (茶黒赤金)             |
| R3, R8, R9           |  3  | 1MΩ抵抗  (茶黒緑金)             |
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

> 💡 **TIP:** 抵抗のカラーコードは、抵抗の値を色で表したものです。各色は特定の数字を表し、通常は4つの帯で構成されます。最初の2つの帯は抵抗の値を示し、3つ目の帯は乗数（何桁増やすか）、4つ目の帯は許容誤差を示します。例えば、**茶黒橙金**の場合、`1(茶)0(黒)×10^3(橙)`、許容誤差`±5%(金)`となり、`10KΩ`の抵抗を意味します。
>   
> また、これらの抵抗値はテスターを使用して計測することも可能です。特に、部品の識別が難しい場合や、カラーコードが読み取りにくい場合には、テスターでの確認をお勧めします。



## はんだ付け

### 準備
- はんだこて、はんだこて台、スポンジ等のコテ先クリーナーを用意します。  
    はんだこては温度調節のあるものがオススメです。

- はんだを用意します。  
    0.8～1.0mmのはんだを使用します。近年では100円ショップでも手に入ります。  


### はんだ付け方法

<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/4c119683-7089-4bfa-83ac-97eec973dfa4)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/4c119683-7089-4bfa-83ac-97eec973dfa4"  width="600" >



1. ランドの予熱  
    基板側のはんだ付け箇所(上図では金色の部分)をランドと呼びます。
    ランドと部品の足にはんだこてで軽く触れ(数秒)、予熱します。これにより、はんだがスムーズに流れるようになります。

2. はんだの供給  
    予熱したランドにはんだこての先を当てたまま、はんだをランドと部品の足に触れさせます。はんだが溶けて流れるのを確認しながら、適量を供給します。  
   はんだこてに直接当てないことによりはんだに含まれるフラックス(はんだ付けを助ける接合助剤)の揮発を抑えられます。

4. 冷却  
    はんだがランドにしっかりと流れたら、はんだこてを離し、はんだが冷え固まるのを待ちます。

5. 確認  
    はんだ付けが完了したら、はんだの盛り上がりが適切であるか、部品の足とランドがしっかりと接合されているかを確認します。不十分な場合は、再度熱してください。  
    余分な長さの部品の足はニッパ等で切り落とします。

<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/bf98cc4a-ed8b-4b13-b897-040dc0b9d2a9)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/bf98cc4a-ed8b-4b13-b897-040dc0b9d2a9"  width="600" >

富士山のような形のはんだ付けが正しいです。☓の不良なはんだ付けはイモハンダ等と呼ばれます。

### 注意点
- はんだ付け作業中は高温になるため、やけどに注意してください。
- はんだ煙は有害なので、換気を良くするか、煙を吸い込まないように注意してください。



## 部品実装

### 抵抗 1kΩ
基板上のシルクR2, R6, R7, R10, R11 に抵抗の足を折り曲げて差し込みます。
<!--  ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/0c114c73-9502-4c88-b86d-762054a3666e)
 -->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/0c114c73-9502-4c88-b86d-762054a3666e"  width="600" >

ラジペン等で足を直角に曲げるとキレイに仕上がります。
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/cbd2daf6-2ffe-4907-8108-3d73bf2e6630)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/cbd2daf6-2ffe-4907-8108-3d73bf2e6630"  width="600" >


反対側は足を少し開き落ちないようにします。

<!--   ![48fc1550910c005ff3ee720e3a30402b49fe9832ef56a8c8a23c7f35e3c751ce](https://github.com/bit-trade-one/ADHSPK/assets/85532743/2cacdf71-31a6-48e2-906a-346250124a0f)

-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/2cacdf71-31a6-48e2-906a-346250124a0f"  width="600" >


片側づつはんだ付けを行い、部品が基板から浮いていないか確認しながらはんだ付けを行うと良いです。  
はんだ付けが完了したら余分な部品の足は切り離してください。  
これで1kΩ抵抗のはんだ付けは完了です。  


### 抵抗 10kΩ

<!--  ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/9f93fdad-a6d2-46e6-8bbd-acab3d57162f)

-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/9f93fdad-a6d2-46e6-8bbd-acab3d57162f"  width="600" >

基板上のシルクR1, R4, R5 に抵抗の足を折り曲げて差し込みます。

### 抵抗 1MΩ
基板上のシルクR3, R8, R9 に抵抗の足を折り曲げて差し込みます。
<!-- ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/2c4e053b-05bf-491b-806a-96f41b4cdd27)
 -->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/2c4e053b-05bf-491b-806a-96f41b4cdd27"  width="600" >



### 0.1uFセラミックコンデンサ (DIPコンデンサ 104)  

基板上のシルクC1, C2, C3 に本体を倒して差し込みます。

<!--  ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/cfcf1abe-1abe-4996-b461-72109ee4ce28)
-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/cfcf1abe-1abe-4996-b461-72109ee4ce28"  width="600" >

このコンデンサは、表面に「104」と記載されています。これは容量を示しており、10という数字に後ろの4つのゼロを加えたもので、100000pF、つまり0.1uF（マイクロファラッド）の容量を意味します。

### 8550トランジスタ  
基板上のシルク Q1 に本体を倒して差し込みます。
部品表面に型番が書いてあるので9013とよく見て見分けてください。

<!--  ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/b630ee6d-f62d-4d94-9aa7-b754175e7849)
-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/b630ee6d-f62d-4d94-9aa7-b754175e7849"  width="600" >



### 9013トランジスタ 
基板上のシルク Q2, Q3, Q4 に本体を倒して差し込みます。

<!--  ![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/24536e1d-3c73-44f1-b334-2b0977c1717b)
 -->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/24536e1d-3c73-44f1-b334-2b0977c1717b"  width="600" >



### CR927ボタン電池ホルダ
基板上のシルク BT1, BT2 に差し込みます。
とても傾きやすいので片側づつはんだ付けを行い、部品が基板から浮いていないか確認しながらはんだ付けを行うと良いです。
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/780fc7e8-090a-4df4-a59a-89319e1d9d59)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/780fc7e8-090a-4df4-a59a-89319e1d9d59"  width="600" >




### タクトスイッチ
SW(裏面)
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/739a47cf-f287-49af-ac94-35d6f17c7465)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/739a47cf-f287-49af-ac94-35d6f17c7465"  width="600" >


表面実装に挑戦！
これまでの組み立てでは、主にDIP (Dual In-line Package) 部品を実装してきました。DIPは部品の足を基板の穴に通して裏側からはんだ付けする方法で、初心者にも扱いやすく、基板上での位置決めがしやすい特徴があります。

しかし、本項のタクトスイッチを通じて、SMD (Surface-Mount Device) という実装方法にも触れます。SMDは部品を基板の表面に直接載せてはんだ付けする技術で、小型の部品を密集させることができますが、はんだ付けの際にはピンセット等で部品を正確に配置し、慎重にはんだ付けする必要があります。


部品の取り扱いやはんだ付けに注意しながらSMD実装の挑戦してみましょう。

#### 表面実装方法
①4つの内1つのランドに若干ハンダを盛ります。 これを予備はんだと呼びます。  
②予備はんだを再度熱しつつ、ピンセット等で掴んだスイッチをスライドさせてはんだ付けを行います。曲がってしまった場合ははんだを再度熱し角度を調節してください。  
③位置が決まったら空いてるランドにもはんだ付けを行い完了です。 必要に応じて予備はんだした箇所にもはんだを足してください。 
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/edc5d042-2ab7-4811-b26c-50251e23c5ff)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/edc5d042-2ab7-4811-b26c-50251e23c5ff"  width="600" >



### LED
基板上のシルクD1, D2, D3, D4にLEDを差し込みます。
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/53aad21f-e890-40dc-8504-7af2c2924e20)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/53aad21f-e890-40dc-8504-7af2c2924e20"  width="600" >


LEDはダイオードという部品のため極性があります。
長い足がプラス側(アノード)、短い足がマイナス側(カソード)です。**基板に印刷されている+記号に注意して、正しい向きに挿入してください。**

また、点灯しないと色がわからないため、本体にテスト電池を挿入し、裏面SWを押し導通された状態にしてLEDをD1～D4いずれかのランドに当ててみることにより発光し色がわかります。  
D1～D4どこに何色を差しても問題ないので好きな順番ではんだ付けを行ってください。

<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/9d03e22b-4492-4b37-8e31-5e48b979f59a)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/9d03e22b-4492-4b37-8e31-5e48b979f59a"  width="600" >


電池が入った状態でSWを押すたびにLEDの点灯・消灯が切り替われば回路は完成です。  
うまく動かない場合はハンダ不良等が無いか再度確認してください。

## 組み立て
下記画像のように差し込んでゆき、組み立てを行います。  
基板のスイッチ面とケースのスイッチ箇所が正しいか注意してください。
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/212c2f96-7bd9-4b67-8b49-b3750ec1103b)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/212c2f96-7bd9-4b67-8b49-b3750ec1103b"  width="600" >


うまくハマったら完成です。  
付属のタッピングネジを取り付けると剛性が上がりますが、電池交換が難しくなるのでタイミングを見てネジの取り付けを行ってください。
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/ed00f356-71aa-4166-91b3-d790f41269a6)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/ed00f356-71aa-4166-91b3-d790f41269a6"  width="600" >


**これでハンドスピナーは完成です。お疲れ様でした。**  
回転させていないとただの点灯に見えたLEDですが、回転すると光が点滅していることがわかります。  
このLEDの点滅はこれまではんだ付けしていた「非安定マルチバイブレータ」という回路で実現しています。  
  
こだわりたい方はここの空きランドにハンダを盛って重心を変えることも可能です。
<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/a2bf0909-79ff-4151-80df-6d9bc1e3a78a)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/a2bf0909-79ff-4151-80df-6d9bc1e3a78a"  width="600" >


## 回路について

<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/bc6624b4-5380-4bdd-abfd-3ff4771f72a9)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/bc6624b4-5380-4bdd-abfd-3ff4771f72a9"  width="600" >


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

<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/0ffb3c1b-fad5-492a-a5d3-b4f8dc6af2b3)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/0ffb3c1b-fad5-492a-a5d3-b4f8dc6af2b3"  width="600" >


この回路は、ボタン（S1）を押すごとにLEDの点灯・消灯を切り替えます。トランジスタQ1（PNP型）とQ2（NPN型）は、このトグル動作を実現するために使用されています。

#### 回路の動作の詳細な説明
- **ボタンS1を押したとき:**
  - S1を押すと、Q2のベースに電圧がかかり、Q2が飽和状態になります（オン）。Q2がオンになると、Q1のベースにも電圧がかかり、Q1も飽和状態になります（オン）。これにより、LEDに電流が流れ、点灯します。
- **ボタンS1をもう一度押したとき:**
  - S1を再度押すと、Q2のベースから電圧が取り除かれ、Q2はカットオフ状態になります（オフ）。これにより、Q1のベースからも電圧が取り除かれ、Q1もカットオフ状態になります（オフ）。結果として、LEDへ電流が流れなくなり、消灯します。



### 非安定マルチバイブレータ回路

<!--![image](https://github.com/bit-trade-one/ADHSPK/assets/85532743/6f4955ee-219c-447a-9c63-544ed7f23f4b)-->
<img src="https://github.com/bit-trade-one/ADHSPK/assets/85532743/6f4955ee-219c-447a-9c63-544ed7f23f4b"  width="600" >


右側の非安定マルチバイブレータは、トランジスタのスイッチング動作とコンデンサの充電・放電を利用して、一定の幅のパルスを生成する回路です。

#### 回路の動作
- **初期状態:** 電源投入時、トランジスタの特性のばらつきやノイズの影響で、左右のトランジスタに流れる電流が異なります。これにより、一方のトランジスタがオン状態になり、もう一方がオフ状態になります。
- **スイッチング動作:** オン状態のトランジスタがコンデンサを通じて充電を開始し、そのコンデンサの電圧がトランジスタのベース・エミッタ間の閾値電圧を超えると、トランジスタのオン/オフ状態が切り替わります。これにより、反対側のトランジスタがオンになり、先にオンだったトランジスタがオフになります。
- **パルス生成:** このスイッチング動作が繰り返されることで、トランジスタのコレクタで互い違いのパルス波形が得られます。パルス幅は、抵抗とコンデンサの値によって決まりますが、部品の誤差や温度の影響を受けます。

#### 部品の性能のばらつきについて
- **性能のばらつき:** トランジスタ、抵抗、コンデンサの性能は製造上の理由から完全に同じではありません。これが回路の動作に影響を与え、パルスの幅が設計した値からずれることがあります。
- **温度の影響:** 温度が変化すると、特にトランジスタの性能が影響を受け、パルスの幅が変化することがあります。
- **対策:** これらのずれを最小限に抑えるために、性能のばらつきが少ない高精度の部品を使用したり、回路を設計する際にずれの影響を考慮したりすることが重要です。必要に応じて、温度の影響を補正する回路を追加することもあります。
