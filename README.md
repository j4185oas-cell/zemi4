# plusコマンド
![test](https://github.com/j4185oas-cell/zemi4/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数値の合計を計算するコマンドです。

## 使い方

```bash
seq 5 | ./plus
```

実行結果

```
15.0
```

## 必要なソフトウェア
- Python
  - テスト済み：3.10、3.11、3.12、3.13

## テスト環境
- Ubuntu

## テスト結果
GitHub Actionsを利用して自動テストを行い、
4つのPythonバージョンですべて正常に動作することを確認した。
