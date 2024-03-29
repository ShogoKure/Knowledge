# GitHubについて

## Gitとは

Gitは、コード管理やバージョン管理システムの1つで、複数の人々が同じプロジェクトで作業する際に役立ち、Gitを使うと、各個人が独自の`ブランチ`を作成して、変更を加え、それを本体の`ブランチ`に`マージ`することができる。  

Gitを使うと、プロジェクトのバージョン履歴を管理できる。すなわち、過去にどのような変更が行われたか、誰が行ったか、何が変更されたかを追跡することが可能でまた、Gitを使うことで、異なるバージョンを比較することができ、不具合が発生した場合に以前のバージョンに戻すことができる。  

Gitは、`分散型バージョン管理システム`の1つであり、ネットワーク上で複数の人が同時に作業することができる。そのため、オープンソースプロジェクトやチーム開発の場で多く使用される。また、GitHubやBitbucket、AWSなどのプラットフォームを利用して、リポジトリを共有することも可能。  

## リポジトリとは

`リポジトリ（repository）`とは、Gitの中でコードやプロジェクトのバージョン履歴や変更履歴を保存する場所。

`リポジトリ`には、ファイルやディレクトリ、コードの変更履歴などが格納される。  
`リポジトリ`には、`ローカルリポジトリ`と`リモートリポジトリ`の2つの種類がある。  

`ローカルリポジトリ`は、コンピュータ内に保存されている`リポジトリ`で、そのコンピュータ上で管理され  
一方、`リモートリポジトリ`は、リモートサーバ上に保存されている`リポジトリ`で、複数の人がアクセスできるように公開されている場合がある。`リモートリポジトリ`は、チーム開発で複数の人がコードを共有するために利用される。

`リポジトリ`には、`ブランチ`という概念があり、`ブランチ`とは、`リポジトリ`のコピーで、コードやファイルを変更してテストするために使用される。`ブランチ`を作成することで、メインのコードを変更することなく、新しい機能や修正を実装することも可能。

`リポジトリ`は、`Git`によって管理されており、`Git`の`コマンド`を使用して変更を記録したり、履歴を表示するなどを行うことができる。

## GitHubでGitを始めるには

1. GitHubのアカウントを作成する  
    まず、GitHubのアカウントを作成する必要で、アカウント作成には、ユーザー名、メールアドレス、パスワードを入力する必要がある。アカウントは無料で作成できる。

2. 新しいリポジトリを作成  
    GitHubにログインしたら、新しいリポジトリを作成する。作成方法は以下の通りです。
    - 右上の＋アイコンをクリックして、"New repository"を選択します。
    - リポジトリの名前、説明、公開/非公開などの設定を入力し、"Create repository"をクリックします。

3. ローカル環境でGitを初期化  
    新しいリポジトリを作成したら、ローカル環境でGitを初期化する必要があり、以下のコマンドを実行して、新しいGitリポジトリを作成する。
