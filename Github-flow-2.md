## Github-flow-2

### 現在のブランチを確認する  
<mark>git branch</mark>

### ブランチを作成する  
<mark>git branch [ブランチ名]</mark>

### マージ済みブランチを削除する  
<mark>git branch -d [ブランチ名]</mark>

### マージされていないブランチを削除する  
<mark>git branch -D [ブランチ名]</mark>

### ブランチを切り替える  
<mark>git checkout [ブランチ名]</mark>

### ブランチを使用した開発の進め方  
1. 作業者側が新しいブランチを作成する feature/タイトルを記述  
ブランチを作成するとそのブランチに自動的に移動する。
2. 作業者側が作業をしてコミットする。
3. 作業者側がプッシュする。
4. 作業者側がGithubでプルリクエストする。
5. レビューする側がGithubでマージする。
6. レビューする側がGithubでブランチを削除する。
7. 作業者側が作業したブランチからmainに移動してブランチを削除する。  
ソース管理->リポジトリ->チェックアウト先からmainを選択する。ブランチを削除する。
8. 作業者側がリモートリポジトリをプルする。

### Github プルリクエストとレビューのやり方
https://qiita.com/obscure723/items/5265556d1b89e77c456b

### レビュー側が変更の内容をブラウザで確認する方法
GitHub　codespace
https://github.co.jp/features/codespaces