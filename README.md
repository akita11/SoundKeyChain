# SoundKeyChain

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain1.jpg" width="240px">

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain2.jpg" width="240px">

最大3つの音声ファイル（MP3形式）を保存し、ボタンを押して再生します。
お気に入りの音声データをいつも持ち運んで再生できます。。


## 使い方

<img src="https://github.com/akita11/SoundKeyChain/blob/main/SoundKeyChain3.jpg" width="240px">

コイン電池(CR2025)を、基板側がマイナス側に向きに差し込みます。
一度、どれかのボタンを押して再生してください。

1, 2, 3のボタンを押すと、それぞれ001.mpg, 002.mp3, 003.mp3を再生します。

※電池を入れた直後は消費電流が5mA（再生中と同等）あり電池の消耗が進みますのでご注意ください。一度再生したあとは、低消費電力モード（5uA程度）になります。


## 音声データの保存

_コイン電池をはずし_、USB Type-CケーブルでPCと接続すると、USBメモリドライブとして認識されます。
用意した音声データ（最大3つ、合計約300KB以下）のファイルをコピーし、とりはずしてください。
ファイル名は、"001.mp3", "002.mp3", "003.mp3"としてくださ（固定）。

容量は合計で最大300KBのため、必要に応じてビットレートやビット数、モノラル化などの処理を行ってください。
（例えば[Webのmp3データ形式変換サイト](https://online-audio-converter.com/ja/)などを利用できます）


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
