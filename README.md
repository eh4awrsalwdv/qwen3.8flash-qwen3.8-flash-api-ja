# Qwen3.8 Flash API 日本語ガイド（qwen3.8-flash / qwen3.8flash）

> 従量課金、最低 1 ドルから、OpenAI 互換エンドポイント。 **input $0.0914; cached_input $0.0114; explicit_cached_input $0.0114**

**[模型页](https://go.apimart.ai/k-ce1390) · [实时价格](https://go.apimart.ai/k-b88c52) · [获取 API Key](https://go.apimart.ai/k-24829a)**

## 料金（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `input` | $0.0914 |
| `cached_input` | $0.0114 |
| `explicit_cached_input` | $0.0114 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"qwen3.8-flash","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本リポジトリはサードパーティ中継サービス APIMart の利用ガイドです。
