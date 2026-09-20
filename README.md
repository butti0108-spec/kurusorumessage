# kurusorumessage

このリポは **クル ↔ ソルの連絡専用** です。

- コード正本・秘密・パスワードは置かない
- 質問・提案・報告・回答の受け渡しに使う
- 制作の正本は `WEB制作資料`（ポートフォリオ案件の合意は `ポートフォリオ\docs`）

## ファイル

| ファイル | 役割 |
|----------|------|
| `inbox/pending.md` | 未回答（**新しいものを上に追記**） |
| `inbox/answered.md` | 回答済み（クルが移す／回答を残す） |

## 役割

| 誰 | やること |
|----|----------|
| **ソル** | 疑問・提案・区切り報告を `pending.md` に書いて push。独断で実装を広げない |
| **敦さん** | 急ぎは「クルに確認お願い」。区切りで「連絡リポ、確認ありそう？」。普段は挟まなくてよい |
| **クル** | pending を見て回答。リポへ書くときは Agent 可。ソルへの指示もここに書いてよい |

## 行動前ルール（重要・2026-09-20）

- **ソルは作業・実装・commit の前に必ず `git pull`（本リポ）**。クルが先に書いていないか確認する
- クルも pending／answered を書く前に pull
- 被りそうなら止めて pending に「衝突／待ち」と書く（git 更新が重なったら一回止める）

## 暴走止め（重要）

**自分で確定できない判断 → 実装せず `pending.md` に書いて止める。**

- 意見・提案は書いてよい
- 採用されるまで実装・`docs/確定` の変更はしない
- 緊急「高」は敦さん経由で一声

## 追記フォーマット（pending）

```text
### YYYY-MM-DD HH:mm ソル
- 種別: 質問 / 提案 / 報告
- 緊急: 高（敦さんに一声） / 低（区切りで可）
- 内容:
- 関連パス: （あれば）
```

## 訂正

「DEX」は docs の音声誤認。DEX という別正本枠は無い。

## 関連URL

- 連絡リポ: https://github.com/butti0108-spec/kurusorumessage
- kuru-hub: https://github.com/butti0108-spec/kuru-hub ／ Pages: https://butti0108-spec.github.io/kuru-hub/
- portfolio Pages: https://butti0108-spec.github.io/portfolio/
