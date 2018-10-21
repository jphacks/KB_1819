# レシピまる
![レシピ丸](https://youtu.be/i0bZLRvz1Pw)

## 製品概要
### Food Tech

### 背景（製品開発のきっかけ、課題等）
妻・彼女の言う「晩御飯何食べたい？」には冷蔵庫事情を踏まえて答えろ！というのを聞き、冷蔵庫事情を踏まえたレシピを教えてくれるサービスの必要性を感じたため。
（参考サイト:https://grapee.jp/426501）

なので、LINE CLOVAのスキルを使って今家にある食材から作れる料理をご提案することにしました。LINE CLOVAにした理由は、新しく食材を買った時に買ったものをスマホに入力するのは面倒臭いが食材を冷蔵庫に入れながら口で話すことで入力すれば楽だろうと思ったからです。


### 製品説明（具体的な製品の説明）
LINEClovaのアプリケーションを作成。冷蔵庫の中身を教えるとその中で作ることが出来るメニューを教えてくれる。

### 特長

#### 1. 『人参2本買って来たよ』などと言うと、いま家にある人参の本数に買って来た本数を足して、家にある食材を覚えさせることができる。減らすこともできる。



![資料1](https://github.com/jphacks/KB_1819/blob/master/material-before.jpg)
![資料2](https://github.com/jphacks/KB_1819/blob/master/material-before.jpg)
#### 2.「今家にある食材から作れる料理 」と言うと、家にある食材から作れる料理を数種類クックパッドから厳選！

![資料3](https://github.com/jphacks/KB_1819/blob/master/recipe-before.jpg)
![資料4](https://github.com/jphacks/KB_1819/blob/master/recipe-after.jpg)


#### 3.「今ある食材は？」と話しかけることで登録されてある食材の個数と量がわかる





### 解決出来ること
晩御飯を考える手間。

### 今後の展望
家にある食材をLINEで送る機能。
料理名だけではなく作り方もこのスキル内で話させたい。
賞味期限も管理。





## 開発内容・開発技術
### 活用した技術
#### API・データ
今回スポンサーから提供されたAPI、製品などの外部技術があれば記述をして下さい。

* LINE DEVELOPPMENT
* 
* 

#### フレームワーク・ライブラリ・モジュール
* clova-cek-sdk
* 

#### デバイス
* LINE CLOVA
* 

### 研究内容・事前開発プロダクト（任意）
特にないです


### 独自開発技術（Hack Dayで開発したもの）
#### 2日間に開発した独自の機能・技術
食品600種類以上をLINE CLOVAに登録させたことです。
これにより日常で使うような食材のほぼ全てをきちんと認識させることができた。
