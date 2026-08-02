# SoundKeyChain

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain1.jpg" width="240px">

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain2.jpg" width="240px">

最大3つの音声ファイル（MP3形式）を保存し、ボタンを押して再生します。
お気に入りの音声データをいつも持ち運んで再生できます。。


## 使い方

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain3.jpg" width="240px">

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain4.jpg" width="240px">

コイン電池(CR2025 or CR2032)を、基板側がマイナス側に向きに差し込みます。

1, 2, 3のボタンを押すと、それぞれ001.mpg, 002.mp3, 003.mp3を再生します。

※音声再生中の消費電流が約10mA程度で、再生終了の約2秒後に低消費電力モード（5uA程度）になります。

[音声再生例](https://github.com/user-attachments/assets/13cc77fd-8777-434c-830f-a518a013cece)


## 音声データの保存

**コイン電池をはずし**、USB Type-CケーブルでPCと接続すると、USBメモリドライブとして認識されます。
用意した音声データ（最大3つ、合計約300KB以下）のファイルをコピーし、とりはずしてください。
ファイル名は、各ボタンに応じて"001.mp3", "002.mp3", "003.mp3"としてください（固定）。

容量は合計で最大300KBのため、必要に応じてビットレートやビット数の調整、モノラル化などの処理を行ってください。
（例えば[Webのmp3データ形式変換サイト](https://online-audio-converter.com/ja/)などを利用できます）


## 音量の変更

PCに接続してUSBメモリとして認識されているドライブの中にあるconfig.txtで機能を設定をできます。設定方法の詳細はconfig.txtに記載されていますが、1行目の2-3文字目（初期設定では"30"）で音量を変更できます（最大30）。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
