# FL_Studio_i18n
FL Studioの多言語サポートに言語を追加するプロジェクトです。

## FL Studioの言語ファイルの置き場所（Windows版）
デフォルト設定でインストールした場合、以下に配置。
```
C:\Program Files (x86)\Image-Line\FL Studio 20\System\Languages\
```
日本語のファイルを置く場合は以下の場所に配置。
```
C:\Program Files (x86)\Image-Line\FL Studio 20\System\Languages\ja\LC_MESSAGES
Default.mo
```

## 翻訳で気を付けてほしい留意点
* 直訳だと逆に使いづらくなるので意訳を意識してほしい
* 翻訳してもアプリで表示するとはみ出す場合があるので、アプリでの表示の確認の上、言い換えや半角カナ文字にするなど調整をしてほしい

## 編集方法
poeditをインストールする
https://poedit.net/
poファイルを開き編集する
ファイルタブからmoファイルにコンパイルできる。

## メモ
* 用語を統一したい 例(オーディオと音声、アップデートと更新みたいな(まともな例が思いつかなかった))
* あと言葉使いも統一したい 例(XXを編集 と XXの編集 みたいな)

## ということで一応の規則
* %s とかには何かしらの文字が代入されるので自然に翻訳する
* &Aや&Bみたいなのは翻訳した後に最後に(&A) (&B)を追加する
* &All notes → 全てのノート(&A)
* XXを編集 XXを追加　ではなく　XXの編集 XXの追加　といった感じに【の】を使う

## 単語の翻訳
* All = 全ての
* analyze = 分析
* advanced = 高度な
* audio = オーディオ
* point = ポイント
* detect = 検出
* browser = ブラウザ
* Edison = エディソン