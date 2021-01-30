# Hogen
 方言翻訳機のうち公開可能な部分

## 使用上の注意
参考リポジトリの方言パッチとしてのご利用を推奨します。
参考元から以下の3ファイルをダウンロードし、リポジトリのROOTフォルダに置いてください。
+ model.py
+ preprocess_utils.py
+ weight_utils.py

## フォルダ構成

+ _OLD : 要らないファイルですが、使い道があればと思い残したものたちです
+ checkpoints_EX : Tensorチェックポイント保管用フォルダです。参考元のmodelに傷を付けないよう切り離しを行いました。
+ hogen_sentences : 方言アライメントのサンプルを置いています。
+ jpn_sentences : 日本語アライメントを置いています。ライセンスが別で存在します（CC-BY 2.0 (France)）。利用時には注意が必要です。
+ DATA : 使うアライメントはこちらに移動させてください。

## ファイル説明
+ kana_SUDACHI.ipynb
CSVを読み込み、特定の列のカタカナをひらがなに変換します。
+ Train_on_GPU_HIRA.ipynb
翻訳学習ファイル。
+ Predict_on_GPU_HIRA_UNK.ipynb
翻訳予測ファイル。

## 参考リポジトリ
[kawasaki-kento/Transformer](https://github.com/kawasaki-kento/Transformer)

### 翻訳結果の一例
![翻訳結果だよ](./_OLD/output11.png "翻訳結果だよ")
