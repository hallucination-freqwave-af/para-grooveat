# para grooveat

二本以上の映像を重ねて、見えるほうだけを信号のように切り替えるブラウザアプリ。
五つの層が対等に入れ替わる。作為がずれて、偶然に毎回予想を外される。その意外性を録るための道具。

インストール不要。HTML ファイル一つで動く。

**▶ [ブラウザで今すぐ開く](https://hallucination-freqwave-af.github.io/para-grooveat/para_grooveat.html)**

## はじめかた

1. 上のリンクを Chrome で開く（手元に置きたいなら `para_grooveat.html` をダウンロードして開いてもいい）
2. 映像を二本以上、画面に放り込む

素材はブラウザの中で読むだけで、どこにも送られない。

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
