## FontBakery report

fontbakery version: 0.12.9



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Pochaevsk-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[17] Pochaevsk-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.fontbakery.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.9, while a newer 0.12.10 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">uk_Cyrl (Ukrainian)</td>
<td align="left">Some base glyphs were missing: ʼ, ґ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sr_Cyrl (Serbian)</td>
<td align="left">Some base glyphs were missing: ђ, љ, њ, ћ, џ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bs_Cyrl (Bosnian (Cyrillic))</td>
<td align="left">Some base glyphs were missing: Ђ, Љ, Њ, Ћ, Џ, ђ, љ, њ, ћ, џ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">uk_Cyrl (Ukrainian)</td>
<td align="left">Some auxiliary glyphs were missing: ʼ, ґ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Cyrillic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sr_Cyrl (Serbian)</td>
<td align="left">Some auxiliary glyphs were missing: ђ, љ, њ, ћ, џ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x030A (COMBINING RING ABOVE)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2122 (TRADE MARK SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
acutecomb (U+0301), gravecomb (U+0300), uni0307 (U+0307), uni0308 (U+0308), uni030B (U+030B), uni030F (U+030F), uni0311 (U+0311), uni0483 (U+0483), uni0484 (U+0484), uni0485 (U+0485), uni0486 (U+0486), uni2DE00487 (U+F4E0), uni2DE1 (U+2DE1), uni2DE60487 (U+F4E6), uni2DE70487 (U+F4E7), uni2DEB0487 (U+F4EB), uni2DF00487 (U+F4F0), uni2DF20487 (U+F4F2), uni2DF30487 (U+F4F3), uni2DFD0487 (U+F4FD), uniE000 (U+E000), uniE002 (U+E002) and uniE004 (U+E004)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0360 (U+0360), uni20DD (U+20DD) and uniA66F (U+A66F)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: .null	Contours detected: 2	Expected: 0

- Glyph name: ydieresis	Contours detected: 2	Expected: 3

- Glyph name: afii10044	Contours detected: 1	Expected: 2

- Glyph name: afii10070	Contours detected: 1	Expected: 2

- Glyph name: afii10076	Contours detected: 2	Expected: 1

- Glyph name: afii10092	Contours detected: 1	Expected: 2

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: afii10071	Contours detected: 3	Expected: 4

- Glyph name: afii10103	Contours detected: 1	Expected: 2

- Glyph name: afii10109	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: .null	Contours detected: 2	Expected: 0

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: ydieresis	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 887 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 453:
plus</p>
<p>Width = 611:
less</p>
<p>Width = 376:
equal</p>
<p>Width = 600:
greater</p>
<p>Width = 541:
logicalnot</p>
<p>Width = 579:
plusminus, divide, multiply</p>
<p>Width = 352:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Font has **proper** whitespace glyph names? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Glyph 0x00A0 is called &quot;nbspace&quot;: Change to &quot;uni00A0&quot;</p>
 [code: not-recommended-00a0]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* paragraph (U+00B6): L&lt;&lt;41.0,490.0&gt;--&lt;41.0,489.0&gt;&gt;/B&lt;&lt;41.0,489.0&gt;-&lt;43.0,540.0&gt;-&lt;82.0,583.0&gt;&gt; = 2.245742565895049

* u1F312 (U+1F312): B&lt;&lt;468.0,49.0&gt;-&lt;442.0,33.0&gt;-&lt;425.0,33.0&gt;&gt;/B&lt;&lt;425.0,33.0&gt;-&lt;432.0,32.0&gt;-&lt;435.0,32.0&gt;&gt; = 8.13010235415596

* u1F318 (U+1F318): B&lt;&lt;376.5,763.0&gt;-&lt;384.0,766.0&gt;-&lt;393.0,768.0&gt;&gt;/L&lt;&lt;393.0,768.0&gt;--&lt;379.0,768.0&gt;&gt; = 12.528807709151492

* u1F377 (U+1F377): B&lt;&lt;466.5,415.5&gt;-&lt;489.0,424.0&gt;-&lt;507.0,431.0&gt;&gt;/B&lt;&lt;507.0,431.0&gt;-&lt;499.0,430.0&gt;-&lt;487.5,430.0&gt;&gt; = 14.12548915823142

* u1F41F (U+1F41F): B&lt;&lt;516.0,308.0&gt;-&lt;543.0,314.0&gt;-&lt;730.0,332.0&gt;&gt;/B&lt;&lt;730.0,332.0&gt;-&lt;702.0,336.0&gt;-&lt;675.5,337.5&gt;&gt; = 13.62826507913694

* u1F41F (U+1F41F): L&lt;&lt;833.0,445.0&gt;--&lt;914.0,405.0&gt;&gt;/B&lt;&lt;914.0,405.0&gt;-&lt;900.0,416.0&gt;-&lt;900.0,434.0&gt;&gt; = 11.875815566048908

* uni263D (U+263D): B&lt;&lt;114.0,764.0&gt;-&lt;104.0,766.0&gt;-&lt;93.0,767.0&gt;&gt;/B&lt;&lt;93.0,767.0&gt;-&lt;107.0,763.0&gt;-&lt;125.5,749.0&gt;&gt; = 10.750966993188039

* uni263D (U+263D): B&lt;&lt;121.5,28.5&gt;-&lt;110.0,20.0&gt;-&lt;103.0,20.0&gt;&gt;/B&lt;&lt;103.0,20.0&gt;-&lt;110.0,19.0&gt;-&lt;113.0,18.5&gt;&gt; = 8.13010235415596

* uni263E (U+263E): B&lt;&lt;359.5,749.0&gt;-&lt;378.0,763.0&gt;-&lt;392.0,767.0&gt;&gt;/B&lt;&lt;392.0,767.0&gt;-&lt;382.0,766.0&gt;-&lt;372.0,764.0&gt;&gt; = 10.234802763423207

* uni263E (U+263E): B&lt;&lt;372.0,18.5&gt;-&lt;375.0,19.0&gt;-&lt;382.0,20.0&gt;&gt;/B&lt;&lt;382.0,20.0&gt;-&lt;376.0,20.0&gt;-&lt;364.0,28.5&gt;&gt; = 8.13010235415596
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* N (U+004E): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* Ntilde (U+00D1): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* T (U+0054): L&lt;&lt;350.0,504.0&gt;--&lt;352.0,124.0&gt;&gt;

* afii10025 (U+0417): L&lt;&lt;90.0,474.0&gt;--&lt;89.0,591.0&gt;&gt;

* afii10043 (U+0429): L&lt;&lt;713.0,607.0&gt;--&lt;712.0,21.0&gt;&gt;

* afii10090 (U+0448): L&lt;&lt;358.0,82.0&gt;--&lt;361.0,451.0&gt;&gt;

* afii10148 (U+0474): L&lt;&lt;211.0,302.0&gt;--&lt;210.0,46.0&gt;&gt;

* bracketleft (U+005B): L&lt;&lt;180.0,-104.0&gt;--&lt;334.0,-103.0&gt;&gt;

* bracketright (U+005D): L&lt;&lt;19.0,-103.0&gt;--&lt;173.0,-104.0&gt;&gt;

* e (U+0065): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* eacute (U+00E9): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* ecircumflex (U+00EA): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* edieresis (U+00EB): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* egrave (U+00E8): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* onequarter (U+00BC): L&lt;&lt;216.0,635.0&gt;--&lt;215.0,361.0&gt;&gt;

* uni046C (U+046C): L&lt;&lt;512.0,367.0&gt;--&lt;168.0,369.0&gt;&gt;

* uni046D (U+046D): L&lt;&lt;478.0,263.0&gt;--&lt;168.0,265.0&gt;&gt;

* uni046D (U+046D): L&lt;&lt;532.0,0.0&gt;--&lt;533.0,246.0&gt;&gt;

* uni0476 (U+0476): L&lt;&lt;211.0,302.0&gt;--&lt;210.0,46.0&gt;&gt;

* uni1C85 (U+1C85): L&lt;&lt;361.0,0.0&gt;--&lt;358.0,369.0&gt;&gt;

* uni1C85 (U+1C85): L&lt;&lt;652.0,0.0&gt;--&lt;651.0,128.0&gt;&gt;

* uni1C85 (U+1C85): L&lt;&lt;763.0,353.0&gt;--&lt;764.0,133.0&gt;&gt;

* uniA656 (U+A656): L&lt;&lt;421.0,504.0&gt;--&lt;570.0,505.0&gt;&gt;

* uniA656 (U+A656): L&lt;&lt;570.0,482.0&gt;--&lt;421.0,483.0&gt;&gt;

* uniE5D1 (U+E5D1): L&lt;&lt;172.0,761.0&gt;--&lt;173.0,450.0&gt;&gt;

* uniE5D1 (U+E5D1): L&lt;&lt;173.0,404.0&gt;--&lt;175.0,0.0&gt;&gt;

* uniE5D1 (U+E5D1): L&lt;&lt;690.0,761.0&gt;--&lt;691.0,438.0&gt;&gt;

* uniE5D1 (U+E5D1): L&lt;&lt;691.0,341.0&gt;--&lt;692.0,0.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̋ j̀ j́ j̈ j̑ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ȉ ȋ i̾ i҃ i҄ i҅ i҆ i҇ iⷠ iⷡ iⷢ iⷣ iⷤ iⷥ iⷦ iⷧ iⷨ iⷩ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ekpeye (Latn, 226,000 speakers), Bafut (Latn, 158,146 speakers), Dan (Latn, 1,099,244 speakers), Mango (Latn, 77,000 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Gulay (Latn, 250,478 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), South Central Banda (Latn, 244,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Nzakara (Latn, 50,000 speakers), Zapotec (Latn, 490,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Ma’di (Latn, 584,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), Dutch (Latn, 31,709,104 speakers), Sar (Latn, 500,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Aghem (Latn, 38,843 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Fur (Latn, 1,230,163 speakers), Lithuanian (Latn, 2,357,094 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ejagham (Latn, 120,000 speakers), Dii (Latn, 71,000 speakers), Ngbaka (Latn, 1,020,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+007F : try adding symbols</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, coptic, old-permic, tai-le, syriac, math</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+10FB GEORGIAN PARAGRAPH SEPARATOR: try adding georgian</li>
<li>U+2000 EN QUAD: not included in any glyphset definition</li>
<li>U+2001 EM QUAD: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2006 SIX-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2007 FIGURE SPACE: not included in any glyphset definition</li>
<li>U+2008 PUNCTUATION SPACE: not included in any glyphset definition</li>
<li>U+200A HAIR SPACE: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: modi, thaana, kharoshthi, dogra, yi, hanunoo, tai-tham, pahawh-hmong, avestan, balinese, hatran, khudawadi, tagalog, javanese, khmer, siddham, sinhala, meetei-mayek, tirhuta, syriac, warang-citi, syloti-nagri, buginese, bengali, duployan, batak, new-tai-lue, myanmar, mandaic, gunjala-gondi, tifinagh, limbu, gujarati, tamil, devanagari, rejang, kannada, sharada, buhid, newa, kaithi, mongolian, arabic, mahajani, tai-viet, takri, gurmukhi, kayah-li, sundanese, saurashtra, psalter-pahlavi, sogdian, khojki, tagbanwa, grantha, lepcha, malayalam, lao, telugu, bhaiksuki, nko, manichaean, tibetan, chakma, hebrew, masaram-gondi, thai, cham, zanabazar-square, tai-le, phags-pa, hanifi-rohingya, oriya, brahmi</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: modi, thaana, kharoshthi, dogra, yi, hanunoo, tai-tham, pahawh-hmong, avestan, balinese, khudawadi, tagalog, javanese, khmer, siddham, sinhala, meetei-mayek, tirhuta, syriac, warang-citi, syloti-nagri, buginese, bengali, duployan, batak, new-tai-lue, myanmar, mandaic, gunjala-gondi, tifinagh, limbu, gujarati, tamil, devanagari, rejang, kannada, sharada, buhid, newa, kaithi, mongolian, arabic, mahajani, tai-viet, takri, gurmukhi, kayah-li, sundanese, old-hungarian, saurashtra, psalter-pahlavi, sogdian, khojki, tagbanwa, grantha, lepcha, malayalam, lao, telugu, bhaiksuki, nko, manichaean, tibetan, chakma, hebrew, masaram-gondi, thai, cham, zanabazar-square, tai-le, phags-pa, hanifi-rohingya, oriya, brahmi</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, nko, arabic, hebrew, phags-pa, syriac</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, nko, hebrew, phags-pa, syriac</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: yi, syloti-nagri, arabic</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: old-hungarian, meroitic</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+2219 BULLET OPERATOR: try adding one of: yi, tai-tham, math, symbols</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+2241 NOT TILDE: try adding math</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+263D FIRST QUARTER MOON: try adding symbols</li>
<li>U+263E LAST QUARTER MOON: try adding symbols</li>
<li>U+271A HEAVY GREEK CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2734 EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+29DF DOUBLE-ENDED MULTIMAP: try adding math</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E43 DASH WITH LEFT UPTURN: try adding glagolitic</li>
<li>U+2E45 INVERTED LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E46 INVERTED LOW KAVYKA WITH KAVYKA ABOVE: not included in any glyphset definition</li>
<li>U+2E47 LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E48 LOW KAVYKA WITH DOT: not included in any glyphset definition</li>
<li>U+2E49 DOUBLE STACKED COMMA: not included in any glyphset definition</li>
<li>U+E000 : not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E0EC : not included in any glyphset definition</li>
<li>U+E2EA : not included in any glyphset definition</li>
<li>U+E5D0 : not included in any glyphset definition</li>
<li>U+E5D1 : not included in any glyphset definition</li>
<li>U+E5D2 : not included in any glyphset definition</li>
<li>U+E5D3 : not included in any glyphset definition</li>
<li>U+E5D4 : not included in any glyphset definition</li>
<li>U+E5D5 : not included in any glyphset definition</li>
<li>U+E5D6 : not included in any glyphset definition</li>
<li>U+E5D7 : not included in any glyphset definition</li>
<li>U+E8E1 : not included in any glyphset definition</li>
<li>U+E8E3 : not included in any glyphset definition</li>
<li>U+E8E5 : not included in any glyphset definition</li>
<li>U+E901 : not included in any glyphset definition</li>
<li>U+E903 : not included in any glyphset definition</li>
<li>U+E904 : not included in any glyphset definition</li>
<li>U+E907 : not included in any glyphset definition</li>
<li>U+E909 : not included in any glyphset definition</li>
<li>U+E925 : not included in any glyphset definition</li>
<li>U+E926 : not included in any glyphset definition</li>
<li>U+E92A : not included in any glyphset definition</li>
<li>U+E92B : not included in any glyphset definition</li>
<li>U+F4E0 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E6 : not included in any glyphset definition</li>
<li>U+F4E7 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EB : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4EE : not included in any glyphset definition</li>
<li>U+F4F0 : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+F4F2 : not included in any glyphset definition</li>
<li>U+F4F3 : not included in any glyphset definition</li>
<li>U+F4FD : not included in any glyphset definition</li>
<li>U+1F311 NEW MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F312 WAXING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F313 FIRST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F314 WAXING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F315 FULL MOON SYMBOL: try adding symbols</li>
<li>U+1F316 WANING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F317 LAST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F318 WANING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F319 CRESCENT MOON: not included in any glyphset definition</li>
<li>U+1F347 GRAPES: not included in any glyphset definition</li>
<li>U+1F377 WINE GLASS: not included in any glyphset definition</li>
<li>U+1F41F FISH: try adding symbols</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 15 | 119 | 7 | 108 | 0 | 
| 0% | 0% | 1% | 6% | 47% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
