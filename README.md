FlickrExIcon
============

FlickrExIconはFlickrExを拡張してExif情報のテキストをアイコン化する処理を目的に作りました。
始めはF-stop / Exposure / ISOに的を絞り、アイコン化をしました。

## 使い方

使い方は、下記のHTMLコードをコピーしてご自分のサイトに貼り付けるだけで利用できます。

```HTML
    ...
<link rel="stylesheet" type="text/css" href="assets/skins/dark/dark.css">
    ...
<script type="text/javascript">
    //var FLICKREX_API_KEY = "18c9f79a96fd34c3b3f16a93fb0a5d3c";
    //var FLICKREX_EXIF_JQUERY_SELECTOR = ".flickr2tag-img img";
</script>
<script type="text/javascript" src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.2.min.js"></script>
<script type="text/javascript" src="js/FlickrEx/flickrex.js"></script>
<script type="text/javascript" src="js/FlickrExIcon/photosetting.js"></script>
```

## ExifExIconのカスタマイズ

アイコンのスキンはdarkを一つ用意してあります。
フォントは"Titillium Text"を使用しました。

コードは各数字、記号ごとにブロックが生成されるので、スキンとそれに対応したCSSを用意するだけで見た目の変更が可能です。

コードブロックはF-stop / Exposure / ISOのみに対応していて、拡張するのに必要な形は追って追加する予定です。

## Thanks

* http://www.fontsquirrel.com/fonts/TitilliumText
* https://github.com/drikin/FlickrEx
