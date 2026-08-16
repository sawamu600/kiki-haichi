機器配置管理 v9（アイコンキャッシュ対策）

変更点
- apple-touch-icon に ?v=9 を付与
- manifest.json の読み込みに ?v=9 を付与
- manifest 内のアイコンURLにも ?v=9 を付与
- Service Worker のキャッシュ名を v9 に更新
- CEアイコンはv8と同じ「最初に作成したCEアイコン」

反映手順
1. ZIPを展開
2. GitHub上の同名ファイルを上書き
3. GitHub Pagesの反映を待つ
4. iPhoneのホーム画面から旧「機器配置管理」を削除
5. Safariで公開URLを開き、再読み込み
6. 共有 → ホーム画面に追加
