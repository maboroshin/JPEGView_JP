# JPEGView 1.0.39.1 日本語化

〆 バージョン1.0.40でGithubからのダウンロードに組み込み済み。

[JPEGView](https://github.com/sylikc/jpegview), ([sourceferge](https://sourceforge.net/projects/jpegview/)) は、タイトルバー以外がない画像ビューアで、マウスホイールで同じフォルダ内の画像を切り替えできます。自動のスライドショーもできるし、かなり高速にできる。（マウスホイールで画像切り替えの有効化は、```JPEGView.ini``` の ```NavigateWithMouseWheel``` の値を ```true``` にする）

sourceferge本家の同梱では、2015年の日本語化ファイルが同梱されているが、JPEGViewの最終更新は2018年2月のバージョン1.0.37なので未訳部分が残っていた。開発が停滞しているようで、2019年にこちらの開発者に日本語化ファイルを送付したが返信がないので公開しました。

その後、別の開発者が引き継ぎGithubに移動して、2021年にバージョン1.0.37.1に、2022年に1.0.39.1となっていたが、送った日本語ファイルになっていない（開発者が違うので笑）。これに気づいてGithubで併合リクエストを出しました。次のバージョン1.0.40から本家に同梱されています。

## 日本語ファイルの導入

`JPEGView.exe` と同じフォルダに [strings_ja.txt](strings_ja.txt) を置きます。[PortableAppsのJPEGView](https://portableapps.com/apps/graphics_pictures/jpegview_portable) では、`JPEGViewPortable\App\JPEGView` の中です。

## DukeDogDukedom さんによる日本語化
別の作者の日本語化として、2015年のものが、[DukeDogDukedom 1.0.33 日本語パック](https://dukedogdukedom.blogspot.com/2015/01/jpegview-v1033.html) に公開されている。こちらはヘルプなどすべて翻訳されたかなりの力作です。

**DukeDogDukedomの2015年版(1.0.33)と本家2018年版(1.0.37)の差分**
* [JPEGView.ini 差分](https://sourceforge.net/p/jpegview/code/374/tree//current/JPEGView/Config/JPEGView.ini?diff=311)
* [KeyMap.txt 差分](https://sourceforge.net/p/jpegview/code/370/tree//current/JPEGView/Config/KeyMap.txt?diff=306)
* [readme.html 差分](https://sourceforge.net/p/jpegview/code/366/tree//current/JPEGView/Config/readme.html?diff=312)

## ライセンス

本家のライセンスがオープンソースの GPLv2 なので、日本語ファイルはそれに従っています。どなたでもライセンスを継承して更新してください。

* Software developer : David Kleiner et al.
* 1st Japanese translation : by Hiroyuki Matenokoji. (2015) (この翻訳者名は、[readme.txt](https://github.com/sylikc/jpegview/blob/master/readme.txt) の 1.0.34 に記載あり。)
* 2nd Japanese translation : by maboroshin (2019, Adjustment, and translate little new part)

## 翻訳メモ

英語文字列一覧となる翻訳元ファイルはないとのこと(2022年3月): https://github.com/sylikc/jpegview/pull/9#issuecomment-870261967

修正忘れ 別に → 別の
