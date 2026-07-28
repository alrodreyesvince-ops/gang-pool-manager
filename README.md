# Gang Pool Manager v4.1 Shared Fixed

## 修正内容

v4 Sharedで、Supabaseの外部JavaScriptライブラリが読み込めない場合に、
「＋追加」などのボタン処理がすべて止まる問題を修正しました。

この版では外部Supabaseライブラリを使用せず、
ブラウザ標準のfetch機能でSupabase REST APIへ直接接続します。

## GitHubでの更新方法

1. GitHubのgang-pool-managerリポジトリを開く
2. 既存のindex.htmlを開く
3. 右上の鉛筆アイコン、またはAdd file → Upload files
4. このフォルダのindex.htmlで上書き
5. Commit changes
6. GitHub PagesをCtrl + F5で完全更新

## 確認項目

- 画面上部に「共有データ同期済み」と表示される
- メンバーを追加できる
- 犯罪種類を追加できる
- 別端末にも追加内容が表示される
