# OCaml ではじめるプログラミング

OCaml を用いた，未経験者向けのプログラミング入門書

## 形態

技術同人誌ではなく商業誌として，どこかの出版社に企画を持ち込みたい

## 内容 (暫定)

- プログラミングの学び方 (情報収集の技)
  - OCaml 公式サイト
  - Qiita
  - GitHub
- 環境構築
  - OPAM
  - ocamlc / ocamlopt / ocamlmerlin / utop
  - Visual Studio Code + 拡張機能「OCaml and Reason IDE」
- utop ではじめる対話型プログラミング
  - 算術 / 論理式の評価
  - 名前束縛 / 参照
    - `let` 構文
    - 演算子と式の持つ静的型
    - Hello World
    - 意味を持たない値 `unit`
    - `ref`, `:=` 構文
  - 文字列とその操作
  - 関数 (前編)
    - fun 構文
    - 関数適用
    - 関数型
    - 再帰 / 相互再帰 (`let rec` 構文)
    - カリー化と部分適用
    - 高階関数 (map, 畳み込み)
  - 様々なデータ構造と抽象型
    - Tuple
    - List / Array
    - Variant
    - Record
  - 型推論
- コンパイラの活用
  - リファクタリングとデバッグ
    - printf デバッグ
    - ocamldebug の使い方
  - 関数 (後編)
    - ラムダ計算と評価戦略
    - 継続渡しスタイル
  - エラーハンドリング
    - `failwith` / `exception` / `raise` 構文
    - `try with` 構文
  - モジュールシステムと分割コンパイル
    - ストラクチャとシグネチャ
    - ファンクタ
    - インターフェースファイル
    - ocamlc と ocamlopt の違い
    - 出力される各種ファイル (`*.cmi`, `*.cmo`, `*.o`, `*.cmx`, ...) の役割
- Jane Street Base を使ってみよう
  - OPAM で base パッケージをインストールする
  - ocamlfind を用いたリンク
  - GNU Make の使い方
- dune を用いたプロジェクト管理
