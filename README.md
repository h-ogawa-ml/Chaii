# Chaii
kaggle「chaii - Hindi and Tamil Question Answering」コンペにて使用したモデルなどを格納しています。

## modelフォルダに格納された、各modelの説明
1. model1　：<br>
publicLB0.789の元model。10fold交差検証、及びサンプルごとに重みを変えた、CrossEntropyを使用。<br>
0.789を出したモデルはfold1,2,3,4,10のアンサンブルです。<br>
<br>
2. model2　： <br>
lovasz-hinge損失でマルチタスク訓練&xlm-roberta-encoderの最終３層をconcatさせて出力を行なったモデル。<br>
<br>
3. model3　：<br>
xlm-roberta-encoderの最終２層の重みを初期化&マルチサンプルドロップアウトを行なったモデル。<br>

