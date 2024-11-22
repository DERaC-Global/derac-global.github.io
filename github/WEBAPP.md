# ウェブページでの操作

![Dashboard](https://github.com/DERaC-Global/tag_japan/blob/main/docs/img/github_dashboard_new_file.png)

ログイン後、ダッシュボードからリポジトリに移動し、右上にある *Add file* からファイル作成操作を選択します。

- Create new file &rarr; このフォルダにファイルを新規作成
- Upload files &rarr; このフォルダにファイルをアップロード

## ファイルの作成

![Create](https://github.com/DERaC-Global/tag_japan/blob/main/docs/img/github_create_new_file.png)

ファイルを作成する場合 *Create new file* から作成画面へ行き、ファイル名とファイルの内容を入力して保存します。もし下階層にファイルを作成したい場合は、ファイル名を入力する際に下階層のフォルダ名を含めてファイル名を指定します。

例えば、上の画像の例では `tag_japan/docs/github` から新規作成画面に行った状態ですが、この直下に `EXAMPLE.md` を作成する場合はそのままそのファイル名を入力して保存します。もし `tag_japan/docs/github/example` というフォルダを作成してその中に `README.md` として保存したい場合は、ファイル名に `example/README.md` と入力して保存することで意図した場所にファイルを保存することができます。

## ファイルのアップロード

ファイルをアップロードする場合は *Upload files* からアップロードしますが、**アップロード先はそのフォルダ**になります。もし下階層を作成してからそこにファイルをアップロードしたい場合は、以下のような手順に従います。

1. 下階層のフォルダに `README.md` 等のファイルをファイルの新規作成の要領で作成します
2. 作成されたフォルダに移動して *Upload files* からファイルをアップロードします

## ファイルの消去

該当するファイルまたはフォルダをクリックして移動した後、右上の「・・・」ボタンからファイルの場合は *Delete file* を、 フォルダの場合は *Delete directory* を押して指示に従って消去を実行します。

>[!NOTE]
>Github におけるすべての **CRUD 操作**は *Commitment*（コミットメント）という操作で行われます。このため、コミットメントを行うと毎回コメントの記入を求められます。頻度が多いので、あまり深く考えず、一言コメントを入力してください。