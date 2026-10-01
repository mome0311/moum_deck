# moum_deck

PCだけで動作する、完全オフライン対応のオープンソースDJアプリケーションです。
手持ちの楽曲ライブラリを、DJコントローラーやキーボード・マウスを使って直感的にミックスできます。

> **English:** moum deck is an offline DJ application for Windows (macOS support in progress) built with Python and Qt. It supports the Native Instruments Traktor Kontrol S2 MK3 (HID, with LEDs) and the Pioneer DDJ-400 out of the box, and any other MIDI / HID controller can be mapped in the built-in Controller Setup.

---

## ✨ 主な特徴

- 🔌 **完全オフライン動作**：ネット接続不要。クラブや野外など場所を選ばずプレイ可能。
- 🎛️ **対応機器**：
  - **Traktor Kontrol S2 MK3**（HID対応・LED/VUメーター連動）
  - **Pioneer DDJ-400**（プリセット完備）動作未確認
  - その他任意の **MIDI / HID コントローラー**（自作マッピング機能搭載）動作未確認
- 🎚️ **デッキ＆ミキサー**：
  - 2/4 デッキ切り替え（Column / Row レイアウト）
  - BPM自動解析、ビートグリッド、SYNC（倍テン/半テン対応）
  - 3バンドEQ、Filter、Mixer FX (Echo / Reverb / Flanger / Crush)
  - 8 Hot Cues、Loop、Beatjump、Quantize
- 🌊 **視認性の高い3バンド波形**：帯域別の色分け表示 & 1〜128拍の無段階ズーム。
- 🎵 **スマートなライブラリ管理**：
  - フォルダスキャン、iTunes/Music XML読み込み、USBメモリ自動認識
  - BPM / Key のバックグラウンド一括解析
- 🖼️ **SNS用セトリ画像書き出し**：プレイリストを正方形・縦長・ストーリーズ用の画像として出力。

---

## 💻 動作環境

| 項目 | 詳細 |
|---|---|
| **OS** | Windows 10 / 11（推奨）<br>macOS（対応作業中） |
| **対応フォーマット** | MP3 / WAV / AIFF / FLAC<br>※AAC(m4a) / ALAC の再生には別途 [ffmpeg](https://ffmpeg.org/) が必要です |
| **オーディオ出力** | 各種オーディオインターフェース、コントローラー内蔵オーディオ（WASAPI / DirectSound / MME） |

---

## 🚀 クイックスタート（Windows）

1. **ダウンロード**
   [Releases](../../releases) ページから最新のインストーラーをダウンロードして実行します。
2. **初回セットアップ**
   起動時に開く「Setup guide」に従って、デバイスと音声出力を設定します。
   *(※「Help › Setup guide…」からいつでも再設定可能です)*
3. **楽曲の読み込み**
   「File › Scan folder…」または iTunes XML を読み込んでライブラリを構築します。

---

## ⌨️️ 既定のキーボード操作

コントローラーがなくても、キーボードだけで操作可能です。

| キー | デッキ A | デッキ B | デッキ C | デッキ D |
|:---:|:---:|:---:|:---:|:---:|
| **再生 / 一時停止** | `Q` | `W` | `E` | `R` |
| **CUE** | `A` | `S` | `D` | `F` |
| **Hot Cue (1-4)** | `1` 〜 `4` | `5` 〜 `8` | - | - |

- **波形ズーム**：`Ctrl` + `=` / `Ctrl` + `-`
- **ダークモード切替**：`Ctrl` + `Shift` + `D`

---
