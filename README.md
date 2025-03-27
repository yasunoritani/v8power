# v8power

v8power は、自然言語処理を活用した Max for Live プラグインで、IDM/グリッチスタイルの実験的電子音楽制作を支援するツールです。

## 概要

v8power は、音楽制作に関する自然言語コマンドを解釈し、複雑なサウンドデザインプロセスを簡素化することを目的としています。実験的エレクトロニカの制作技法に精通したハイレベルなユーザー向けに設計されています。

## 主な機能

- **自然言語インターフェース**: テキスト入力による直感的な操作
- **グリッチエフェクト生成**: CD操作型グリッチ手法を実装
- **アルゴリズミックリズム**: 複雑なポリリズムや非対称拍子の生成
- **テクスチャー処理**: スペクトル処理やグラニュラー合成
- **Ableton Live統合**: Live APIを活用した深い連携
- **高度な視覚化**: リアルタイムフィードバックを提供

## 技術スタック

- Max for Live (v8ui)
- Python (NumPy/Pandas)
- SQLite
- Model Context Protocol (MCP)

## ディレクトリ構造

```
v8power/
├── src/                 # ソースコード
│   ├── ui/              # v8ui関連のコード
│   ├── dsp/             # 信号処理関連のコード
│   ├── nlp/             # 自然言語処理関連のコード
│   └── db/              # データ管理関連のコード
├── docs/                # ドキュメント
├── tests/               # テストコード
├── resources/           # リソースファイル
└── examples/            # 使用例
```

## セットアップ

開発環境のセットアップ方法は順次ドキュメント化していきます。

## ライセンス

ライセンス情報は今後追加予定です。