# portfolio-lp

自主制作ポートフォリオ用 LP 集。クライアント案件の無断掲載を避けるため、**架空商品**で制作。

## 収録

- `noctela/` — NOCTÉLA（架空の美容・健康食品）高単価 LP。静的 HTML・依存ゼロ。

## 表示

静的 HTML だが scroll-reveal が IntersectionObserver 依存 + Google Fonts 読込のため、
`file://` ではなくローカルサーバ推奨:

```bash
cd noctela && python3 -m http.server 8801   # http://localhost:8801
```
