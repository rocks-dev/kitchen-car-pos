PWA-5.7
・ひとはなPOSアイコンの白い外周余白を除去
・画像の端まで黒背景が続くように調整
・Android用に maskable アイコンとしても指定
・PWA-5.6までの機能はそのまま維持
・GAS変更不要。GitHub Pages側のみ更新

Android/iPhone/PCで古いアイコンが残る場合は、
PWAを一度削除してからGitHub Pages URLより再インストールしてください。

【PWA-5.7.4 USB TEST】
ChromeOS + USB-C接続の58mmプリンター疎通確認用です。

1. プリンター電源ON
2. データ通信対応USB-CケーブルでChromebookと接続
3. GitHub Pagesの出店レジを開く
4. 上部「USB接続」を押す
5. USB機器の選択画面でプリンターを選ぶ
6. 「USBテスト」を押す
7. 紙に「USB TEST OK」が出ればWebUSB接続成功

確認済みUSB ID:
VID 0x0FE6
PID 0x811E

※ 今回は疎通テスト版です。通常のレシート/領収書ボタンは従来の印刷方式のままです。
※ USBテスト成功後、レシート/領収書をUSBへ直接出す機能へ拡張できます。

【USB DIAG版】
前版はWindowsで確認した VID 0x0FE6 / PID 0x811E に絞っていました。
この版はWebUSBの候補をVID/PIDで絞らず表示します。

手順:
1. Chromebookとプリンターをデータ通信対応USB-Cケーブルで接続
2. プリンター電源ON
3. GitHub PagesをChromeで開く
4. 「USB診断接続」を押す
5. 候補が出たらプリンターと思われるUSB機器を選択
6. 選択後に表示されるVID/PIDを確認
7. 「USBテスト」を押す

候補が1台も出ない場合:
ChromeOS/ChromeがこのプリンターをWebUSB機器として公開していない可能性が高いです。
