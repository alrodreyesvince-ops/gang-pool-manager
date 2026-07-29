# Gang Pool Manager v5 Shared

Supabase共有専用としてゼロから作り直した版です。

## GitHubへ反映
1. ZIPを展開
2. index.htmlをGitHubリポジトリのルートへ上書き
3. Commit changes
4. 公開ページで Ctrl + F5
5. タイトルが Gang Pool Manager v5 Shared になっていることを確認

## Supabase
先に完全初期化SQLを実行し、以下のテーブルがある状態で使ってください。
- members
- crime_types
- crime_records
- pool_transactions

## 主な機能
- メンバー登録・削除
- 犯罪種類登録・削除
- 犯罪利益計算
- 犯罪履歴保存
- プール自動入金
- 手動入出金
- 総合／直近7日ランキング
- 30秒ごとの自動同期
- エラーの画面表示
