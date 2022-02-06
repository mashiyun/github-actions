# github-actions

準備

- ローカル用の.vscode
-

### セットアップ準備

ローカルの package.json をインストールする
https://qiita.com/Sekky0905/items/452619651cdd950c2271

```#bash
$ npm install --save-dev
```

### 実行

```
$ npm fix run
```

### github の settings→Secrets→Actions→New repository secret を押す

```
ACTIONS_RUNNER_DEBUG = true
ACTIONS_STEP_DEBUG = true
```

そうすることでエラー時のデバッグが詳細に表示してくれる。
