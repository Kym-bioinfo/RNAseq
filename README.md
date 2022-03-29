## 使い方 ##
1. <a href=https://sites.google.com/s.okayama-u.ac.jp/kym-diary/rna-seq/github%E3%81%8B%E3%82%89clone%E3%81%97%E3%81%A6%E3%81%8F%E3%82%8B>このページ</a>を参照して、MyDrive中にcloneを作成する
2. 0_FirstSetUp.ipynbを実行する
3. Inputsディレクトリ内に、実験名のディレクトリを作り、fastqファイルやカウントファイルを入れる
4. SourceCodesディレクトリ内の必要なコードに必要な箇所を追記し、セルを実行する(一部対話的な箇所があるので臨機応変に)
5. Outputsディレクトリに実行結果が出力される

## How to use ##
1. Clone this git on your Google Drive1.





### Hou to clone ti git on your Google Drive###
use https://colab.research.google.com/gist/Kym-bioinfo/04b1b1356811e5020d2ecc05007d3d26/git_clone.ipynb
Acsess to <a href=https://colab.research.google.com/?hl=en> Google Colab</a> and select "New notebook" to make a jupyter notebook file.<br>
To mount your Google Drive, fill in the code cell as folowing.

```Python
from google.colab import drive
drive.mount('/content/drive')
```

Then, to execute the code in the cell, either press the play button to the left of the code, or use the keyboard shortcut "Command/Ctrl+Enter".
You may need some 操作 to complete mounting your Google Drive. <br>

Afer MOunted your google Drive, to clone this git, fill in a new code cell as following and execute.

```Python
%cd  /content/drive/MyDrive/
!git clone https://github.com/Kym-bioinfo/RNAseq.git
```

Now, your Google Drive has a directry "RNAseq".
Go to <a href=https://colab.research.google.com/?hl=en> Google Colab</a>
