# Gang Pool Manager v4 Shared

Supabaseを使用した全メンバー共有版です。

## 接続先

- Project URL: https://hufgikfjmieckujjpogh.supabase.co
- ブラウザ用 Publishable key を使用

## 主な仕様

- メンバー一覧を全員で共有
- 犯罪種類を全員で共有
- 犯罪履歴を全員で共有
- プール残高と入出金履歴を全員で共有
- 総合／直近7日間ランキングを全員で共有
- 15秒ごとに自動同期
- ページ再読み込みでもSupabaseから最新状態を取得

## GitHubにアップロードするファイル

`index.html` をリポジトリの一番上（ルート）へアップロードしてください。

## 注意

ログインと権限分けがないため、サイトを利用できる人は全員が追加・削除・入出金できます。
`service_role` や Secret key は使用していません。
