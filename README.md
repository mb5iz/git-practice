# git-practice

GitHub Desktop を使って、以下の流れを練習するためのリポジトリです。

- クローン
- ブランチ作成
- ファイル編集
- コミット
- プッシュ
- Pull Request 作成

---

## 練習の流れ

### STEP 1：クローン

このリポジトリを GitHub Desktop でクローンしてください。

---

### STEP 2：ブランチを作成

1. 上部中央の「Current Branch」をクリック
2. 「New Branch」をクリック
3. ブランチ名に自分の出席番号を入力する（例：`feature/01`）
4. 「Create Branch」をクリック

---

### STEP 3：出席番号フォルダを作成・ファイルを追加

1. クローンしたフォルダを VS Code などで開く
2. `students/` フォルダ内に、自分の出席番号のフォルダを作成する
3. その中に `index.txt` を追加する

フォルダ構成例：

```text
students/
└── 01/
    └── index.txt
```

`index.txt` には「名前」と「一言コメント」を記入してください。

記入例：

```txt
名前：山田 太郎
コメント：GitHubの練習をしています。
```

---

### STEP 4：コミット

1. GitHub Desktop の左側に変更ファイルが表示される
2. 左下の「Summary」欄にコミットメッセージを入力する（例：`Add student 01 folder`）
3. 「Commit to feature/01」をクリック

---

### STEP 5：プッシュ

「Publish branch」または「Push origin」をクリックして、GitHub にブランチをアップロードしてください。

---

### STEP 6：Pull Request を作成

1. GitHub Desktop 上部の「Create Pull Request」をクリック
2. ブラウザが開くので、タイトルを入力する（例：`01 の提出`）
3. 「Create pull request」をクリック

---

## 注意

- `main` ブランチでは作業しない
- 必ず自分のブランチを作成して作業する
- `students/` の中には自分の出席番号のフォルダだけを作成する
- 他の人のフォルダやファイルは編集しない
