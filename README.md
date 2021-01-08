# JS道場　コードレビュー

## はじめに
レビューして欲しいコードをフォルダにまとめ、このリポジトリにpushしてください。
GitHub上でコードレビューを実施します。

## 手順

1. このリポジトリをクローンしてください。
```
$ git clone
```

2. `xhack-js-review`というフォルダが生成されるので、そこに移動してください。
```
$ cd xhack-js-review
```

3. 新しくブランチを切ってください
```
$ git checkout -b ((受講年月)_slack名)

# 例
git checkout -b 202101_itagaki_hiroshi
```

4. 2で作られたフォルダ内に自分のslack名のフォルダを作成してください
```
$ mkdir ((受講年月)_slack名)

# 例
mkdir 202001_itagaki_hiroshi
```

5. 4で作ったフォルダに、コードのファイルを移動してください。

6. ステージング→コミットしてください。
```
$ git add .
$ git commit -m '（受講年月）_slack名'

# 例
git add .
git commit -m '202001_itagaki_hiroshi'
```

7. GitHubにpushしてください。

```
$ git push origin head
```

