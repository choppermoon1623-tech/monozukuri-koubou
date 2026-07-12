# ものづくり工房

中学生向けの、レーザー加工機・3Dプリンタ用データジェネレーターです。入口ページ（`index.html`）から4つのツールに分岐します。

🔗 **公開ページ:** https://choppermoon1623-tech.github.io/monozukuri-koubou/

## 4つのツール

| ツール | 対象機器 | 内容 |
|---|---|---|
| 🔧 **ガジェット工房** (`gadget-koubou.html`) | 3Dプリンタ | テンプレートから手早くつくりはじめる |
| ✂️ **レーザー工房** (`laser-koubou.html`) | レーザー加工機 | テンプレートから手早くつくりはじめる |
| 🧊 **ガジェットCAD** (`gadget-cad.html`) | 3Dプリンタ | 自由に設計する |
| 📐 **レーザーCAD** (`laser-cad.html`) | レーザー加工機 | 自由に設計する |

## 使い方

1. 公開ページ（入口）を開く
2. つくりたいもの／使う機器に合わせてカードを選ぶ
3. 生成したデータを加工機・3Dプリンタに読み込ませる

## 構成

- `index.html` — 入口ページ
- `gadget-koubou.html` / `laser-koubou.html` / `gadget-cad.html` / `laser-cad.html` — 各ツール
- いずれもブラウザ完結（サーバー不要）
