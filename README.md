# Windows7-Japanese-Path
# 説明
このソフトウェアはWindows7を日本語化するプログラムです
だだしWindows7が故障するのを防ぐためにレジストリは自分自身で変更してください
まず管理者権限で起動してください
成功すると
The operation completed successfully.
と案内文が表示されます
成功しましたらレジストリエディターにて
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Nls\LanguageにあるInstallLanguageの値を英語を表す0409から日本語を表す0411に変更します。
そして再起動を行ってください
# 起動画面日本語化
管理者権限でコマンドプロンプトを起動し
bcdedit /set {default} locale ja-JP
を実行してください
これにて日本語化は終了です
リカバリーモードは日本語化で来ませんがそこは各自でなんとかしてください
# ダウンロード
https://www.dropbox.com/s/gn5dz09bav59j3x/Windows7%20japanesehack.zip?dl=0
