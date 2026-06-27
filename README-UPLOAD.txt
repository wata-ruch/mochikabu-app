GitHub Pagesへアップロードするファイル一式です。

1. このフォルダ内のファイルとiconsフォルダを、作成したGitHubリポジトリへアップロードします。
2. GitHubのリポジトリで Settings > Pages を開きます。
3. Sourceを Deploy from a branch にします。
4. Branchを main、フォルダを / (root) にして Save を押します。
5. 公開されたURLをiPhoneのSafariで開きます。
6. 共有 > ホーム画面に追加 > Webアプリとして開く を有効にして追加します。

注意:
- mochikabu-*.jsonなど、保有データを書き出したJSONはGitHubへアップロードしないでください。
- 現在のfile://版とは保存領域が別です。最初にJSONを書き出し、GitHub版で一度読み込んでください。
- アプリを更新したらservice-worker.jsのCACHE_NAME末尾（現在はv4）をv5、v6と増やしてください。
