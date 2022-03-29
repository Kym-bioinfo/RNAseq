## 使い方 ##
1. <a href=https://sites.google.com/s.okayama-u.ac.jp/kym-diary/rna-seq/github%E3%81%8B%E3%82%89clone%E3%81%97%E3%81%A6%E3%81%8F%E3%82%8B>このページ</a>を参照して、MyDrive中にcloneを作成する
2. 0_FirstSetUp.ipynbを実行する
3. Inputsディレクトリ内に、実験名のディレクトリを作り、fastqファイルやカウントファイルを入れる
4. SourceCodesディレクトリ内の必要なコードに必要な箇所を追記し、セルを実行する(一部対話的な箇所があるので臨機応変に)
5. Outputsディレクトリに実行結果が出力される

## How to use ##
Acsess to <a herf=https://colab.research.google.com/>Google Colab</a> and select "New notebook"　<br>
To mount your Google Drive, fill in the code cell as folowing
``
from google.colab import drive
drive.mount('/content/drive')
```(
