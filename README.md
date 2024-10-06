##  *初級理解度チェック課題 問題1*

### *実装内容*

#### 四則演算を行う計算プログラムです。ユーザーからの入力内容を受け、結果を出力します。<br>
```
入力例:
  1番目の数字を入力してください。 : 
15
  演算子を入力してください。(+, -, *, /) : 
+
  2番目の数字を入力してください。 : 
40
 
出力例:
  計算結果: 15 + 40 = 55
```

#### 小数点以下で割り切れた場合はその位まで、割り切れなかった場合は小数点第６位を四捨五入して出力します。<br>

```
入力例:
  1番目の数字を入力してください。 : 
33000
  演算子を入力してください。(+, -, *, /) :
 /
  2番目の数字を入力してください。 : 
15400
 
出力例:
  計算結果: 33000 / 15000 = 2.2
```

```
入力例:
  1番目の数字を入力してください。 : 
400
  演算子を入力してください。(+, -, *, /) : 
/
  2番目の数字を入力してください。 : 
33
 
出力例:
  計算結果: 400 / 33 = 12.121212
```

#### 空白や数字以外が入力された場合、「数字以外のものが入力されています。改めて数字を入力してください。」とエラーメッセージを返し、数字が入力されるまで待機します。

```
入力例:
  1番目の数字を入力してください。 : 
（空白）
エラー：数字以外のものが入力されています。改めて数字を入力してください。 
a
エラー：数字以外のものが入力されています。改めて数字を入力してください。 
```

#### 無効な演算子が入力された場合、「無効な演算子です。改めて【 + , - , * , / 】の4つの中から選んで入力してください。」とメッセージを返し、正しい演算子が入力されるまで待機します。
 
```
入力例:
  1番目の数字を入力してください。 : 
154
  演算子を入力してください。(+, -, *, /) : 
÷
無効な演算子です。改めて【 + , - , * , / 】の4つの中から選んで入力してください。
```

#### 0で除算しようとした場合、「エラー：0で割ることはできません。0以外の数字を入力してください。」とエラーメッセージを返し、最初の入力に戻ります。

```
入力例:
  1番目の数字を入力してください。 : 
97
  演算子を入力してください。(+, -, *, /) :
/
  2番目の数字を入力してください。 :
0
エラー：0で割ることはできません。0以外の数字を入力してください。
  1番目の数字を入力してください。 : 
```

### *（問題）*

Javaの基本構文を使用して、簡単な計算機プログラムを作成してください。<br>
加減乗除の四則演算ができ、ユーザーから入力を受け取り、結果を表示するものとします。<br>

```
入力例:
    1番目の数字を入力してください: 10
    演算子を入力してください (+, -, *, /): +
    2番目の数字を入力してください: 5

期待される出力例:
    計算結果: 10 + 5 = 15
```

#### （特記事項）

実施するコード、成果物は下記を満たすようにしてください。<br>

```
・コードフォーマット（環境設定で行ったものです）
・命名規則に従った名前付け（安直な名前付けや間違った名前をつけないこと）
・コード全文と動作結果の共有
・値の入力を受け付けるには「Scannerクラス」を使うこと
・例外処理は可能な範囲で実装（空文字や想定していない値の入力時など）
```

### *動作確認*

・加算<br>

<img width="400" alt="初級理解度チェック課題1／加算" src="https://github.com/user-attachments/assets/d148b587-fda2-42be-bd1a-439b6907203c"> 

・減算<br>

<img width="400" alt="初級理解度チェック課題1／減算" src="https://github.com/user-attachments/assets/731eff7e-2365-4a97-8c2b-73921faf42fe">

・乗算<br>

<img width="400" alt="初級理解度チェック課題1／乗算" src="https://github.com/user-attachments/assets/353884d2-c0b2-42e0-b867-0161b119d45a">

・除算<br>

<img width="400" alt="初級理解度チェック課題1／除算" src="https://github.com/user-attachments/assets/27fa8d6c-f57a-4351-a525-569ba76569ac">

・例外処理（空白・数字以外・無効な演算子・ゼロ除算）※小数点以下第6位表示<br>

<img width="600" alt="初級理解度チェック課題1／例外処理" src="https://github.com/user-attachments/assets/f99599a0-7d91-40ea-95d5-8cbe52b82462">




