# moum deck

**違うDJコントローラー同士で、そのままB2Bできる DJ アプリ。**

![moum deck のメイン画面](docs/images/main.png)

Traktor のコントローラーと rekordbox のコントローラーのように、**違う機材を持ち寄って同じ画面でB2B**ができます。
1人2デッキ・合計4デッキ。ミキサーとヘッドホンは、それぞれ自分のコントローラーのものを使います。

- 無料・オフラインで動作（Windows 10 / 11。macOS は開発中）
- BPM・キーの自動解析、SYNC、ホットキュー、ループ、エフェクトなど、DJ に必要な機能をひととおり搭載

**[⬇ 最新のインストーラー（Releases）](../../releases/latest)**　・　**[📖 画面と機能の説明](docs/guide.md)**

> **English:** A free, offline DJ app that lets two DJs play back-to-back with different controllers (e.g. Traktor Kontrol S2 MK3 + Pioneer DDJ-400) on one shared set of decks.

## moum deck ならではの機能

**① 違うコントローラーでB2B**
メーカーの違うコントローラーを2台つないで、1人2デッキずつ担当できます。各コントローラーのミキサーは自分のデッキだけに効き、ヘッドホンもそれぞれの端子でモニターします。

**② PC2台をつないでB2B（Partner PC）** 🧪
インターネットなしで、LANケーブルや Wi-Fi でもう1台の moum deck とつながります。相手のデッキの曲が自分の画面に出て、音は1つの出力にまとめられます。

**③ 録音と同時にミックス映像を作成**
録音すると、流れている曲のジャケット・曲名・BPM・キー・セットリストが入った映像（.mp4）も一緒にできます。横長・縦長・正方形を選べます。

**④ セットリストを画像で書き出し**
プレイリストを、SNS にそのまま載せられる画像にできます。

| ③ ミックス映像の設定 | ④ セットリスト画像 |
|---|---|
| ![Rec settings。映像のプレビューと設定](docs/images/rec_settings.png) | ![セットリスト画像の書き出し](docs/images/setlist_image.png) |

**⑤ キューやプレイリストをUSBメモリに保存**
USBメモリの曲に付けたキュー・ループ・プレイリストは USB 側に保存されるので、別のPCの moum deck に挿すだけで引き継げます。

**⑥ moum player と連携**
音楽プレイヤー [moum player](https://github.com/mome0311/moum_player) で直した曲名やアーティストが、自動で反映されます。

## そのほかの画面

| 4デッキ | ダークモード |
|---|---|
| ![4デッキ表示](docs/images/4decks.png) | ![ダークモード](docs/images/dark.png) |

## 対応状況

| 使い方 | 状況 |
|---|---|
| コントローラー1台（Traktor Kontrol S2 MK3） | ✅ 使えます |
| コントローラー1台（Pioneer DDJ-400 / DDJ-FLX4） | 🧪 動作未確認 |
| 1台のPCに違うコントローラー2台でB2B | 🧪 動作未確認 |
| PC2台でB2B（Partner PC） | 🧪 動作未確認 |
| macOS | 🚧 開発中 |

## はじめかた

1. [Releases](../../releases/latest) からインストーラー（`moum_deck-x.x.x-Setup.exe`）をダウンロードして実行
2. 初回起動の「Setup guide」で、コントローラーと音の出力先を選ぶ
3. 「File › Scan folder…」で音楽フォルダを読み込む
4. 曲をダブルクリックしてデッキに載せる

対応形式は MP3 / WAV / AIFF / FLAC です。AAC（m4a）/ ALAC だけ ffmpeg が必要です。

画面の見かた、機能の一覧、設定、キーボード操作は [画面と機能の説明](docs/guide.md) にまとめています。

<sub>スクリーンショットは v2.2.0。写っている曲は撮影用のサンプルです。</sub>
