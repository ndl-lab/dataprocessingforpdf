# dataprocessingforpdf
PDFからテキストデータを抽出して機械学習等に適用するためのツール群
文字情報付きPDFからテキストデータを抽出して、機械学習等に転用するためのツール群です。 一番上のセルから、ctrlキーとEnterキーを同時押しして実行してください。

## dataProcessingForIndesign.ipynb
Adobe indesignで作成したPDFから、テキストデータを抽出します。 以下のように必要なパッケージのインストールが必要です。 

```apt-get install poppler-utils```

```pip3 install fileupload pdfminer.six pdf2image```


## dataProcessingForIndesign_colab.ipynb
環境構築の手間を省くため、上記の機能について、Google Colaboratory用のスクリプトも公開しています。


[Google Colaboratory用リンク](https://colab.research.google.com/github/ndl-lab-staff/dataprocessingforpdf/blob/master/dataProcessingForIndesign_colab.ipynb)