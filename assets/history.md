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
これにより, 1997年に**ECMA-262**の初版が策定された.  
ECMA-262のことを一般的には**ECMAScript**と呼ぶ.

その後, ECMAScriptは1998年に第２版, 1999年に第３版と順調に策定されていた.  
しかし, 第４版の策定時に, 賛成派のAdobe, Mozilla(旧ネットスケープ・コミュニケーションズ社)と反対派のマイクロソフト社, Yahoo!とで意見が分かれ打ち切りとなる.

詳しくは [第３章 ECMAScriptとは何か]() にて解説する.

この頃から, 無駄にアニメーションするWebページが乱立し, JavaScriptを使ったページの評判がどんどん悪くなった.  
また, ブラウザ自体もセキュリティに対する配慮が十分でなく, JavaScriptの脆弱性を突くウイルスが登場したり, ブラウザに高負荷をかけるブラクラと呼ばれるプログラムが出回るなど, 様々な問題が起こった.  
これらの問題から, JavaScriptを常時オフにする人が続出した.

インタラクティブなWebページは相変わらずFlashが主流であり, FlashにもECMAScriptを元にしたActionScriptが組み込まれ, より一層需要が高まった.

## Ajax
2000年代後半, GoogleがJavaScriptの**Ajax**技術を使ったGoogle Mapsを発表し, これにより再びJavaScriptが見直され始める.  
Ajaxは画面を遷移することなくデータをやり取りし, 描画する技術群のことを指し, UI/UX的に見てかなり良いものとされている.  
また, Ajaxは `XMLHttpRequest` を中核とした技術群で, これはマイクロソフト社がActiveXを実装し始めたのがはじまりだった.  
当初は, Ajaxでやりとりするデータ構造にXMLが用いられることが多かったが, 現在ではJSONを使ってやり取りされることが多くなっている.  
これらの技術については, [第n章 非同期通信]() にて詳しく解説する.

## ライブラリ
これまでJavaScriptはフォームの内容を加工したり, アニメーションを付けたりするような小規模なものに使われていたが, Ajaxの普及により大規模なプロジェクトにも用いられるようになってきた為, JavaScriptにもライブラリが登場した.  
2005年に**prototype.js**, 2010年に**jQuery**が登場し両者ともに人気を博した.  
また, jQueryはセレクタによる要素の絞り込みができる機能を備えており, それが便利だということでJavaScriptにも `querySelector`, `querySelectorAll` として実装されるなど, JavaScript自体にも影響を与えている.

## V8
2008年に**V8**と呼ばれるJavaScriptエンジンをGoogleが公開され, Google ChromeやNode.jsに採用された.  
V8はJITコンパイラを備えており, それまでのインタプリタ型のJavaScriptエンジンでの実行速度が遅いという問題を改善した.

## ECMAScript 5
ECMAScriptの標準化は長らくの間停滞していたが, 2009年にECMA-262 第５版が策定される.  
これはECMA-262 第3.1版を踏襲している.

## Node.js
2009年, **Node.js**が誕生する.  
Node.jsはサーバサイドを中心とした環境で動作するJavaScriptで, これまでのブラウザで動作するという常識を覆した.
Node.jsは主に以下のような特徴を持つ.
- ノンブロッキングI/O
- CommonJSの実装
- npmによるパッケージ管理

ちなみにそれまでにもサーバサイドのJavaScriptは存在しており, その歴史は1995年にまで遡る.  
それは**LiveWire**と呼ばれる, ネットスケープ・コミュニケーションズ社が開発したNetscape Navigator上で動作していたJavaScriptエンジンをWebサーバに移植したものである.  
LiveWireという名前になった経緯としては, 当時マイクロソフト社とサン・マイクロシステムズ社が「Java」という名前の使用について揉めており, ServerSide JavaScriptという名称が使用できなかったためである.  
また, その当時にglue言語という考え方が流行しており, LiveWireをコンポーネント同士を結びつける, ソフトウェア間のワイヤーとして機能させたかったという思想が含まれている.

## フレームワーク
JavaScriptが見直され, どんどん大規模化・複雑化していく中で, ライブラリだけでは対応しきれなくなっていた.  
そういった流れから, プロジェクトの雛形自体を提供する, **Backbone.js**や**AngularJS**をはじめとするフレームワークが登場した.

// タスクランナー, テンプレートエンジン, AltJS

## ECMAScript 6
ECMA-262第６版が策定される.  
プロジェクトコードはHarmony.  
この年からは年に１回新しい仕様が策定されることとなったため, ECMAScript 2015とも呼ばれる.
