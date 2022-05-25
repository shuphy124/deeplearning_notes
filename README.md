# deeplearning
notebooks for intensive lecture

# 目录
以下链接是各个笔记的链接。从section可以前往各README相关页面，从subsection可以到达Google Colaboratory的页面。
SubsectionはGoogle Colaboratoryにリンクで飛んだ後に**1-1を除き、実際にコードを実行することも可能です**。実行にはGoogleアカウントが必要なようです。リンク先のものを直接実行しても基本的には問題ありませんが、何らかのファイルを保存するような動作をするものが幾つかあるので、それがGoogle Colaboratoryでどのように動作するかは未確認です。**一旦自分のGoogleドライブにコピーしてから実行するのが良い**ような気もします。

> 【注意】：プログラムのソースコードは実は「著作物」です。このリポジトリで多くのプログラムを使用しますが、その著作権に関わる取り決めはMITライセンス https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/LICENSE にある通りとします。MITライセンスについては https://ja.wikipedia.org/wiki/MIT_License などご参照下さい。尚、4-2, 4-3, 5-1, 6-3, 7-3, 8-1, 8-2, 8-3, 9-1 には、私以外の方の作成したソースコードを改変したものが含まれている(それぞれのライセンスについては引用箇所や末尾に記載しました)ので、個人使用を超えた使用の際にはご注意下さい。

- [1. 機械学習の目的と確率論の復習](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section1/README.md)
    - [1-1. 大雑把な分類](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section1/1-1.ipynb)
    - [1-2. 多項式フィッティング](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section1/1-2.ipynb)
    - [1-3. 確率論のおさらい](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section1/1-3.ipynb)
- [2. Kullback-Leiblerダイバージェンスと汎化](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section2/README.md)
    - [2-1. 変な形のサイコロ](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section2/2-1.ipynb)
    - [2-2. KL情報量](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section2/2-2.ipynb)
    - [2-3. ガウス分布における最尤推定](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section2/2-3.ipynb)
    - [2-4. 赤池情報量基準と汎化](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section2/2-4.ipynb)
- [3. ニューラルネットワークの基礎1](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section3/README.md)
    - [3-1. この節の目標](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section3/3-1.ipynb)
    - [3-2. ニューラルネットと誤差関数](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section3/3-2.ipynb)
    - [3-3. 勾配学習](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section3/3-3.ipynb)
    - [3-4. ニューラルネットの勾配学習](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section3/3-4.ipynb)
- [4. ニューラルネットワークの基礎2](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section4/README.md)
    - [4-1. 画像処理と畳込み演算](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section4/4-1.ipynb)
    - [4-2. 離散値データと分散表現](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section4/4-2.ipynb)
    - [4-3. 時系列データと再帰的な構造](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section4/4-3.ipynb)
- [5.ニューラルネットワークの基礎3](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section5/README.md)
    - [5-1. バッチ正規化](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section5/5-1.ipynb)
    - [5-2. スキップ接続](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section5/5-2.ipynb)
    - [5-3. アテンション機構](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section5/5-3.ipynb)
- [6. 教師あり深層学習](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section6/README.md)
    - [6-1. まだ解説していないテクニック](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section6/6-1.ipynb)
    - [6-2. Adversarial examples](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section6/6-2.ipynb)
    - [6-3. 転移学習](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section6/6-3.ipynb)
- [7. アルゴリズム学習](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section7/README.md)
    - [7-1. LSTMでアルゴリズム学習してみる](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section7/7-1.ipynb)
    - [7-2. tensorflowでRNNをカスタマイズする方法](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section7/7-2.ipynb)
    - [7-3. Neural Turing Machines](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section7/7-3.ipynb)
- [8. 教師なし深層学習](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section8/README.md)
    - [8-1. 変分自己符号化器](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section8/8-1.ipynb)
    - [8-2. 敵対的生成ネットワーク](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section8/8-2.ipynb)
    - [8-3. Flow-basedモデル](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section8/8-3.ipynb)
- [9. 強化学習](https://github.com/AkinoriTanaka-phys/deeplearning_notes/blob/master/section9/README.md)
    - [9-1. 多腕バンディット問題](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section9/9-1.ipynb)
    - [9-2. マルコフ決定過程](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section9/9-2.ipynb)
    - [9-3. 行動価値推定に基づくRL](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section9/9-3.ipynb)
    - [9-4. 方策勾配法によるRL](https://colab.research.google.com/github/AkinoriTanaka-phys/deeplearning_notes/blob/master/section9/9-4.ipynb)
