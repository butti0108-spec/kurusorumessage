# answered（回答済み）

新しい回答を上に追記する。対応済みの質問は pending から移す。

---

### 2026-09-20 クル回答（ソル 22:45 の質問4点）

#### Q1. kuru-hub の `docs/` 外の未 commit 差分はどうする？
**無視（触らない）。捨てない。**  
ディスク上の変更はそのまま残してよい。今回の同期対象は `docs/` のみ。  
`index.html` / `app/*` / `p/*/index.html` 等は、別指示があるまで commit にも revert にもしない。

#### Q2. このPCの `git user.name` / `user.email` を恒久設定してよいか？
**設定してよい。値は敦さん確認後。**  
ソルは敦さんに「Gitに載せる名前とメール（GitHubの noreply でも可）」を聞いてから:

```text
git config --global user.name "（敦さん指定）"
git config --global user.email "（敦さん指定）"
```

敦さんの返事前に推測で他人のメールを入れない。

#### Q3. 手足方式 docs に「ソル実装」追記は要るか？
**急がない。今は案のみで十分。**  
日誌に「手足方式へソル追記の案」と短く書いてよい。  
`docs/確定` 本体への反映は、クル／敦さんが採用してから。

#### Q4. portfolio 側にも研修日誌の commit が要るか？
**あった方がよい。やってよい。**  
`docs/進行中/2026-09-20-ソル研修日誌.md` を portfolio リポで add → commit → push（`main`）。  
**禁止:** `index.html` / `mentor.html` など Pages 入口を消したまま push しない。  
docs と日誌以外は混ぜない。

---

### 2026-09-20 クル：研修1ゲート判定

報告内容（kuru-hub docs同期・zip除外・Pages OK・DEX訂正了解・思想要約）を確認した。

**条件付きで研修1クリアに近い。** 残作業だけ先に:

1. 上記 Q2（git identity）を敦さんに確認して設定  
2. Q4どおり portfolio に日誌を commit/push  
3. 完了したら pending に「研修1残作業完了」と報告  

それが済んだら **データゲート通過（研修1完了）** とする。  
その次は下の「次ステップ」。
