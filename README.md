# ♠ CARTAE ♥
### トランプ牌の論理パズル — Card Logic Puzzle

♠スペードと♥ハートを6×6グリッドに正しく配置する、1ファイル完結の論理パズルゲームです。

![License](https://img.shields.io/badge/license-MIT-black) ![Puzzles](https://img.shields.io/badge/puzzles-∞-crimson)　![No dependencies](https://img.shields.io/badge/dependencies-none-green)

---

## 🎮 プレイ

**[► ここでプレイ](https://ksuy-bottom.github.io/cartae/)**

または `index.html` をブラウザで直接開くだけでプレイできます。インストール不要・サーバー不要。

---

## 📖 ルール

| ルール | 内容 |
|--------|------|
| ♠ / ♥ | 各行・各列にスペード3個、ハート3個を配置する |
| ✕ | 同じ記号を**3つ連続**して並べてはいけない |
| ＝ | バッジのある隣接セルは**同じ記号**でなければならない |
| × | バッジのある隣接セルは**異なる記号**でなければならない |

---

## 🕹️ 操作

- **左クリック** — ♠ を配置（もう一度で♥、もう一度でクリア）
- **右クリック** — ♥ を直接配置（もう一度でクリア）

---

## ✨ 機能

- **問題数無限**（ブラウザで自動生成）
- **タイマー** — 最初の入力から自動計測
- **統計** — 難易度別のクリア数・ベストタイム・平均時間・達成率
- **リアルタイムエラー表示** — 間違いをすぐハイライト
- **ヒント機能** — 1マスずつ答えを表示
- **クリア演出** — ♠♥が降り注ぐコンフェッティ

---

## 📁 ファイル構成

```
cartae/
├── index.html   # ゲーム本体（これ1ファイルのみ）
├── README.md
└── LICENSE
```

---

## 🛠️ 技術

- 純粋な HTML / CSS / JavaScript（フレームワーク・ライブラリなし）
- パズルはPythonのバックトラッキングソルバーで自動生成・一意解を検証済み
- フォント：[Playfair Display](https://fonts.google.com/specimen/Playfair+Display) / [Courier Prime](https://fonts.google.com/specimen/Courier+Prime)（Google Fonts / OFL）

---

## 📜 ライセンス

MIT License © 2026 ksuy-bottom
