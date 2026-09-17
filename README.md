# 超教科書｜バズアーカイブ

リアルタイムバズポストで集めた公開ポストを残す場所。

- 1件の検索は目標 **1000件**（いいね100以上・表示1万以上）
- PNGスクショは置かない（容量のため、JSONのみ）
- 語・ジャンルごとに `collections/YYYY-MM-DD/` へ追記

## 2026-09-17

ジャンル横断のバズ **1000件**（いいね最小 104 / 表示最小 10,118）

- 全文: [collections/2026-09-17/ima-1000.json](collections/2026-09-17/ima-1000.json)
- 索引: [collections/2026-09-17/index.json](collections/2026-09-17/index.json)
- カタログ: `catalog-1.json` … `catalog-5.json`（各200件・本文短縮）

```
collections/
  YYYY-MM-DD/
    {keyword}-{HHmmss}.json
    ima-1000.json
    catalog-*.json
    index.json
```

各JSON:

```json
{
  "query": "猫",
  "genres": ["cat"],
  "period": "day",
  "collectedAt": "2026-09-16T00:00:00.000Z",
  "target": 1000,
  "minLikes": 100,
  "minViews": 10000,
  "count": 32,
  "posts": [{ "id": "", "url": "", "handle": "", "text": "", "likes": 0, "rts": 0, "replies": 0, "views": 0, "time": "", "query": "" }]
}
```

サイト側で自動保存するときは、このリポジトリの Contents 書き込みトークンを使う。
