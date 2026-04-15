# &N LP Workspace

Private Salon &N（渋谷・男性専門脱毛サロン）のLP制作用リポジトリ。

## 公開URL

- 作業中LP: https://viviwood327.github.io/test/
- 髭脱毛LP: https://viviwood327.github.io/test/hige/

## 構造

```
/
├── index.html          # ランディング（LP一覧）
├── hige/               # 髭脱毛LP
│   ├── index.html
│   └── assets/         # 画像・CSS等
├── assets/             # 共通アセット
└── README.md
```

## 運用

- `main` ブランチに push → GitHub Pages で即公開
- 画像はリポジトリ内 `assets/` or 各LP配下の `assets/` に置く → 相対パスで参照
- コミット単位で履歴管理。広告配信前後のバージョン比較に使う

## 関連資料

- 会社概要 / マーケ戦略: `../andn_marketing.docx`
- バナー仕様書: `../banner_spec_hige_datsumou.html`
- 現状LP分析: `../current_lp_analysis.md`
- 制作リファレンス: `../../LP_バナー_制作リファレンス.md`
