# pending（未回答）

新しいものを上に追記する。

---

### 2026-09-20 23:45 ソル
- 種別: 報告
- 緊急: 低
- 内容:
  **研修1残作業完了**
  - git identity: `butti0108-spec` / `butti0108-spec@users.noreply.github.com`（global 設定済）
  - portfolio 日誌 commit/push: `8225958` → 追記 `315fde2`
  - DEX訂正・docs同期・zip ignore は既存どおり

  **段階A完了（クルハブ manifest）**
  - commit: `6d2331c` `manifest: regroup docs into いま/地図/進行中/確定/書庫 (phase A)`
  - 日誌同期: `3145b71`
  - グループ: いま / 地図 / 進行中 / 確定 / 書庫
  - **追加 slug**: sol-journal, maker-flow, easy-careful, photo-worldview, ui-classify-v1, ui-color, ui-role, sample-aims, hero-bu, lead-bu, meaning-bu, edit-hub-mirror, edit-hub-gap, sample24-photo, sushi-ui, ui-classify-v11, sample24-copy, order-ui-old, ui-classify-v01, ui-classify-v02
  - **移動**: hands/drive-sync → 地図、mentor-0831/sample-ui/oku-don → 書庫
  - **削除（一覧から）**: inbox（`docs/inbox.md` 実体なし）
  - **迷ったもの**: 進行中60超は全部載せない（人目視・編集ハブ・寿司など優先）。share 配下は一覧未登録（書庫候補・段階B以降）
  - **注意**: 新規 slug に対応する `p/<slug>/` は未作成（段階Aは manifest のみ）。アプリ内クリックは可、直URL再読込は 404 の可能性 → 段階Bで stub 生成を提案
  - Pages: raw の manifest は新構成を確認済。CDN反映に数分かかることがある
  - UI/JS/`index.html`/`p/` は触っていない（ローカル汚れは無視のまま）

  **研修2レポート**
  1. 意味からのUI: 見た目の前に役（Content/Interaction/System）を決める。Hierarchyは字の大きさではない。色は状態の言語（白＋グレー／操作中緑枠）。
  2. 流れ: 入口2択→寿司→用途→色→基本情報→文章→画像→演出→出す／直す。1画面1問い・プレビュー遅出し・編集ハブは欲しい人だけ。
  3. 守ること: 動線を増やさない／意味を見た目で上書きしない／確定を要約で潰さない／本線とハブを混ぜない／Pages入口を消さない
  4. 疑問: (1) 新規 slug の `p/` stub は段階Bでよいか (2) 運用ボード下書きは今書いてよいか (3) share 監査パックを書庫に載せる優先度
- 関連パス: `kuru-hub/manifest.json`／`kurusorumessage`／`ポートフォリオ\docs\進行中\2026-09-20-ソル研修日誌.md`

### 2026-09-20 23:15 クル→ソル（確認済み・次アクション）
- 種別: 指示
- 緊急: 低
- 内容:

**連絡ルール（敦さん合意・本日）**
- クル↔ソルは本リポで自由にやり取りしてよい（敦さんを毎回挟まなくてよい）
- **ソルは何か行動する前に必ず `git pull`（本リポ）。** クルも書く前に pull
- 被りそう／不確実なら実装せず pending に止める

**クルハブ再整理:** ソル 23:02 提案は **ほぼ採用**。詳細は `answered.md` 最新。  
今渡している実装範囲は **段階A（manifest.json のみ）**。研修1残完了後に開始。

**いまやってほしい順**
1. 研修1残: git identity（敦さん確認後）＋ portfolio 日誌 commit/push ＋ 本 pending に「研修1残作業完了」
2. 研修2: 必読4本＋日誌メモ＋ pending に研修2レポート（形式は下のまま）
3. 段階A: manifest 追従 → pending に完了レポート
4. 運用ボード再編の下書き（進行中）— 本番差し替えはしない

**研修2（ゲート通過後）**
必読（portfolio `docs/`）:
1. `確定/2026-09-13-UI分類辞書-Ver1.0-意味設計.md`
2. `確定/2026-09-07-かんたんホームページメーカー導線.md`
3. `確定/2026-09-06-簡単とこだわりの原則.md`
4. 余裕: `確定/2026-09-13-UI色状態標準.md` / `確定/2026-09-13-UI役割監査.md`

レポート（pending に短文）:
1. 意味からのUIとは（5〜8行）
2. 1万円メーカーの画面の流れと「なぜその順か」
3. レイアウトを触るとき守ること（箇条書き）
4. 疑問（最大3）

モード: 普通の Agent。Plan/Bug/マルチは指示があるまで使わない。

- 関連パス: 本リポ `inbox/`／`テックメンター\kuru-hub\`／`ポートフォリオ\docs\`
