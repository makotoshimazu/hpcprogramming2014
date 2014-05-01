B4M1勉強会2014 - High Performance Computing
====

概要
----
Fx10やMICを最大限利用した行列演算を作成し、競う。

内容
----
このテストプログラムをリンクし、測定を行う。
その際に、Fx10とMICでオプションが異なるので注意すること。(計算リソースが大幅に異なるため)
といいつつまだ実装してないので、実装したら詳細を書きます。

最も簡単な使い方
----
1. srcの中にある、mymulmat.cppを変更する
2. このREADME.mdがあるディレクトリに移動して、`make`コマンドを実行
3. 生成されるmain.binを実行する

また、main.binといった副生成物を削除したい場合は、
```
make clean
```
を実行してください。

自分のリポジトリとの結合
----
別にリポジトリを自分で作ってしまって、mymulmat.(cpp|h)をシンボリックリンクに置き換えてしまうのが手軽でよいと思います。

テスト
----
プログラムをテストするための方法を用意する予定です。
実装をお待ちください。

測定
----
プログラムを走らせて測定する方法を用意します。
実装をお待ちください。

結果の参照
----
測定結果をうまく表示するためのシステムを用意しようと考えています。
実装をお待ちください。

作者
----
Makoto Shimazu <shimazu@eidos.ic.i.u-tokyo.ac.jp>