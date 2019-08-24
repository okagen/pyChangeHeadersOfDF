# pyChangeHeadersOfDF
Change the headers of DataFrame according to the header list(csv). <br>
ヘッダーリスト(csv)に従って、DataFrameのヘッダを書き換える。

## 0 : Data
### Header List.(csv)
The image of headerlist.csv is as below. The columns are required to contain 2 kinds of the header names, one is before changed and the other is after changed. / headerlist.csvのイメージ。変更前と変更後のヘッダの名前が書いてある列が必要。  
Image of HeaderList<br>
<img src="https://github.com/okagen/pyChangeHeadersOfDF/blob/master/Data/headerlist.png?raw=true" width="200">

### Target file.(csv)
Target file whose header names would be changed. / ヘッダー名が変更させるターゲットファイル。  
Image of H19<br>
<img src="https://github.com/okagen/pyChangeHeadersOfDF/blob/master/Data/H19.png" width="400">

## 1 : Proceture
### 1-1 : Extract only necessary columns from the header list and convert them to a dictionary.
Header Listから変更前と後のヘッダ名が書いてある列を抽出し、dictoionaryに変換。  
<img src="https://github.com/okagen/pyChangeHeadersOfDF/blob/master/Data/headerName_before_after_dictionary.png" width="400">

### 1-2 : Read target file as a DataFrame.
ターゲットファイルを読み込み、DataFrameに保存。

### 1-3 : Change the header name of the DataFrame using the dictionary.
dictionaryを使って、DataFrameのヘッダ名を変更。
<img src="https://github.com/okagen/pyChangeHeadersOfDF/blob/master/Data/dataframe_before_after.png" width="400">

### An addition : Add the original header names on the first line of the DataFrame.
追加：1行目に、オリジナルのヘッダ名を追加する。



