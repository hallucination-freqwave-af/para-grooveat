# para grooveat

[English](#english)

二本以上の映像を重ねて、見えるほうだけを信号のように切り替えるブラウザアプリ。
五つの層が対等に入れ替わる。作為がずれて、偶然に毎回予想を外される。その意外性を録るための道具。

インストール不要。HTML ファイル一つで動く。

**▶ [ブラウザで今すぐ開く](https://hallucination-freqwave-af.github.io/para-grooveat/para_grooveat.html)**

## はじめかた

1. 上のリンクを Chrome で開く（手元に置きたいなら `para_grooveat.html` をダウンロードして開いてもいい）
2. 映像を二本以上、画面に放り込む

素材はブラウザの中で読むだけで、どこにも送られない。

画面は右上のボタンで日本語 ⇄ English を切り替えられる（最初はブラウザの言語に合わせる）。

## 素材の準備

読み込めるのは **H.264 の mp4 / mov**。iPhone の動画や ProRes などはそのままだと入らないことがある。

変換は [HandBrake](https://handbrake.fr/)（無料）で：

- プリセット「**Fast 1080p30**」を選んで書き出すだけ
- 4K の素材なら「**Fast 2160p60 4K**」
- コマ数は元のまま通る（30 は上限で、5fps の素材は 5fps のまま）

写真はまとめて放り込むと、一つの層に束で入る。

## 遊びかた

- **演奏**：流しながら、つまみがその場で効く
- **生成**：決めた尺で一本組む
- **録画**：押して始め、もう一回押して止めると保存される
- **収集**：通しで録りながら「ここから」で印を打ち、ええところだけ部品として落とす（ffmpeg で繋ぐ手順も一緒に出る）

## VDJ で遊ぶ、編集で刻んで遊ぶ

層は5つ読み込めて、見えるのは上下の2枚。残りは差し替え用の手札。

- **VDJ として**：音を流しながら、キーボードを楽器みたいに叩く
  - `1`〜`5`：その層へ切り替え（同じ数字をもう一回叩くと、少し先へ進む）
  - ほかの文字キー：次の層へ
  - 長押し：押してる間だけ切り替わり、離すと戻る
  - `H`：自動の切り替えに戻る
  - MIDI パッドやコントローラーを持ってたら、キーにアサインしてみて
- **編集で刻んで**：録ったテイクを Final Cut Pro などに持ち込んで、さらに切って、並べて、ぶつける

演奏で素材を生んで、編集で作品にする。どっちで止めてもいい。

## 書き出し

録画ボタンの横に、書き出しの形式が出る。

- **MP4**（Chrome の最近の版など）→ そのまま Final Cut Pro などに入る
- **webm**（MP4 で録れないブラウザ）→ 編集ソフトに入れるなら HandBrake で MP4 に

## 点滅について

光の点滅が激しい映像になることがある。光に敏感な人は注意して使ってほしい。人前で流すときは、冒頭に注意書きを入れるのがおすすめ。

## 改造について

好きに使って、好きに改造していい。AI に投げて、まったく別の使い方にしてもいい。
ただ、できたものは見せてほしい。フォークしてくれたら見に行きます。

## 作った人

狂った周波数（hallucination-freqwave-af）

- YouTube：[作品のプレイリスト](https://www.youtube.com/playlist?list=PL9Kh2obqNfCkZ_d_TJ3XWH0phgQjvP9p0)
- Instagram：[hallucination_freqwave_af](https://www.instagram.com/hallucination_freqwave_af/)

## ライセンス

MIT

---

## English

A browser app that layers two or more videos and switches which one is visible, like a signal.
Five layers swap places as equals. Intention slips, and chance keeps beating your expectations. It's a tool for recording that surprise.

No install. It runs from a single HTML file.

**▶ [Open in your browser](https://hallucination-freqwave-af.github.io/para-grooveat/para_grooveat.html)**

### Getting started

1. Open the link above in Chrome (or download `para_grooveat.html` and open it locally)
2. Drop two or more videos onto the screen

Your footage is only read inside the browser. Nothing is uploaded.

The app switches between Japanese and English with the button at the top right (it follows your browser language at first).

### Preparing footage

Supported: **H.264 mp4 / mov**. iPhone videos and ProRes may not load as-is.

Convert with [HandBrake](https://handbrake.fr/) (free):

- Pick the "**Fast 1080p30**" preset and export
- For 4K footage, "**Fast 2160p60 4K**"
- Frame rate stays as it was (30 is the cap; 5fps footage stays 5fps)

Drop a batch of photos at once and they go into one layer as a bundle.

### Modes

- **Live**: the knobs take effect instantly while it runs
- **Generate**: builds one piece at a length you choose
- **Record**: press to start, press again to stop and save
- **Collect**: record straight through, mark "from here", and keep only the good parts as pieces (ffmpeg steps to join them are included)

### Play it like a VDJ, or cut it up in an editor

You can load five layers; two are visible, top and bottom. The rest are cards in your hand, ready to swap in.

- **As a VDJ**: play music and hit the keyboard like an instrument
  - `1`–`5`: switch to that layer (hit the same number again to jump a little ahead)
  - Any other letter key: next layer
  - Hold: switches only while held, returns on release
  - `H`: back to automatic switching
  - Got a MIDI pad or controller? Try mapping it to the keys
- **In an editor**: bring your takes into Final Cut Pro or similar, then cut, arrange, and smash them together

Make material by playing, make the work by editing. Stopping at either is fine.

### Export

The export format shows next to the record button.

- **MP4** (recent Chrome, etc.) → goes straight into Final Cut Pro and the like
- **webm** (browsers that can't record MP4) → convert to MP4 with HandBrake before editing

### About flashing

The output can include intense flashing light. Please take care if you are sensitive to light. When showing it to an audience, adding a warning at the start is recommended.

### Remixing

Use it however you like and modify it however you like. Hand it to an AI and turn it into something completely different, if you want.
Just show me what you make. Fork it and I'll come take a look.

### Made by

狂った周波数 (hallucination-freqwave-af)

- YouTube: [playlist of works](https://www.youtube.com/playlist?list=PL9Kh2obqNfCkZ_d_TJ3XWH0phgQjvP9p0)
- Instagram: [hallucination_freqwave_af](https://www.instagram.com/hallucination_freqwave_af/)

### License

MIT
