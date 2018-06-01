コマンド並列実行マクロ『multiExec_from_ExcelVBA』
===

ExcelVBAからコマンドをマルチプロセスで並列実行するサンプルプログラムです。  
  

## システム要件
*Windows XP/Vista/7/8/10 or Windows Server 2008/2012/2016  
*Microsoft Excel 2007/2010以降  

## ダウンロード

コマンド プロンプト（またはPowerShell）を開き、git でダウンロードします。  
```
>git clone https://github.com/gx3n-inue/multiExec_from_ExcelVBA
```

## 実行方法
1. multiExec_from_ExcelVBA_20YYmmdd.xlsm を開きます。

2. [実行コマンド列]シートを開き、A列に実行したいコマンドを列挙します。

3. [メニュー]シートを開き、最大プロセス数、リトライ回数、プロセス一覧取得間隔に任意の値をセットし、
   終了を待つ、コマンド実行方法から任意の項目を選択します。

4. [BAT並列実行]ボタンをクリックします。

## ライセンス
  
コマンド並列実行マクロ『multiExec_from_ExcelVBA』 ver1.00  
This project is licensed under the terms of the MIT license, see LICENSE.  
