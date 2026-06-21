# ゲーミフィケーション実践大全

基礎理論から実践設計、応用分野、効果測定・倫理、最新研究までを網羅した、ゲーミフィケーションの体系的テキストです。MkDocs Material でビルドし、GitHub Pages で公開します。

📖 **公開サイト: <https://asari-mtr.github.io/gamification/>**

## ローカルでのプレビュー

```bash
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt

# プレビュー（http://127.0.0.1:8000）
mkdocs serve

# 静的ビルド（site/ に出力）
mkdocs build --strict
```

## 公開

`main` ブランチへの push で GitHub Actions（`.github/workflows/deploy.yml`）が自動的にビルドし、GitHub Pages へデプロイします。

## 構成

```
docs/
├── index.md          # トップページ
├── part1/            # 第Ⅰ部 基礎編
├── part2/            # 第Ⅱ部 設計編
├── part3/            # 第Ⅲ部 応用編
├── part4/            # 第Ⅳ部 計測と倫理
├── part5/            # 第Ⅴ部 最新研究と未来
└── appendix/         # 付録
```

## ライセンス

本文は [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja) で公開しています。
