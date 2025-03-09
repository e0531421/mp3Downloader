MP3Downloader の使い方
MP3Downloader は、YouTube の動画を MP3 に変換してダウンロードできるツールです。

最初に！
https://qiita.com/e0531421/private/63e4b73d5f2d5737f663
FFmpegがはいっていない方はこちらの記事を最初にお読みになってからお進みください（入れていない場合エラーが出て使えません）

📥 インストールと準備
1.ダウンロード
・mp3Downloader.exe を PC にダウンロードします。
2.ffmpeg の準備
・ffmpeg がインストールされていない場合、以下の手順でインストールしてください。
1.FFmpeg公式サイト から Windows 版をダウンロード
2.ffmpeg.exe を mp3Downloader.exe と同じフォルダに配置する
3.または、環境変数に ffmpeg のパスを追加

📌 使い方
1.アプリを開く
・mp3Downloader.exe をダブルクリックして起動します。
黒いコンソール画面（または入力ウィンドウ）が表示されます。
2.YouTube の URL を入力
・画面に表示されたメッセージに従って、MP3 に変換したい YouTube の動画 URL を入力し、Enter を押します。
3.MP3 のダウンロード
・自動的に動画の音声がダウンロードされ、MP3 に変換されます。
・MP3 ファイルは downloads フォルダに保存されます。
続けてダウンロードするか選択
4.続けてダウンロードするか選択
・ダウンロード完了後、「続けてダウンロードしますか？ (y/n)」と表示されます。
・y を入力 → 新しい YouTube の URL を入力し、再びダウンロード
・n を入力 → プログラムを終了
🛠 トラブルシューティング
問題	解決策
ffmpeg が見つからない	ffmpeg.exe をダウンロードし、実行ファイルと同じフォルダに配置
RuntimeError: input(): lost sys.stdin	--noconsole を外して .exe を再作成するか、GUI 版を使用
ダウンロードした MP3 がない	downloads フォルダを確認
.exe を実行してもすぐ閉じる	コンソール版を使う (--noconsole をつけずに .exe を作成)

📂 保存先
ダウンロードした MP3 ファイルは、mp3Downloader.exe と同じディレクトリにある downloads フォルダに保存されます。

📜 注意事項
・本ソフトは 個人利用の範囲でのみ 使用してください。
・著作権のあるコンテンツのダウンロードは 自己責任で行ってください。

✅ まとめ
1.mp3Downloader.exe を開く
2.YouTube の URL を入力
3.MP3 が downloads フォルダに保存される
4.y/n で続けるか終了を選択
これで YouTube の音声を簡単に MP3 に変換できます！ 🎵







