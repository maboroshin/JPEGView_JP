# JPEGView 1.0.39.1 日本語化

[JPEGView](https://sourceforge.net/projects/jpegview/) は、タイトルバー以外がない画像ビューアで、マウスホイールで同じフォルダ内の画像を切り替えできます。自動のスライドショーもできるし、かなり高速にできる。

日本語化は2015年のものが本家に同梱されていて、本家の最終更新は2018年2月(バージョン1.0.37)なので未訳部分があった。開発がひと段落しているようで、2019年に本家開発者に送付したが返信がないので公開。

いつのまにか開発がGithubに移動して、2021年に後続の1.0.37.1にバージョンアップ、2022年に1.0.39.1だが、日本語ファイルは更新されていない。気づいてGithubで併合リクエストを出しました。併合されればその次のバージョンで本家に同梱かと。

## インストール

`JPEGView.exe` と同じフォルダに [strings_ja.txt](strings_ja.txt) を置きます。PortableApps では、`JPEGViewPortable\App\JPEGView` の中です。

## DukeDogDukedom さんによる日本語化
別の作者の日本語化として、2015年のものが、[DukeDogDukedom 1.0.33 日本語パック](https://dukedogdukedom.blogspot.com/2015/01/jpegview-v1033.html) に公開されている。こちらはヘルプなどすべて翻訳されたかなりの力作です。

**DukeDogDukedomの2015年版(1.0.33)と本家2018年版(1.0.37)の差分**
* [JPEGView.ini 差分](https://sourceforge.net/p/jpegview/code/374/tree//current/JPEGView/Config/JPEGView.ini?diff=311)
* [KeyMap.txt 差分](https://sourceforge.net/p/jpegview/code/370/tree//current/JPEGView/Config/KeyMap.txt?diff=306)
* [readme.html 差分](https://sourceforge.net/p/jpegview/code/366/tree//current/JPEGView/Config/readme.html?diff=312)

## ライセンス

本家のライセンスがオープンソースの GPLv2 なので、それに従います。どなたでもライセンスを継承して更新してください。

* Software developer : David Kleiner et al.
* 1st Japanese translation : by Hiroyuki Matenokoji. (2015)
* 2nd Japanese translation : by maboroshin (2019, Adjustment, and translate little new part)

2015年の翻訳者名は、[readme.txt](https://github.com/sylikc/jpegview/blob/master/readme.txt) の 1.0.34 に記載あり。

英語文字列一覧となる翻訳元ファイルはないとのこと(2022年3月): https://github.com/sylikc/jpegview/pull/9#issuecomment-870261967
