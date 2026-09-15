# サイバー攻撃の疑似体験サイト



## Github Pages

https://sooshima.github.io/fish-demo/



## Pages公開手順

### **1. GitHubでリポジトリを作る**

まずGitHubにログインします。

GitHub

右上の **「＋」→「New repository」**。

例えば、

- Repository name
  - interview-timer

とします。

**重要**

今回のような単純なWebアプリなら、**Public repository**にするのが一番簡単です。

例として、ここに

- index.html
- dodon.mp3
- dodondodon.mp3

を公開します。

HTMLだけでなく、ここに置かれたファイルは**誰でも取得可能**です。

今回の効果音程度なら問題ないと思いますが、著作権や社内機密に関係するファイルは置かないでください。

### **2. ファイルをアップロード**

リポジトリを作ったら、

**Add file → Upload files**

を選びます。

そして、例として

- index.html
- dodon.mp3
- dodondodon.mp3

をまとめてアップロード。

そのまま **Commit changes**。

GitHub Pagesは静的ファイルを公開できるので、今回のHTMLならサーバー側のプログラムは不要です。

### **3. GitHub Pagesを有効にする**

リポジトリの

**Settings → Pages**

へ進みます。

「Build and deployment」のところで、

- Source
  - Deploy from a branch
- Branch
  - main
    - / (root)

を選択して **Save**。

GitHub Pagesは指定したブランチの静的ファイルを公開できます。

少し待つと、

- Your site is live at
  - https://ユーザー名.github.io/interview-timer/

のようなURLが表示されます。(F5等で何度か画面更新して確認してください)



### 4. サンプル

- 作成したサイト
  - https://sooshima.github.io/dodon-timer/
- 上記サイトのリポジトリ
  - https://github.com/sooshima/dodon-timer