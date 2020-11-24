# AR-Image-Tracking

## AR.js
[AR.js](https://ar-js-org.github.io/AR.js-Docs/)とは
数行のコードでARを体験できるjavascriptライブラリです  
three.jsとjsartoolkit5をベースにつくられています

## Processing
Processingというソフトで画像の特徴量を抽出し、マーカーにすることができます  
手順は以下の通りです

1. Processingを起動  
2. ファイル→サンプル→nftFilesGen  
3. 表示されたプログラムを実行する  
4. 生成されたウィンドウのimportから画像を選択  
5. DPIを変更(macならプレビューでcmd+iで確認できる)  
6. MakeFeatureSetで解析
7. 解析が終了したらexport→SaveFeatureSetFilesで保存  

あとはGitHubなどにアップロードすれば完了です


## デモ
デモはこちらです  
https://iehokado.github.io/AR/
