# JS道場　コードレビュー

## はじめに
レビューして欲しいコードをフォルダにまとめ、このリポジトリにpushしてください。
GitHub上でコードレビューを実施します。

## 手順

1. このリポジトリをクローンしてください。
```
$ git clone git@github.com:gakisan8273/xhack-js-review.git
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
$ git add -A
$ git commit -m '（受講年月）_slack名'

# 例
git add -A
git commit -m '202001_itagaki_hiroshi'
```

7. GitHubにpushしてください。

```
$ git push origin head
```

8. このリポジトリのページに移動してください。

9. `Compare and Pull Request`を押してください。
![スクリーンショット 2021-01-20 23 14 28](https://user-images.githubusercontent.com/52925914/105187456-292cc300-5b76-11eb-813f-87d3943f406b.png)

10. タイトルに 「受講年月_slack名」 を入力してください。
本文には特にみてもらいたい箇所など、自由に記入してください。

![スクリーンショット 2021-01-20 23 17 56](https://user-images.githubusercontent.com/52925914/105187425-1f0ac480-5b76-11eb-9f01-fdd4130e62c0.png)

11. `Create Pull Request' を押してください。

12. GitHub上でレビューができる状態になったので、Slackで`Pull Request`をした旨を報告してください。

13. レビューをします。

14. レビューが完了した旨をSlackに報告しますので、提示されたリンク先を参照ください。
