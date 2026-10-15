# Power BI もくもく・わくわく会 サンプル置き場

Power BI もくもく・わくわく会で使うサンプルデータと、開催回ごとの資料を置いています。
GitHub のアカウントがなくても、見るのもダウンロードも自由です。

## 🚀 はじめての方へ

1. **[サンプルデータ（わくわくマート）をダウンロード](https://github.com/PowerBI-MokumokuWakuwaku/samples/raw/main/data/wakuwaku_mart_sample.xlsx)**
2. Power BI Desktop で **ホーム → Excel ブック** から読み込む
3. どんなデータかは [データの説明](data/README.md) を見てください

勉強会では、基本的にこのデータを共通で使います。

## 📂 探しているものは？

| 探しているもの | 場所 |
|---|---|
| 共通のサンプルデータ（わくわくマート） | [`data/`](data/) |
| 参加した回の資料・サンプル | [`sessions/`](sessions/) |
| このリポジトリーの更新履歴 | [`docs/history.md`](docs/history.md) |

## 🛒 わくわくマートとは

食品・日用品・文具・家電を扱う、架空の小売チェーンです。2024年1月〜2026年12月の3年分の売上を、6つの表にしています。

| 表 | 中身 | 行数 |
|---|---|---:|
| 売上明細 | 注文の明細（いつ・誰が・何を・いくつ） | 65,704 |
| 商品 | 商品マスター | 92 |
| 顧客 | 顧客マスター | 1,415 |
| 地域 | 都道府県と地方の対応 | 47 |
| 予算 | 月 × 地方 × カテゴリの予算 | 1,152 |
| 返品 | 返品のあった注文 | 1,373 |

列の意味や表どうしのつなぎ方は [`data/README.md`](data/README.md) にあります。

## ⬇️ ダウンロードのしかた

- **1ファイルだけ**：ファイルを開いて、右上の **Download raw file**（⬇ アイコン）
- **まとめて全部**：[ZIP でダウンロード](https://github.com/PowerBI-MokumokuWakuwaku/samples/archive/refs/heads/main.zip)
- **PBIP 形式のサンプル**：フォルダごとダウンロードして、`.pbip` ファイルを Power BI Desktop で開く

## ℹ️ このリポジトリーについて

- データはすべて**架空のデータ**です。社名・人名・数値は実在のものと関係ありません
- [MIT License](LICENSE) です。社内勉強会などで自由に使い、改変・再配布できます（著作権表示は残してください）
- サンプルは学習用です。内容の正確さは保証しません
- 運営：石川陽一（[@ishiayaya](https://github.com/ishiayaya)）

運営メンバー向け：新しい回の追加は [`sessions/`](sessions/)、push 前の確認は [公開前チェックリスト](docs/publishing-checklist.md) を見てください。
