# python構築メモ（windows）

__インストール内容(ハイパーリンクからインストール)__
- [Anaconda(Python実行環境)](https://www.anaconda.com/products/individual)
- OpenCV(画像・動画処理のライブラリー)
- [MeCab(日本語形態素解析のライブラリー)](https://github.com/ikegami-yukino/mecab/releases)
- gensim(自然言語処理のライブラリー)
- TensorFlow/Keras(ディープラーニングのライブラリー)
- Dlib(機械学習・画像処理のライブラリー)

## 1.opencv・tensorflow/kerasのインストール
Anaconda powershell Promptで操作
```dos
> pip install opencv-python==4.1.2.30
> pip install --upgrade tensorflow-cpu==2.2.0
> pip install --upgrade keras==2.4.3
```
## 2.mecab・gensim・dlibのインストール
windowsにExeをインストール後
「環境変数にインストールしたフォルダ/bin/」でパス追加
下記、コマンドでPythonと連携
Anaconda powershell Promptで操作
```dos
> pip install mecab
> pip install -U gensim
> pip install dlib
```
