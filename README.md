# emoji_commit_template
コミットする際にEmoji Prefix一覧を表示するためのテンプレートです。

## Setup
任意の場所にcommit_templateを置いてgit configコマンドで設定します。

```bash
$ touch ~/commit_template
$ git config --global commit.template ~/commit_template
```

特定のプロジェクトだけに適用したい場合はプロジェクト内に置いて  
git config --localとかで設定するといいかと思います。
