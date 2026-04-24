# QQ #032/#033 — Edward & Alphonse

> アプリの種を育て、要件定義へ変換する兄弟アプリ。

## 構成

| # | ファイル | 役割 |
|---|----------|------|
| #032 | [edward.html](./edward.html) | 要件ヒアリング → `qq_seed` を localStorage に保存 |
| #033 | [alphonse.html](./alphonse.html) | `qq_seed` を受け取り → 要件定義 & README 生成 |

## localStorage 連携仕様

キー名: `qq_seed`

```json
{
  "title": "アプリ名",
  "problem": "解決したいモヤモヤ",
  "target": "誰のため",
  "features": ["機能1", "機能2"],
  "timestamp": "ISO8601"
}
```

## 使い方

1. Edward でアプリの情報を入力し「種を保存する」
2. Alphonse へ移動 → 自動的に種を読み込んで要件定義・README を生成

---

*QQ Project｜#032–#033*
