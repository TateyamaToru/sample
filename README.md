# GitHub Desktopとは
## 概念
公式サイトにはこのように記されています。

> Gitと戦うことよりも大事なことに集中しよう。あなたがGitの新入りでも熟練者でも、GitHub Desktopはあなたの開発フローをシンプルにします。

つまり、Gitで苦しまない為にGitでの作業を可視化したツールということです。

## GitHUb Desktop何ができるの？
簡単にいうと、コマンドを叩かず、GUI（マウスポチポチ作業）にてあらゆるGitコマンドを実行できます。

# GitHUb Desktopの使い方
## 1. git clone
1. 左上の「Current Repository」をクリックします。
2. 既にGitHUb Desktopに登録されているリポジトリリストが表示されます。
3. 「Add ▼」をクリックすると、リポジトリを追加する3つの方法が表示されます。
4. クローンしたい場合は、「Clone Repository...」をクリックします。
5. GitHUb上の目的のリポジトリを選択します。
6. ローカル上のどのディレクトリに置くか選択します。
7. 「clone」ボタンをクリックすると完了

## 2. git status / add
1. クローンしたローカルのリポジトリ内のファイルを編集します。
2. すると、Git Desktop上のChangesにて、変更内容が追加(add)されています

## 3. git commit
1. 左下のテキストフィールドにコミットメッセージを記入し、Commit to [ブランチ名]をクリックします。
   
## 4. git push
1. 変更元がmasterだった場合、右上の「Push origin」をクリックするとプッシュできます。
2. 変更元が開発用Branchだった場合、右側にある[Create Pull Request]をクリックすると、Githubページに遷移しPullリクみぎくりっくエストを作成できます。


## 5. git checkout
1. 画面上の「Current Branch」をクリックします。
2. そのリポジトリにあるすべてのブランチ（リモートブランチも含む）が表示されます。
3. 目的のブランチをクリックするだけで、切り替える完了です。
4. 新しくブランチを作成したい場合は、「New Branch」をクリックすることですぐに作成することができます。

## 6. git log
1. 「History」を開くと、これまでのコミットの履歴を確認できます。
2. 特定のコミットを復元する際は、右クリックをして「Revert this Commit」を選ぶことで復元できます。