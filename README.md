# Gang Pool Manager v4.2 Shared Fixed

## 修正内容

Supabaseの新しいPublishable keyをAuthorization Bearerへ入れていたため、
追加・犯罪保存・プール入金が拒否される問題を修正しました。

この版ではPublishable keyを `apikey` ヘッダーだけに設定します。

## 更新手順

1. GitHubのリポジトリを開く
2. Add file → Upload files
3. このindex.htmlをアップロードして既存ファイルを上書き
4. Commit changes
5. 公開サイトでCtrl + F5
6. 画面タイトルが「Gang Pool Manager v4.2 Shared」になっていることを確認

## 動作確認

- メンバー追加時に「追加中…」と表示
- 成功すると追加完了のメッセージ
- 犯罪種類追加時に「追加中…」と表示
- 犯罪記録保存時に「保存中…」と表示
