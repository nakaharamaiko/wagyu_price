# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
.リモートリポジトリ：Web上の保管場所。すべてのローカルリポジトリの複製元となる。
.ローカルリポジトリ：自分のパソコンの中にある自分専用の保管場所

## プッシュとマージの違いは何でしょうか？
.ローカルの内容をリモートにアップするのがプッシュ
.別のブランチの作業内容をブランチに取り込むのがマージ

## コミットとプッシュの違い
.コミットはローカルリポジトリのブランチに保存すること
.プッシュはリモートにアップすること



## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
.誰が見ても目的が分かりやすいように書く


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
.ローカルでマージするフロー
1.Workingブランチをプッシュ
2.workingからmasterにcheckout
3.workingからmasterにマージ
4.リモートのmasterブランチにプッシュ
.メリット：短時間でできる
.デメリット：間違えたら危険
.プルリクエストでマージするフロー
1.workingブランチをプッシュ
2.プルリクエスト作成
3.レビューしてもらってマージ
4.ローカルのmasterブランチにpull(リモートリポジトリのmasterで行った変更をpullで反映)
.メリット：バグの発生を抑えることができる
.デメリット：時間がかかる


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
1.先にマージされた変更内容を取り込む
2.後にマージしようとしている変更内容を取り込む
3.どちらの変更内容も取り込む
.この３点のどれかで取り込みを行い、作業内容をコミットする。
