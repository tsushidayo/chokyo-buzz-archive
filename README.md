# 超教科書｜バズアーカイブ

リアルタイムバズポストで集めた公開ポストを残す場所。

- 1件の検索は目標 **1000件**（取れた分を積み上げる）
- PNGスクショは置かない（容量のため、JSONのみ）
- 語・ジャンルごとに `collections/YYYY-MM-DD/` へ追記

```
collections/
  YYYY-MM-DD/
    {keyword}-{HHmmss}.json
```

各JSON:

```json
{
  "query": "猫",
  "genres": ["cat"],
  "period": "day",
  "collectedAt": "2026-09-16T00:00:00.000Z",
  "target": 1000,
  "count": 32,
  "posts": [{ "id": "", "url": "", "handle": "", "text": "", "likes": 0, "rts": 0, "replies": 0, "time": "", "query": "" }]
}
```

サイト側で自動保存するときは、このリポジトリの Contents 書き込みトークンを使う。
