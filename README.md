# DxLibToHTML5Test

DxLibアプリをHTML5に出力する試み

## Install

準備中 (気が向いたらQiitaにでも記事を書きます)

## Backend

### DxPortLib

- ライブラリサイト: <https://github.com/mauvecow/DxPortLib>
- 本家 DXライブラリが Android, iOS 対応する前から、Windows 以外のビルトターゲットを広くサポートしていた
- SDL2のラッパーライブラリ

### emscripten

- ライブラリサイト: <https://emscripten.org>
- C/C++で書いたプログラムをHTML上で動かすためのトランスパイラ環境
- WebGLのほか, SDLにも対応した(らしい)

## Sample Games

- 公開しているものすべて, DxLibアプリからHTML5へのの仕上がりを誰もが確認できるようにするためのものです.予告なく削除することもありますことをご了承願います.
- Safari, Google Chromeでは音が出ません (仕様です)
- FireFox, Microsoft Edgeでは音が出るようです
- それ以外のブラウザ, およびWebGLに対応していないデバイスはサポート外です

### MegaDeath

![MegaDeath](http://qpic.jp/games/402ede0faa1f78ffa77971a7ed7493b7/参考画面だよ.png)

- HTML5版: <https://nokotan.github.io/MegaDeath/index.html>
- Windows, MacOS版: <http://www.qpic.jp/new/works/games/187>

### EscapeSPY

- HTML5版: <https://nokotan.github.io/EscapeSPY/index.html>
- Windows, MacOS版: (準備中)

### ももぐり

![momo](http://qpic.jp/games/097c2d12eea3c652e88b0cc27bbb2258/ScreenShot.png)

- HTML5版: <https://nokotan.github.io/momo/index.html>
- Windows, MacOS版: <http://www.qpic.jp/new/works/games/178>