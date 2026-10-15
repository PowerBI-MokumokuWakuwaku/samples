# 更新履歴

このリポジトリーと [組織ページ](https://github.com/PowerBI-MokumokuWakuwaku) の主な変更です。新しいものが上です。

## 2026-10-15 リポジトリー開設・構成の整理

### やったこと

- **組織とリポジトリーを作成**
  - GitHub 組織 [PowerBI-MokumokuWakuwaku](https://github.com/PowerBI-MokumokuWakuwaku) を作成
  - サンプル置き場として `samples` リポジトリーを作成（README、MIT License、`.gitignore`、`.gitattributes`、フォルダの雛形）
- **組織トップページに案内を表示**
  - 組織ページは `.github` リポジトリーの `profile/README.md` が表示される仕組み。最初は `.github` 直下に README を置いていたため、組織ページに何も出ていなかった
  - `profile/README.md` を作成し、会の紹介と samples への入口、ダウンロード方法を載せた
- **共通サンプルデータを追加**
  - 架空の小売チェーン「わくわくマート」のデータ（[`data/wakuwaku_mart_sample.xlsx`](../data/wakuwaku_mart_sample.xlsx)）を追加。今後の勉強会で共通に使う
  - シート・列・表のつながりを [`data/README.md`](../data/README.md) にまとめた
- **構成を整理**
  - `samples/samples/` という入れ子で迷いやすかったため廃止し、Excel は `data/` に移動
  - 中身のなかったテーマ別フォルダは置かず、`data/`（共通データ）と `sessions/`（開催回）の 2 本立てにした
  - トップの README を参加者向けに書き直し（はじめての方へ／探しているものは？／データの概要／ダウンロード方法）
  - 各フォルダの README に「トップに戻る」リンクを付けた
  - この更新履歴を追加

### 構成（この時点）

```
samples/
├── README.md                  入口
├── data/
│   ├── README.md              データの説明
│   └── wakuwaku_mart_sample.xlsx
├── sessions/
│   ├── README.md              開催回の一覧
│   └── _template/             新しい回のひな形
└── docs/
    ├── history.md             この更新履歴
    └── publishing-checklist.md 公開前チェックリスト
```

### 残っていること

- 組織ページ（`.github/profile/README.md`）の「テーマ別のサンプル」の行を、共通サンプルデータへのリンクに差し替える
- samples リポジトリーの About（説明文）を設定する

[← トップに戻る](../README.md)
