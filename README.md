# TIL (Today I Learned)

学んだことをまとめるリポジトリ。

## ディレクトリ構成

````
til/
├── books/                  # 書籍から学んだこと
│   ├── _example/           # テンプレート (新しい本を追加する時はここをコピー)
│   └── {book-name}/
│       ├── index.md        # 本のメタ情報 + 読了日 + 全体メモ
│       └── chXX-xxx.md     # 章別メモ
└── README.md
````

## 運用ルール

### 本のステータス

`{book-name}/index.md` の冒頭にある「読了:」が空欄か日付かでステータス判定する。

- 空欄 → 読書中
- 日付あり → 読了

ラベル管理や一覧表は持たない。メモなので運用は最小限にする。

### 章別メモの命名

`chXX-xxx.md` (例: `ch01-introduction.md`)。`xxx` は章タイトルから適当に。

### 新しい本を追加する時

1. `books/_example/` をコピーして `books/{book-name}/` にリネーム
2. `index.md` のプレースホルダーを埋める
3. 章ごとに `chXX-xxx.md` を作って書いていく
