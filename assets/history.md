# JavaScriptの歴史
この章ではJavaScriptが生まれてから現在まで, どのような技術が生まれそして滅びていったのかを概観する.

## NCSA Mosaic
1993年, イリノイ大学の米国スーパーコンピュータ応用研究所(NCSA)に所属するマーク・アンドリーセンらによって**NCSA Mosaic**というブラウザがリリースされる.  
NCSA Mosaicはテキストと画像を同一ウィンドウ内に混在して表示させることができる最初のブラウザである.  
尚, HTTP以外にも, FTP・NNTP・Gopherなどのプロトコルが実装されていた.  
その後, NCSAはNCSA Mosaicのマスターライセンスをスパイグラス社に与えた.

ちなみに1993年というのは欧州原子核研究機構(CERN)がWorld Wide Web(WWW)の利用を一般にも開放した年である.

## Netscape Navigator 1.0
NCSA Mosaicをリリースした後, マーク・アンドリーセンらによってモザイク・コミュニケーション社(後のネットスケープ・コミュニケーションズ社)が設立された.

そして1994年, ネットスケープ・コミュニケーションズ社から**Netscape Navigator** 1.0がリリースされる(ベータ版ではMosaic Netscape).  
当初は「Mozilla」という名前でリリースするつもりであったが, マーケティングの事情により変更されている.

## Internet Explorer 1
マイクロソフト社はスパイグラス社からNCSA Mosaicのライセンスを受け, **Internet Explorer**は開発された.  
Internet Explorer 1は1995年８月に公開されたMicrosoft Plus! for Windows95に組み込まれた.  
このバージョンでは機能が少なく, 使用するユーザはほとんどいなかった.

## Netscape Navigator 2.0
1995年12月, Netscape Navigator 2.0がリリースされる.  
これには, ネットスケープ・コミュニケーションズ社のブレンダン・アイク氏が開発した**LiveScript**が実装された.  
その後, ネットスケープ・コミュニケーションズ社と当時提携関係に合ったサン・マイクロシステムズ社(現オラクル)のJavaの勢いに便乗しようとLiveScriptから**JavaScript**に改称された.

ちなみにJavaは同年５月に発表され, 同時にJavaアプレットも発表され, ブラウザで動作するJavaとして注目を集めていた.

また, この頃からDHTML(DynamicHTML), つまり動くWebページを実現するための技術が出始める.

## Internet Explorer 3
1996年８月にInternet Explorer 3がリリースされた.  
マイクロソフト社はInternet ExplorerにJavaScriptを搭載しようと試みたが, ネットスケープ・コミュニケーションズ社がライセンスを付与しなかったため, JavaScriptと似た言語として**JScript**を開発した.  
しかし, JavaScriptとは互換性がなく, JavaScriptで作成されたスクリプトはInternet Explorerで動かず, JScriptで作成されたスクリプトはNetscape Navigatorでは動かないという事態が起き, 開発者を困惑させた.

## Flash
1996年, FutureWave Software社がWebページ上でのアニメーションやインタラクティブな操作を簡単に実現するFutureSplash Playerというプラグインを開発.   
これは後のAdobe Flash Playerとなる.  
Javaアプレットよりも軽量でかつ機能差もほとんどなかったことから, 大流行する.

## ECMAScript
JScriptとJavaScriptが非互換である問題を解決するため, ネットスケープ・コミュニケーションズ社は**Ecma International**という標準化機関にJavaScriptの標準化を依頼する.  
これにより, **ECMA-262**の初版ができ, ECMA-262のことを一般的には**ECMAScript**と呼ぶ.

その後, ECMAScriptは1998年に第２版, 1999年に第３版と順調に策定されていた.  
しかし, 第４版の策定時に, 賛成派のAdobe, Mozilla(旧ネットスケープ・コミュニケーションズ社)と反対派のマイクロソフト社, Yahoo!とで意見が分かれ打ち切りとなる.

詳しくは [第３章 ECMAScriptとは何か]() にて解説する.

この頃から, 無駄にアニメーションするWebページが乱立し, JavaScriptを使ったページの評判がどんどん悪くなった.  
また, ブラウザ自体もセキュリティに対する配慮が十分でなく, JavaScriptの脆弱性を突くウイルスが登場したり, ブラウザに高負荷をかけるブラクラと呼ばれるプログラムが出回るなど, 様々な問題が起こった.  
これらの問題から, JavaScriptを常時オフにする人が続出した.

インタラクティブなWebページは相変わらずFlashが主流であり, FlashにもECMAScriptを元にしたActionScriptが組み込まれ, より一層需要が高まった.
