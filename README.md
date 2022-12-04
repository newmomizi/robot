# 使い方の説明

## 編集したいとき
projectフォルダーをダウンロードする。

フォルダーの中身から、scratchフォルダーの中身3つを選択し、zip圧縮する。

圧縮したファイルの名前を、scratch.sb3に変える。また、scratch.sb3ファイルはprojectフォルダー内に置いておく。

元のscratchフォルダーは消しておくこと。

ここまで正しく出来ていれば、projectフォルダーの中身は、以下のファイルになっているはず
- icon.svg
- manifest.json
- monitor.json (無いこともある。条件不明)
- scratch.sb3

これで出来たprojectフォルダーの中身を全て選択、zip圧縮する

圧縮済みファイルの名前を、XXX.zipから、project.llspに変える。これでエディターで開けるようになる


## アップロードするとき
保存したプロジェクトファイルを、project.zipに改名する。

このファイルを解凍すると、中には次のファイルがあるはず。
- icon.svg
- manifest.json
- monitor.json (無いことも以下略)
- scratch.sb3

scratch.sb3を、scratch.zipに改名し、解凍する。zipファイルの方は消してOK

これで、projectフォルダーの中身は、この通りとなっているはず。
- icon.svg
- manifest.json
- monitor.json (無いこともry)
- scratch (フォルダー)

このprojectフォルダーをアップロードすれば完了だ。

## なんか面倒くさくね?
そのうちこれを自動化してくれるソフトを作るので、それまで待っててくれ...
