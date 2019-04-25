# ECMAScriptとは何か
現在, JavaScriptの仕様はECMAScript(ECMA-262)という名前でEcma Internationalによって標準化が行われている.  
この章では, Ecma Internationalという機関について, そしてECMAScriptの移り変わり, ECMAScriptの策定プロセスについて解説する.

## ECMA International
**ECMA International**は情報通信システム分野における国際的な標準化団体である.  
1961年にヨーロッパにおける計算機システムを標準化をするために設立され, 欧州電子計算機工業会という名称で活動していたが, その後1994年に国際的な立場を反映し, ECMA Internationalに改称された.  
本部はスイスのジュネーヴにある.

Ecma Internationalが標準化しているものは多岐に渡り, 代表的なものには,
- ECMA-262(ECMAScript)
- ECMA-327(ECMAScript Compact Profile)
- ECMA-334(C#)
- ECMA-335(共通言語基盤)
- ECMA-357(ECMAScript for XML)
- ECMA-402(国際化API)
- ECMA-404(JSON)

がある.  
このうち, JavaScriptと深く関わりのある, **ECMA-262**(**ECMAScript**), **ECMA-327**(**ECMAScript Compact Profile**), **ECMA-357**(**ECMAScript for XML**), **ECMA-402**(**国際化API**), **ECMA-404**(**JSON**)について解説する.

## ECMAScript
[第２章 JavaScriptの歴史](history.md) で触れたように, ネットスケープ・コミュニケーションズ社のJavaScriptとマイクロソフト社のJScriptの非互換が問題になり, ネットスケープ・コミュニケーションズ社がJavaScriptの標準化をEcma Internalに依頼した.  
こうして生まれたのがECMAScript(規格番号はECMA-262)である.  
また, Ecma Internationalの他にも, ISO/IEC JTC 1からISO/IEC 16262, JISからJIS X 3060として標準化されている.

ECMAScriptにはいくつかのエディションがあり, バージョンごとに新機能の追加が行われている.

|エディション|公開日|
|:--|:--|
|1|1997年６月|
|2|1998年６月|
|3|1999年12月|
|4|放棄|
|5|2009年12月|
|5.1|2011年６月|
|6(2015)|2015年６月|
|2016|2016年６月|
|2017|2017年６月|
|2018|2018年６月|

ちなみに, ECMAScript 6(ECMAScript 2015)以降は１年に１回仕様が改定されることとなっている.
