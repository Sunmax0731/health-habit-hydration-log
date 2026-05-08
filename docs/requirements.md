# 要件定義

## 背景

NON PICKUP Rank 39 の `体調・習慣・水分ログ` は、水分、体調、習慣チェックを夜に振り返るAndroidログとして閉域アルファ化します。

## ユーザー価値

- 水分量と体調メモから次の習慣アクションを出す
- 入力、確認、履歴保存、次アクションを同じ作業単位で扱う。
- MVP後の磨き込みで UI/UX、責務分割、手動テスト、配布準備を同時に確認できる。

## MVP

- 代表データ4種を処理できる。
- 必須項目不足を error、補助項目不足を warning として分ける。
- リリース前 docs、QCDS、security/privacy、traceability、release evidence をそろえる。

## 非目標

- 実ユーザーデータのクラウド同期。
- 有料販売ページ、Google Play Console、BOOTH 商品ページの実公開。
- Codex 側での手動テスト代行。
