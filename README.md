# atcoder

## コマンドでbuild〜実行まで
```bash
g++ test.cpp && ./a.out
```

## 不要な実行ファイル削除
```bash
# 無視ファイル（x）を含めて削除確認
git clean -dxn
```

## コマンド類
```bash
source atcoder_env/bin/activate # 仮想環境(atcoder_env)を有効化
npx acc login # atcoderにログイン
npx acc session # ログイン状態確認
npx acc logout # ログアウト
deactivate # 仮想環境(atcoder_env)の終了
```

## ショートカット類

* F5: デバッグ実行
* Ctrl + Option + N: Run Codeからgccを実行(デバッグしない)
