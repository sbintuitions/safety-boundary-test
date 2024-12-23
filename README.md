# Satefy Boundary Test
日本語安全性境界テスト (Japanese Safety Boundary Test) とは、言語モデルの安全性に関する振る舞いについて評価するデータセットである。
データセットには、以下の2種類の入力が含まれる
- 安全な入力: 言語モデルが回答をすべき入力。適切に訓練されていない言語モデルは誤って回答を拒否する可能性がある。
- 安全でない入力: 言語モデルが回答をすべきでない、または否定すべき入力。

## Structure
本リポジトリには2種類のデータが含まれる。

### Data
NLP2025で公開する入力120件と、実験で使用したプロンプト。
詳細はNLP2025予稿を参照のこと。

### Results
NLP2025の予稿で行なった実験の評価結果。
v1.0.0, v1.0.1 はそれぞれプロンプト修正前と修正後を示している。
