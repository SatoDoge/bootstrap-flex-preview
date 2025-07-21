# Bootstrap Flex Utility プレビュー

このプロジェクトは、Bootstrapの**Flexユーティリティクラス**（`d-flex`, `justify-content-*`, `align-items-*` など）を  
**ビジュアルに体験できるプレビューUI**です。  
各種ボタンやプルダウンでクラスを切り替えると、中央のBox表示が即座に変化し、  
**現在適用中のクラス**もリアルタイムで確認できます。

---

## 主なFlexクラスの意味・解説

| クラス                           | 役割・意味                                                                                 |
|----------------------------------|-------------------------------------------------------------------------------------------|
| `d-flex`                         | 要素をFlexboxレイアウトにする。                                                            |
| `d-inline-flex`                  | 要素をinline-flexにする。                                                                  |
| `flex-row`                       | 子要素を「横並び」にする（デフォルト：row方向）。                                          |
| `flex-column`                    | 子要素を「縦並び」にする（column方向）。                                                   |
| `flex-wrap`                      | 子要素が領域を超えたとき、折り返して表示（wrap）。                                         |
| `flex-nowrap`                    | 子要素が折り返さず一列で表示（nowrap）。                                                   |
| `flex-fill`                      | 子要素が均等に広がる（fill）。                                                             |
| `justify-content-start`          | 水平方向（X軸）で左寄せ。                                                                  |
| `justify-content-center`         | 水平方向（X軸）で中央寄せ。                                                                |
| `justify-content-end`            | 水平方向（X軸）で右寄せ。                                                                  |
| `justify-content-between`        | 両端に寄せて、間隔を均等にする。                                                           |
| `justify-content-around`         | 子要素の左右に均等な間隔を空ける。                                                         |
| `justify-content-evenly`         | 子要素間の間隔を完全に均等にする。                                                         |
| `align-items-start`              | 垂直方向（Y軸）で上寄せ。                                                                  |
| `align-items-center`             | 垂直方向（Y軸）で中央寄せ。                                                                |
| `align-items-end`                | 垂直方向（Y軸）で下寄せ。                                                                  |
| `align-items-baseline`           | 子要素のテキストのベースラインで揃える。                                                   |
| `align-items-stretch`            | 子要素の高さを均等に広げる（デフォルト）。                                                 |

---

## 使い方

1. [index.html](./index.html)をブラウザで開きます。
2. 左側の操作パネルで表示方向（水平方向/縦方向）、揃え方、wrapオプションなどをボタンやプルダウンで選択します。
3. 右側のプレビュー領域で、Boxがどのように配置されるかが即座に反映されます。
4. 下部に現在適用されているBootstrapクラスの一覧が表示されます。

---

## 参考

- [Bootstrap公式 Flexユーティリティ](https://getbootstrap.com/docs/5.3/utilities/flex/)
- [Bootstrap公式 レイアウト関連](https://getbootstrap.com/docs/5.3/layout/grid/)
- 本プロジェクトは追加CSSを最小限にし、**Bootstrap標準機能のみ**で構成しています。

---

## ライセンス

MIT License