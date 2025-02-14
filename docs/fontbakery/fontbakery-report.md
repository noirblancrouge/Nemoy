## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[15] Nemoy[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* 🔥 **FAIL** <p>'Light' instance has the same coordinates as the default instance; its postscript name should be 'Nemoy-VF', instead of 'Nemoy-Light'.</p>
 [code: invalid-default-instance-postscript-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking if OS/2 usWeightClass matches fvar. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-weight-class-fvar">opentype/weight_class_fvar</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 usWeightClass is '400', but should match fvar default value '300.0'.</p>
 [code: bad-weight-class]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, Ɔ, ɔ, Ɛ</td>
<td align="left">bm_Latn (Bambara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɔ, Ɔ, Ɛ, ɛ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɔ, ɛ, Ɔ, Ɛ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɓ, ƴ, ɗ, Ƴ, ɓ, Ɗ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɗ, ƙ, Ƴ, Ƙ, ƴ, ɓ, Ɓ, ɗ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɛ, ɛ, ɔ, Ɔ</td>
<td align="left">tw_akuapem_Latn (Akuapem Twi)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɵ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɵ</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Nemoy Light</td>
<td align="left">Nemoy Light</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Nemoy Light</td>
<td align="left">Nemoy Light</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>Nemoy-VF</strong></td>
<td align="left"><strong>Nemoy-Light</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Nemoy</td>
<td align="left">Nemoy</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">Light</td>
<td align="left">Light</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-weightclass">googlefonts/weightclass</a></summary>
    <div>







* 🔥 **FAIL** <p>Best SubFamily name is 'Light'. Expected OS/2 usWeightClass is 300, got 400.</p>
 [code: bad-value]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 27 in glyph 'uni02BD' has a kink between location wght=300 and location wght=900

- Contour 1 point 36 in glyph 'three' has a kink between location wght=300 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* Aacute (U+00C1): B&lt;&lt;439.0,721.0&gt;-&lt;439.0,716.0&gt;-&lt;435.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Aacute (U+00C1): B&lt;&lt;435.0,712.5&gt;-&lt;431.0,709.0&gt;-&lt;426.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Aacute (U+00C1): B&lt;&lt;253.5,712.5&gt;-&lt;250.0,716.0&gt;-&lt;250.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EAE (U+1EAE): B&lt;&lt;439.0,894.0&gt;-&lt;439.0,889.0&gt;-&lt;435.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EAE (U+1EAE): B&lt;&lt;435.0,885.5&gt;-&lt;431.0,882.0&gt;-&lt;426.0,882.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EAE (U+1EAE): B&lt;&lt;253.5,885.5&gt;-&lt;250.0,889.0&gt;-&lt;250.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EB0 (U+1EB0): B&lt;&lt;481.0,894.0&gt;-&lt;481.0,889.0&gt;-&lt;477.5,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EB0 (U+1EB0): B&lt;&lt;305.0,882.0&gt;-&lt;300.0,882.0&gt;-&lt;296.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EB0 (U+1EB0): B&lt;&lt;296.0,885.5&gt;-&lt;292.0,889.0&gt;-&lt;292.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EA4 (U+1EA4): B&lt;&lt;602.0,839.0&gt;-&lt;602.0,834.0&gt;-&lt;598.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EA4 (U+1EA4): B&lt;&lt;598.0,830.5&gt;-&lt;594.0,827.0&gt;-&lt;589.0,827.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EA4 (U+1EA4): B&lt;&lt;416.5,830.5&gt;-&lt;413.0,834.0&gt;-&lt;413.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EA6 (U+1EA6): B&lt;&lt;298.0,839.0&gt;-&lt;298.0,834.0&gt;-&lt;294.5,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EA6 (U+1EA6): B&lt;&lt;122.0,827.0&gt;-&lt;117.0,827.0&gt;-&lt;113.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EA6 (U+1EA6): B&lt;&lt;113.0,830.5&gt;-&lt;109.0,834.0&gt;-&lt;109.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni0200 (U+0200): B&lt;&lt;340.0,721.0&gt;-&lt;340.0,716.0&gt;-&lt;336.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0200 (U+0200): B&lt;&lt;164.0,709.0&gt;-&lt;159.0,709.0&gt;-&lt;155.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0200 (U+0200): B&lt;&lt;155.0,712.5&gt;-&lt;151.0,716.0&gt;-&lt;151.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0200 (U+0200): B&lt;&lt;406.0,709.0&gt;-&lt;401.0,709.0&gt;-&lt;397.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0200 (U+0200): B&lt;&lt;397.0,712.5&gt;-&lt;393.0,716.0&gt;-&lt;393.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Agrave (U+00C0): B&lt;&lt;481.0,721.0&gt;-&lt;481.0,716.0&gt;-&lt;477.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Agrave (U+00C0): B&lt;&lt;305.0,709.0&gt;-&lt;300.0,709.0&gt;-&lt;296.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Agrave (U+00C0): B&lt;&lt;296.0,712.5&gt;-&lt;292.0,716.0&gt;-&lt;292.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Aringacute (U+01FA): B&lt;&lt;439.0,835.0&gt;-&lt;439.0,830.0&gt;-&lt;435.0,826.5&gt;&gt; has the same coordinates as a previous segment.

* Aringacute (U+01FA): B&lt;&lt;435.0,826.5&gt;-&lt;431.0,823.0&gt;-&lt;426.0,823.0&gt;&gt; has the same coordinates as a previous segment.

* Aringacute (U+01FA): B&lt;&lt;253.5,826.5&gt;-&lt;250.0,830.0&gt;-&lt;250.0,835.0&gt;&gt; has the same coordinates as a previous segment.

* AEacute (U+01FC): B&lt;&lt;961.0,721.0&gt;-&lt;961.0,716.0&gt;-&lt;957.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* AEacute (U+01FC): B&lt;&lt;957.0,712.5&gt;-&lt;953.0,709.0&gt;-&lt;948.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* AEacute (U+01FC): B&lt;&lt;775.5,712.5&gt;-&lt;772.0,716.0&gt;-&lt;772.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Cacute (U+0106): B&lt;&lt;459.0,723.0&gt;-&lt;459.0,718.0&gt;-&lt;455.0,714.5&gt;&gt; has the same coordinates as a previous segment.

* Cacute (U+0106): B&lt;&lt;455.0,714.5&gt;-&lt;451.0,711.0&gt;-&lt;446.0,711.0&gt;&gt; has the same coordinates as a previous segment.

* Cacute (U+0106): B&lt;&lt;273.5,714.5&gt;-&lt;270.0,718.0&gt;-&lt;270.0,723.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E08 (U+1E08): B&lt;&lt;459.0,723.0&gt;-&lt;459.0,718.0&gt;-&lt;455.0,714.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E08 (U+1E08): B&lt;&lt;455.0,714.5&gt;-&lt;451.0,711.0&gt;-&lt;446.0,711.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E08 (U+1E08): B&lt;&lt;273.5,714.5&gt;-&lt;270.0,718.0&gt;-&lt;270.0,723.0&gt;&gt; has the same coordinates as a previous segment.

* Eacute (U+00C9): B&lt;&lt;357.0,721.0&gt;-&lt;357.0,716.0&gt;-&lt;353.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Eacute (U+00C9): B&lt;&lt;353.0,712.5&gt;-&lt;349.0,709.0&gt;-&lt;344.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Eacute (U+00C9): B&lt;&lt;171.5,712.5&gt;-&lt;168.0,716.0&gt;-&lt;168.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EBE (U+1EBE): B&lt;&lt;520.0,839.0&gt;-&lt;520.0,834.0&gt;-&lt;516.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EBE (U+1EBE): B&lt;&lt;516.0,830.5&gt;-&lt;512.0,827.0&gt;-&lt;507.0,827.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EBE (U+1EBE): B&lt;&lt;334.5,830.5&gt;-&lt;331.0,834.0&gt;-&lt;331.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EC0 (U+1EC0): B&lt;&lt;216.0,839.0&gt;-&lt;216.0,834.0&gt;-&lt;212.5,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EC0 (U+1EC0): B&lt;&lt;40.0,827.0&gt;-&lt;35.0,827.0&gt;-&lt;31.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EC0 (U+1EC0): B&lt;&lt;31.0,830.5&gt;-&lt;27.0,834.0&gt;-&lt;27.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni0204 (U+0204): B&lt;&lt;258.0,721.0&gt;-&lt;258.0,716.0&gt;-&lt;254.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0204 (U+0204): B&lt;&lt;82.0,709.0&gt;-&lt;77.0,709.0&gt;-&lt;73.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0204 (U+0204): B&lt;&lt;73.0,712.5&gt;-&lt;69.0,716.0&gt;-&lt;69.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0204 (U+0204): B&lt;&lt;324.0,709.0&gt;-&lt;319.0,709.0&gt;-&lt;315.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0204 (U+0204): B&lt;&lt;315.0,712.5&gt;-&lt;311.0,716.0&gt;-&lt;311.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Egrave (U+00C8): B&lt;&lt;399.0,721.0&gt;-&lt;399.0,716.0&gt;-&lt;395.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Egrave (U+00C8): B&lt;&lt;223.0,709.0&gt;-&lt;218.0,709.0&gt;-&lt;214.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Egrave (U+00C8): B&lt;&lt;214.0,712.5&gt;-&lt;210.0,716.0&gt;-&lt;210.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E16 (U+1E16): B&lt;&lt;357.0,894.0&gt;-&lt;357.0,889.0&gt;-&lt;353.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E16 (U+1E16): B&lt;&lt;353.0,885.5&gt;-&lt;349.0,882.0&gt;-&lt;344.0,882.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E16 (U+1E16): B&lt;&lt;171.5,885.5&gt;-&lt;168.0,889.0&gt;-&lt;168.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E14 (U+1E14): B&lt;&lt;399.0,894.0&gt;-&lt;399.0,889.0&gt;-&lt;395.5,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E14 (U+1E14): B&lt;&lt;223.0,882.0&gt;-&lt;218.0,882.0&gt;-&lt;214.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E14 (U+1E14): B&lt;&lt;214.0,885.5&gt;-&lt;210.0,889.0&gt;-&lt;210.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* Iacute (U+00CD): B&lt;&lt;251.0,721.0&gt;-&lt;251.0,716.0&gt;-&lt;247.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Iacute (U+00CD): B&lt;&lt;247.0,712.5&gt;-&lt;243.0,709.0&gt;-&lt;238.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Iacute (U+00CD): B&lt;&lt;65.5,712.5&gt;-&lt;62.0,716.0&gt;-&lt;62.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0208 (U+0208): B&lt;&lt;152.0,721.0&gt;-&lt;152.0,716.0&gt;-&lt;148.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0208 (U+0208): B&lt;&lt;-24.0,709.0&gt;-&lt;-29.0,709.0&gt;-&lt;-33.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0208 (U+0208): B&lt;&lt;-33.0,712.5&gt;-&lt;-37.0,716.0&gt;-&lt;-37.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0208 (U+0208): B&lt;&lt;218.0,709.0&gt;-&lt;213.0,709.0&gt;-&lt;209.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0208 (U+0208): B&lt;&lt;209.0,712.5&gt;-&lt;205.0,716.0&gt;-&lt;205.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E2E (U+1E2E): B&lt;&lt;251.0,870.0&gt;-&lt;251.0,865.0&gt;-&lt;247.0,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E2E (U+1E2E): B&lt;&lt;247.0,861.5&gt;-&lt;243.0,858.0&gt;-&lt;238.0,858.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E2E (U+1E2E): B&lt;&lt;65.5,861.5&gt;-&lt;62.0,865.0&gt;-&lt;62.0,870.0&gt;&gt; has the same coordinates as a previous segment.

* Igrave (U+00CC): B&lt;&lt;293.0,721.0&gt;-&lt;293.0,716.0&gt;-&lt;289.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Igrave (U+00CC): B&lt;&lt;117.0,709.0&gt;-&lt;112.0,709.0&gt;-&lt;108.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Igrave (U+00CC): B&lt;&lt;108.0,712.5&gt;-&lt;104.0,716.0&gt;-&lt;104.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni004A0301: B&lt;&lt;313.0,721.0&gt;-&lt;313.0,716.0&gt;-&lt;309.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni004A0301: B&lt;&lt;309.0,712.5&gt;-&lt;305.0,709.0&gt;-&lt;300.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni004A0301: B&lt;&lt;127.5,712.5&gt;-&lt;124.0,716.0&gt;-&lt;124.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Lacute (U+0139): B&lt;&lt;295.0,721.0&gt;-&lt;295.0,716.0&gt;-&lt;291.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Lacute (U+0139): B&lt;&lt;291.0,712.5&gt;-&lt;287.0,709.0&gt;-&lt;282.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Lacute (U+0139): B&lt;&lt;109.5,712.5&gt;-&lt;106.0,716.0&gt;-&lt;106.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;371.0,721.0&gt;-&lt;371.0,716.0&gt;-&lt;367.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;367.0,712.5&gt;-&lt;363.0,709.0&gt;-&lt;358.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;185.5,712.5&gt;-&lt;182.0,716.0&gt;-&lt;182.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Oacute (U+00D3): B&lt;&lt;459.0,721.0&gt;-&lt;459.0,716.0&gt;-&lt;455.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Oacute (U+00D3): B&lt;&lt;455.0,712.5&gt;-&lt;451.0,709.0&gt;-&lt;446.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Oacute (U+00D3): B&lt;&lt;273.5,712.5&gt;-&lt;270.0,716.0&gt;-&lt;270.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1ED0 (U+1ED0): B&lt;&lt;622.0,839.0&gt;-&lt;622.0,834.0&gt;-&lt;618.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1ED0 (U+1ED0): B&lt;&lt;618.0,830.5&gt;-&lt;614.0,827.0&gt;-&lt;609.0,827.0&gt;&gt; has the same coordinates as a previous segment.

* uni1ED0 (U+1ED0): B&lt;&lt;436.5,830.5&gt;-&lt;433.0,834.0&gt;-&lt;433.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni1ED2 (U+1ED2): B&lt;&lt;318.0,839.0&gt;-&lt;318.0,834.0&gt;-&lt;314.5,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1ED2 (U+1ED2): B&lt;&lt;142.0,827.0&gt;-&lt;137.0,827.0&gt;-&lt;133.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1ED2 (U+1ED2): B&lt;&lt;133.0,830.5&gt;-&lt;129.0,834.0&gt;-&lt;129.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni020C (U+020C): B&lt;&lt;360.0,721.0&gt;-&lt;360.0,716.0&gt;-&lt;356.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni020C (U+020C): B&lt;&lt;184.0,709.0&gt;-&lt;179.0,709.0&gt;-&lt;175.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni020C (U+020C): B&lt;&lt;175.0,712.5&gt;-&lt;171.0,716.0&gt;-&lt;171.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni020C (U+020C): B&lt;&lt;426.0,709.0&gt;-&lt;421.0,709.0&gt;-&lt;417.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni020C (U+020C): B&lt;&lt;417.0,712.5&gt;-&lt;413.0,716.0&gt;-&lt;413.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Ograve (U+00D2): B&lt;&lt;501.0,721.0&gt;-&lt;501.0,716.0&gt;-&lt;497.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Ograve (U+00D2): B&lt;&lt;325.0,709.0&gt;-&lt;320.0,709.0&gt;-&lt;316.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Ograve (U+00D2): B&lt;&lt;316.0,712.5&gt;-&lt;312.0,716.0&gt;-&lt;312.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EDA (U+1EDA): B&lt;&lt;459.0,721.0&gt;-&lt;459.0,716.0&gt;-&lt;455.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EDA (U+1EDA): B&lt;&lt;455.0,712.5&gt;-&lt;451.0,709.0&gt;-&lt;446.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EDA (U+1EDA): B&lt;&lt;273.5,712.5&gt;-&lt;270.0,716.0&gt;-&lt;270.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EDC (U+1EDC): B&lt;&lt;501.0,721.0&gt;-&lt;501.0,716.0&gt;-&lt;497.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EDC (U+1EDC): B&lt;&lt;325.0,709.0&gt;-&lt;320.0,709.0&gt;-&lt;316.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EDC (U+1EDC): B&lt;&lt;316.0,712.5&gt;-&lt;312.0,716.0&gt;-&lt;312.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E52 (U+1E52): B&lt;&lt;459.0,894.0&gt;-&lt;459.0,889.0&gt;-&lt;455.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E52 (U+1E52): B&lt;&lt;455.0,885.5&gt;-&lt;451.0,882.0&gt;-&lt;446.0,882.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E52 (U+1E52): B&lt;&lt;273.5,885.5&gt;-&lt;270.0,889.0&gt;-&lt;270.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E50 (U+1E50): B&lt;&lt;501.0,894.0&gt;-&lt;501.0,889.0&gt;-&lt;497.5,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E50 (U+1E50): B&lt;&lt;325.0,882.0&gt;-&lt;320.0,882.0&gt;-&lt;316.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E50 (U+1E50): B&lt;&lt;316.0,885.5&gt;-&lt;312.0,889.0&gt;-&lt;312.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* Oslashacute (U+01FE): B&lt;&lt;459.0,721.0&gt;-&lt;459.0,716.0&gt;-&lt;455.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Oslashacute (U+01FE): B&lt;&lt;455.0,712.5&gt;-&lt;451.0,709.0&gt;-&lt;446.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Oslashacute (U+01FE): B&lt;&lt;273.5,712.5&gt;-&lt;270.0,716.0&gt;-&lt;270.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E4C (U+1E4C): B&lt;&lt;459.0,907.0&gt;-&lt;459.0,902.0&gt;-&lt;455.0,898.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E4C (U+1E4C): B&lt;&lt;455.0,898.5&gt;-&lt;451.0,895.0&gt;-&lt;446.0,895.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E4C (U+1E4C): B&lt;&lt;273.5,898.5&gt;-&lt;270.0,902.0&gt;-&lt;270.0,907.0&gt;&gt; has the same coordinates as a previous segment.

* Racute (U+0154): B&lt;&lt;301.0,721.0&gt;-&lt;301.0,716.0&gt;-&lt;297.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Racute (U+0154): B&lt;&lt;297.0,712.5&gt;-&lt;293.0,709.0&gt;-&lt;288.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Racute (U+0154): B&lt;&lt;115.5,712.5&gt;-&lt;112.0,716.0&gt;-&lt;112.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0210 (U+0210): B&lt;&lt;202.0,721.0&gt;-&lt;202.0,716.0&gt;-&lt;198.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0210 (U+0210): B&lt;&lt;26.0,709.0&gt;-&lt;21.0,709.0&gt;-&lt;17.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0210 (U+0210): B&lt;&lt;17.0,712.5&gt;-&lt;13.0,716.0&gt;-&lt;13.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0210 (U+0210): B&lt;&lt;268.0,709.0&gt;-&lt;263.0,709.0&gt;-&lt;259.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0210 (U+0210): B&lt;&lt;259.0,712.5&gt;-&lt;255.0,716.0&gt;-&lt;255.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Sacute (U+015A): B&lt;&lt;340.0,721.0&gt;-&lt;340.0,716.0&gt;-&lt;336.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Sacute (U+015A): B&lt;&lt;336.0,712.5&gt;-&lt;332.0,709.0&gt;-&lt;327.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Sacute (U+015A): B&lt;&lt;154.5,712.5&gt;-&lt;151.0,716.0&gt;-&lt;151.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E64 (U+1E64): B&lt;&lt;469.0,721.0&gt;-&lt;469.0,716.0&gt;-&lt;465.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E64 (U+1E64): B&lt;&lt;465.0,712.5&gt;-&lt;461.0,709.0&gt;-&lt;456.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E64 (U+1E64): B&lt;&lt;283.5,712.5&gt;-&lt;280.0,716.0&gt;-&lt;280.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Uacute (U+00DA): B&lt;&lt;367.0,721.0&gt;-&lt;367.0,716.0&gt;-&lt;363.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Uacute (U+00DA): B&lt;&lt;363.0,712.5&gt;-&lt;359.0,709.0&gt;-&lt;354.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Uacute (U+00DA): B&lt;&lt;181.5,712.5&gt;-&lt;178.0,716.0&gt;-&lt;178.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0214 (U+0214): B&lt;&lt;268.0,721.0&gt;-&lt;268.0,716.0&gt;-&lt;264.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0214 (U+0214): B&lt;&lt;92.0,709.0&gt;-&lt;87.0,709.0&gt;-&lt;83.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0214 (U+0214): B&lt;&lt;83.0,712.5&gt;-&lt;79.0,716.0&gt;-&lt;79.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0214 (U+0214): B&lt;&lt;334.0,709.0&gt;-&lt;329.0,709.0&gt;-&lt;325.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0214 (U+0214): B&lt;&lt;325.0,712.5&gt;-&lt;321.0,716.0&gt;-&lt;321.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni01D7 (U+01D7): B&lt;&lt;367.0,870.0&gt;-&lt;367.0,865.0&gt;-&lt;363.0,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni01D7 (U+01D7): B&lt;&lt;363.0,861.5&gt;-&lt;359.0,858.0&gt;-&lt;354.0,858.0&gt;&gt; has the same coordinates as a previous segment.

* uni01D7 (U+01D7): B&lt;&lt;181.5,861.5&gt;-&lt;178.0,865.0&gt;-&lt;178.0,870.0&gt;&gt; has the same coordinates as a previous segment.

* uni01DB (U+01DB): B&lt;&lt;409.0,870.0&gt;-&lt;409.0,865.0&gt;-&lt;405.5,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni01DB (U+01DB): B&lt;&lt;233.0,858.0&gt;-&lt;228.0,858.0&gt;-&lt;224.0,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni01DB (U+01DB): B&lt;&lt;224.0,861.5&gt;-&lt;220.0,865.0&gt;-&lt;220.0,870.0&gt;&gt; has the same coordinates as a previous segment.

* Ugrave (U+00D9): B&lt;&lt;409.0,721.0&gt;-&lt;409.0,716.0&gt;-&lt;405.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Ugrave (U+00D9): B&lt;&lt;233.0,709.0&gt;-&lt;228.0,709.0&gt;-&lt;224.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Ugrave (U+00D9): B&lt;&lt;224.0,712.5&gt;-&lt;220.0,716.0&gt;-&lt;220.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EE8 (U+1EE8): B&lt;&lt;367.0,721.0&gt;-&lt;367.0,716.0&gt;-&lt;363.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EE8 (U+1EE8): B&lt;&lt;363.0,712.5&gt;-&lt;359.0,709.0&gt;-&lt;354.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EE8 (U+1EE8): B&lt;&lt;181.5,712.5&gt;-&lt;178.0,716.0&gt;-&lt;178.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EEA (U+1EEA): B&lt;&lt;409.0,721.0&gt;-&lt;409.0,716.0&gt;-&lt;405.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EEA (U+1EEA): B&lt;&lt;233.0,709.0&gt;-&lt;228.0,709.0&gt;-&lt;224.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EEA (U+1EEA): B&lt;&lt;224.0,712.5&gt;-&lt;220.0,716.0&gt;-&lt;220.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E78 (U+1E78): B&lt;&lt;367.0,907.0&gt;-&lt;367.0,902.0&gt;-&lt;363.0,898.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E78 (U+1E78): B&lt;&lt;363.0,898.5&gt;-&lt;359.0,895.0&gt;-&lt;354.0,895.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E78 (U+1E78): B&lt;&lt;181.5,898.5&gt;-&lt;178.0,902.0&gt;-&lt;178.0,907.0&gt;&gt; has the same coordinates as a previous segment.

* Wacute (U+1E82): B&lt;&lt;407.0,721.0&gt;-&lt;407.0,716.0&gt;-&lt;403.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Wacute (U+1E82): B&lt;&lt;403.0,712.5&gt;-&lt;399.0,709.0&gt;-&lt;394.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Wacute (U+1E82): B&lt;&lt;221.5,712.5&gt;-&lt;218.0,716.0&gt;-&lt;218.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Wgrave (U+1E80): B&lt;&lt;449.0,721.0&gt;-&lt;449.0,716.0&gt;-&lt;445.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Wgrave (U+1E80): B&lt;&lt;273.0,709.0&gt;-&lt;268.0,709.0&gt;-&lt;264.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Wgrave (U+1E80): B&lt;&lt;264.0,712.5&gt;-&lt;260.0,716.0&gt;-&lt;260.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Yacute (U+00DD): B&lt;&lt;398.0,721.0&gt;-&lt;398.0,716.0&gt;-&lt;394.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Yacute (U+00DD): B&lt;&lt;394.0,712.5&gt;-&lt;390.0,709.0&gt;-&lt;385.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Yacute (U+00DD): B&lt;&lt;212.5,712.5&gt;-&lt;209.0,716.0&gt;-&lt;209.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Ygrave (U+1EF2): B&lt;&lt;440.0,721.0&gt;-&lt;440.0,716.0&gt;-&lt;436.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* Ygrave (U+1EF2): B&lt;&lt;264.0,709.0&gt;-&lt;259.0,709.0&gt;-&lt;255.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Ygrave (U+1EF2): B&lt;&lt;255.0,712.5&gt;-&lt;251.0,716.0&gt;-&lt;251.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* Zacute (U+0179): B&lt;&lt;360.0,721.0&gt;-&lt;360.0,716.0&gt;-&lt;356.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* Zacute (U+0179): B&lt;&lt;356.0,712.5&gt;-&lt;352.0,709.0&gt;-&lt;347.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* Zacute (U+0179): B&lt;&lt;174.5,712.5&gt;-&lt;171.0,716.0&gt;-&lt;171.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* aacute (U+00E1): B&lt;&lt;439.0,721.0&gt;-&lt;439.0,716.0&gt;-&lt;435.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* aacute (U+00E1): B&lt;&lt;435.0,712.5&gt;-&lt;431.0,709.0&gt;-&lt;426.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* aacute (U+00E1): B&lt;&lt;253.5,712.5&gt;-&lt;250.0,716.0&gt;-&lt;250.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EAF (U+1EAF): B&lt;&lt;439.0,894.0&gt;-&lt;439.0,889.0&gt;-&lt;435.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EAF (U+1EAF): B&lt;&lt;435.0,885.5&gt;-&lt;431.0,882.0&gt;-&lt;426.0,882.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EAF (U+1EAF): B&lt;&lt;253.5,885.5&gt;-&lt;250.0,889.0&gt;-&lt;250.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EB1 (U+1EB1): B&lt;&lt;481.0,894.0&gt;-&lt;481.0,889.0&gt;-&lt;477.5,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EB1 (U+1EB1): B&lt;&lt;305.0,882.0&gt;-&lt;300.0,882.0&gt;-&lt;296.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EB1 (U+1EB1): B&lt;&lt;296.0,885.5&gt;-&lt;292.0,889.0&gt;-&lt;292.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EA5 (U+1EA5): B&lt;&lt;602.0,839.0&gt;-&lt;602.0,834.0&gt;-&lt;598.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EA5 (U+1EA5): B&lt;&lt;598.0,830.5&gt;-&lt;594.0,827.0&gt;-&lt;589.0,827.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EA5 (U+1EA5): B&lt;&lt;416.5,830.5&gt;-&lt;413.0,834.0&gt;-&lt;413.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EA7 (U+1EA7): B&lt;&lt;298.0,839.0&gt;-&lt;298.0,834.0&gt;-&lt;294.5,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EA7 (U+1EA7): B&lt;&lt;122.0,827.0&gt;-&lt;117.0,827.0&gt;-&lt;113.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EA7 (U+1EA7): B&lt;&lt;113.0,830.5&gt;-&lt;109.0,834.0&gt;-&lt;109.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni0201 (U+0201): B&lt;&lt;340.0,721.0&gt;-&lt;340.0,716.0&gt;-&lt;336.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0201 (U+0201): B&lt;&lt;164.0,709.0&gt;-&lt;159.0,709.0&gt;-&lt;155.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0201 (U+0201): B&lt;&lt;155.0,712.5&gt;-&lt;151.0,716.0&gt;-&lt;151.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0201 (U+0201): B&lt;&lt;406.0,709.0&gt;-&lt;401.0,709.0&gt;-&lt;397.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0201 (U+0201): B&lt;&lt;397.0,712.5&gt;-&lt;393.0,716.0&gt;-&lt;393.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* agrave (U+00E0): B&lt;&lt;481.0,721.0&gt;-&lt;481.0,716.0&gt;-&lt;477.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* agrave (U+00E0): B&lt;&lt;305.0,709.0&gt;-&lt;300.0,709.0&gt;-&lt;296.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* agrave (U+00E0): B&lt;&lt;296.0,712.5&gt;-&lt;292.0,716.0&gt;-&lt;292.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* aringacute (U+01FB): B&lt;&lt;439.0,913.0&gt;-&lt;439.0,908.0&gt;-&lt;435.0,904.5&gt;&gt; has the same coordinates as a previous segment.

* aringacute (U+01FB): B&lt;&lt;435.0,904.5&gt;-&lt;431.0,901.0&gt;-&lt;426.0,901.0&gt;&gt; has the same coordinates as a previous segment.

* aringacute (U+01FB): B&lt;&lt;253.5,904.5&gt;-&lt;250.0,908.0&gt;-&lt;250.0,913.0&gt;&gt; has the same coordinates as a previous segment.

* aeacute (U+01FD): B&lt;&lt;961.0,721.0&gt;-&lt;961.0,716.0&gt;-&lt;957.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* aeacute (U+01FD): B&lt;&lt;957.0,712.5&gt;-&lt;953.0,709.0&gt;-&lt;948.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* aeacute (U+01FD): B&lt;&lt;775.5,712.5&gt;-&lt;772.0,716.0&gt;-&lt;772.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* cacute (U+0107): B&lt;&lt;459.0,723.0&gt;-&lt;459.0,718.0&gt;-&lt;455.0,714.5&gt;&gt; has the same coordinates as a previous segment.

* cacute (U+0107): B&lt;&lt;455.0,714.5&gt;-&lt;451.0,711.0&gt;-&lt;446.0,711.0&gt;&gt; has the same coordinates as a previous segment.

* cacute (U+0107): B&lt;&lt;273.5,714.5&gt;-&lt;270.0,718.0&gt;-&lt;270.0,723.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E09 (U+1E09): B&lt;&lt;459.0,723.0&gt;-&lt;459.0,718.0&gt;-&lt;455.0,714.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E09 (U+1E09): B&lt;&lt;455.0,714.5&gt;-&lt;451.0,711.0&gt;-&lt;446.0,711.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E09 (U+1E09): B&lt;&lt;273.5,714.5&gt;-&lt;270.0,718.0&gt;-&lt;270.0,723.0&gt;&gt; has the same coordinates as a previous segment.

* eacute (U+00E9): B&lt;&lt;357.0,721.0&gt;-&lt;357.0,716.0&gt;-&lt;353.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* eacute (U+00E9): B&lt;&lt;353.0,712.5&gt;-&lt;349.0,709.0&gt;-&lt;344.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* eacute (U+00E9): B&lt;&lt;171.5,712.5&gt;-&lt;168.0,716.0&gt;-&lt;168.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EBF (U+1EBF): B&lt;&lt;520.0,839.0&gt;-&lt;520.0,834.0&gt;-&lt;516.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EBF (U+1EBF): B&lt;&lt;516.0,830.5&gt;-&lt;512.0,827.0&gt;-&lt;507.0,827.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EBF (U+1EBF): B&lt;&lt;334.5,830.5&gt;-&lt;331.0,834.0&gt;-&lt;331.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EC1 (U+1EC1): B&lt;&lt;216.0,839.0&gt;-&lt;216.0,834.0&gt;-&lt;212.5,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EC1 (U+1EC1): B&lt;&lt;40.0,827.0&gt;-&lt;35.0,827.0&gt;-&lt;31.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EC1 (U+1EC1): B&lt;&lt;31.0,830.5&gt;-&lt;27.0,834.0&gt;-&lt;27.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni0205 (U+0205): B&lt;&lt;258.0,721.0&gt;-&lt;258.0,716.0&gt;-&lt;254.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0205 (U+0205): B&lt;&lt;82.0,709.0&gt;-&lt;77.0,709.0&gt;-&lt;73.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0205 (U+0205): B&lt;&lt;73.0,712.5&gt;-&lt;69.0,716.0&gt;-&lt;69.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0205 (U+0205): B&lt;&lt;324.0,709.0&gt;-&lt;319.0,709.0&gt;-&lt;315.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0205 (U+0205): B&lt;&lt;315.0,712.5&gt;-&lt;311.0,716.0&gt;-&lt;311.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* egrave (U+00E8): B&lt;&lt;399.0,721.0&gt;-&lt;399.0,716.0&gt;-&lt;395.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* egrave (U+00E8): B&lt;&lt;223.0,709.0&gt;-&lt;218.0,709.0&gt;-&lt;214.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* egrave (U+00E8): B&lt;&lt;214.0,712.5&gt;-&lt;210.0,716.0&gt;-&lt;210.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E17 (U+1E17): B&lt;&lt;357.0,894.0&gt;-&lt;357.0,889.0&gt;-&lt;353.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E17 (U+1E17): B&lt;&lt;353.0,885.5&gt;-&lt;349.0,882.0&gt;-&lt;344.0,882.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E17 (U+1E17): B&lt;&lt;171.5,885.5&gt;-&lt;168.0,889.0&gt;-&lt;168.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E15 (U+1E15): B&lt;&lt;399.0,894.0&gt;-&lt;399.0,889.0&gt;-&lt;395.5,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E15 (U+1E15): B&lt;&lt;223.0,882.0&gt;-&lt;218.0,882.0&gt;-&lt;214.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E15 (U+1E15): B&lt;&lt;214.0,885.5&gt;-&lt;210.0,889.0&gt;-&lt;210.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* iacute (U+00ED): B&lt;&lt;251.0,721.0&gt;-&lt;251.0,716.0&gt;-&lt;247.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* iacute (U+00ED): B&lt;&lt;247.0,712.5&gt;-&lt;243.0,709.0&gt;-&lt;238.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* iacute (U+00ED): B&lt;&lt;65.5,712.5&gt;-&lt;62.0,716.0&gt;-&lt;62.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0209 (U+0209): B&lt;&lt;152.0,721.0&gt;-&lt;152.0,716.0&gt;-&lt;148.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0209 (U+0209): B&lt;&lt;-24.0,709.0&gt;-&lt;-29.0,709.0&gt;-&lt;-33.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0209 (U+0209): B&lt;&lt;-33.0,712.5&gt;-&lt;-37.0,716.0&gt;-&lt;-37.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0209 (U+0209): B&lt;&lt;218.0,709.0&gt;-&lt;213.0,709.0&gt;-&lt;209.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0209 (U+0209): B&lt;&lt;209.0,712.5&gt;-&lt;205.0,716.0&gt;-&lt;205.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E2F (U+1E2F): B&lt;&lt;251.0,870.0&gt;-&lt;251.0,865.0&gt;-&lt;247.0,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E2F (U+1E2F): B&lt;&lt;247.0,861.5&gt;-&lt;243.0,858.0&gt;-&lt;238.0,858.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E2F (U+1E2F): B&lt;&lt;65.5,861.5&gt;-&lt;62.0,865.0&gt;-&lt;62.0,870.0&gt;&gt; has the same coordinates as a previous segment.

* igrave (U+00EC): B&lt;&lt;293.0,721.0&gt;-&lt;293.0,716.0&gt;-&lt;289.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* igrave (U+00EC): B&lt;&lt;117.0,709.0&gt;-&lt;112.0,709.0&gt;-&lt;108.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* igrave (U+00EC): B&lt;&lt;108.0,712.5&gt;-&lt;104.0,716.0&gt;-&lt;104.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni006A0301: B&lt;&lt;313.0,721.0&gt;-&lt;313.0,716.0&gt;-&lt;309.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni006A0301: B&lt;&lt;309.0,712.5&gt;-&lt;305.0,709.0&gt;-&lt;300.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni006A0301: B&lt;&lt;127.5,712.5&gt;-&lt;124.0,716.0&gt;-&lt;124.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* lacute (U+013A): B&lt;&lt;295.0,721.0&gt;-&lt;295.0,716.0&gt;-&lt;291.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* lacute (U+013A): B&lt;&lt;291.0,712.5&gt;-&lt;287.0,709.0&gt;-&lt;282.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* lacute (U+013A): B&lt;&lt;109.5,712.5&gt;-&lt;106.0,716.0&gt;-&lt;106.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* nacute (U+0144): B&lt;&lt;371.0,721.0&gt;-&lt;371.0,716.0&gt;-&lt;367.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* nacute (U+0144): B&lt;&lt;367.0,712.5&gt;-&lt;363.0,709.0&gt;-&lt;358.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* nacute (U+0144): B&lt;&lt;185.5,712.5&gt;-&lt;182.0,716.0&gt;-&lt;182.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* oacute (U+00F3): B&lt;&lt;459.0,721.0&gt;-&lt;459.0,716.0&gt;-&lt;455.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* oacute (U+00F3): B&lt;&lt;455.0,712.5&gt;-&lt;451.0,709.0&gt;-&lt;446.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* oacute (U+00F3): B&lt;&lt;273.5,712.5&gt;-&lt;270.0,716.0&gt;-&lt;270.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1ED1 (U+1ED1): B&lt;&lt;622.0,839.0&gt;-&lt;622.0,834.0&gt;-&lt;618.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1ED1 (U+1ED1): B&lt;&lt;618.0,830.5&gt;-&lt;614.0,827.0&gt;-&lt;609.0,827.0&gt;&gt; has the same coordinates as a previous segment.

* uni1ED1 (U+1ED1): B&lt;&lt;436.5,830.5&gt;-&lt;433.0,834.0&gt;-&lt;433.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni1ED3 (U+1ED3): B&lt;&lt;318.0,839.0&gt;-&lt;318.0,834.0&gt;-&lt;314.5,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1ED3 (U+1ED3): B&lt;&lt;142.0,827.0&gt;-&lt;137.0,827.0&gt;-&lt;133.0,830.5&gt;&gt; has the same coordinates as a previous segment.

* uni1ED3 (U+1ED3): B&lt;&lt;133.0,830.5&gt;-&lt;129.0,834.0&gt;-&lt;129.0,839.0&gt;&gt; has the same coordinates as a previous segment.

* uni020D (U+020D): B&lt;&lt;360.0,721.0&gt;-&lt;360.0,716.0&gt;-&lt;356.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni020D (U+020D): B&lt;&lt;184.0,709.0&gt;-&lt;179.0,709.0&gt;-&lt;175.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni020D (U+020D): B&lt;&lt;175.0,712.5&gt;-&lt;171.0,716.0&gt;-&lt;171.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni020D (U+020D): B&lt;&lt;426.0,709.0&gt;-&lt;421.0,709.0&gt;-&lt;417.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni020D (U+020D): B&lt;&lt;417.0,712.5&gt;-&lt;413.0,716.0&gt;-&lt;413.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* ograve (U+00F2): B&lt;&lt;501.0,721.0&gt;-&lt;501.0,716.0&gt;-&lt;497.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* ograve (U+00F2): B&lt;&lt;325.0,709.0&gt;-&lt;320.0,709.0&gt;-&lt;316.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* ograve (U+00F2): B&lt;&lt;316.0,712.5&gt;-&lt;312.0,716.0&gt;-&lt;312.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EDB (U+1EDB): B&lt;&lt;459.0,721.0&gt;-&lt;459.0,716.0&gt;-&lt;455.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EDB (U+1EDB): B&lt;&lt;455.0,712.5&gt;-&lt;451.0,709.0&gt;-&lt;446.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EDB (U+1EDB): B&lt;&lt;273.5,712.5&gt;-&lt;270.0,716.0&gt;-&lt;270.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EDD (U+1EDD): B&lt;&lt;501.0,721.0&gt;-&lt;501.0,716.0&gt;-&lt;497.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EDD (U+1EDD): B&lt;&lt;325.0,709.0&gt;-&lt;320.0,709.0&gt;-&lt;316.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EDD (U+1EDD): B&lt;&lt;316.0,712.5&gt;-&lt;312.0,716.0&gt;-&lt;312.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E53 (U+1E53): B&lt;&lt;459.0,894.0&gt;-&lt;459.0,889.0&gt;-&lt;455.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E53 (U+1E53): B&lt;&lt;455.0,885.5&gt;-&lt;451.0,882.0&gt;-&lt;446.0,882.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E53 (U+1E53): B&lt;&lt;273.5,885.5&gt;-&lt;270.0,889.0&gt;-&lt;270.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E51 (U+1E51): B&lt;&lt;501.0,894.0&gt;-&lt;501.0,889.0&gt;-&lt;497.5,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E51 (U+1E51): B&lt;&lt;325.0,882.0&gt;-&lt;320.0,882.0&gt;-&lt;316.0,885.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E51 (U+1E51): B&lt;&lt;316.0,885.5&gt;-&lt;312.0,889.0&gt;-&lt;312.0,894.0&gt;&gt; has the same coordinates as a previous segment.

* oslashacute (U+01FF): B&lt;&lt;459.0,721.0&gt;-&lt;459.0,716.0&gt;-&lt;455.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* oslashacute (U+01FF): B&lt;&lt;455.0,712.5&gt;-&lt;451.0,709.0&gt;-&lt;446.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* oslashacute (U+01FF): B&lt;&lt;273.5,712.5&gt;-&lt;270.0,716.0&gt;-&lt;270.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E4D (U+1E4D): B&lt;&lt;459.0,907.0&gt;-&lt;459.0,902.0&gt;-&lt;455.0,898.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E4D (U+1E4D): B&lt;&lt;455.0,898.5&gt;-&lt;451.0,895.0&gt;-&lt;446.0,895.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E4D (U+1E4D): B&lt;&lt;273.5,898.5&gt;-&lt;270.0,902.0&gt;-&lt;270.0,907.0&gt;&gt; has the same coordinates as a previous segment.

* racute (U+0155): B&lt;&lt;301.0,721.0&gt;-&lt;301.0,716.0&gt;-&lt;297.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* racute (U+0155): B&lt;&lt;297.0,712.5&gt;-&lt;293.0,709.0&gt;-&lt;288.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* racute (U+0155): B&lt;&lt;115.5,712.5&gt;-&lt;112.0,716.0&gt;-&lt;112.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0211 (U+0211): B&lt;&lt;198.0,721.0&gt;-&lt;198.0,716.0&gt;-&lt;194.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0211 (U+0211): B&lt;&lt;22.0,709.0&gt;-&lt;17.0,709.0&gt;-&lt;13.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0211 (U+0211): B&lt;&lt;13.0,712.5&gt;-&lt;9.0,716.0&gt;-&lt;9.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0211 (U+0211): B&lt;&lt;264.0,709.0&gt;-&lt;259.0,709.0&gt;-&lt;255.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0211 (U+0211): B&lt;&lt;255.0,712.5&gt;-&lt;251.0,716.0&gt;-&lt;251.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* sacute (U+015B): B&lt;&lt;340.0,721.0&gt;-&lt;340.0,716.0&gt;-&lt;336.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* sacute (U+015B): B&lt;&lt;336.0,712.5&gt;-&lt;332.0,709.0&gt;-&lt;327.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* sacute (U+015B): B&lt;&lt;154.5,712.5&gt;-&lt;151.0,716.0&gt;-&lt;151.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E65 (U+1E65): B&lt;&lt;469.0,721.0&gt;-&lt;469.0,716.0&gt;-&lt;465.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E65 (U+1E65): B&lt;&lt;465.0,712.5&gt;-&lt;461.0,709.0&gt;-&lt;456.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E65 (U+1E65): B&lt;&lt;283.5,712.5&gt;-&lt;280.0,716.0&gt;-&lt;280.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uacute (U+00FA): B&lt;&lt;367.0,721.0&gt;-&lt;367.0,716.0&gt;-&lt;363.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uacute (U+00FA): B&lt;&lt;363.0,712.5&gt;-&lt;359.0,709.0&gt;-&lt;354.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uacute (U+00FA): B&lt;&lt;181.5,712.5&gt;-&lt;178.0,716.0&gt;-&lt;178.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0215 (U+0215): B&lt;&lt;268.0,721.0&gt;-&lt;268.0,716.0&gt;-&lt;264.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0215 (U+0215): B&lt;&lt;92.0,709.0&gt;-&lt;87.0,709.0&gt;-&lt;83.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0215 (U+0215): B&lt;&lt;83.0,712.5&gt;-&lt;79.0,716.0&gt;-&lt;79.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni0215 (U+0215): B&lt;&lt;334.0,709.0&gt;-&lt;329.0,709.0&gt;-&lt;325.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni0215 (U+0215): B&lt;&lt;325.0,712.5&gt;-&lt;321.0,716.0&gt;-&lt;321.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni01D8 (U+01D8): B&lt;&lt;367.0,870.0&gt;-&lt;367.0,865.0&gt;-&lt;363.0,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni01D8 (U+01D8): B&lt;&lt;363.0,861.5&gt;-&lt;359.0,858.0&gt;-&lt;354.0,858.0&gt;&gt; has the same coordinates as a previous segment.

* uni01D8 (U+01D8): B&lt;&lt;181.5,861.5&gt;-&lt;178.0,865.0&gt;-&lt;178.0,870.0&gt;&gt; has the same coordinates as a previous segment.

* uni01DC (U+01DC): B&lt;&lt;409.0,870.0&gt;-&lt;409.0,865.0&gt;-&lt;405.5,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni01DC (U+01DC): B&lt;&lt;233.0,858.0&gt;-&lt;228.0,858.0&gt;-&lt;224.0,861.5&gt;&gt; has the same coordinates as a previous segment.

* uni01DC (U+01DC): B&lt;&lt;224.0,861.5&gt;-&lt;220.0,865.0&gt;-&lt;220.0,870.0&gt;&gt; has the same coordinates as a previous segment.

* ugrave (U+00F9): B&lt;&lt;409.0,721.0&gt;-&lt;409.0,716.0&gt;-&lt;405.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* ugrave (U+00F9): B&lt;&lt;233.0,709.0&gt;-&lt;228.0,709.0&gt;-&lt;224.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* ugrave (U+00F9): B&lt;&lt;224.0,712.5&gt;-&lt;220.0,716.0&gt;-&lt;220.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EE9 (U+1EE9): B&lt;&lt;367.0,721.0&gt;-&lt;367.0,716.0&gt;-&lt;363.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EE9 (U+1EE9): B&lt;&lt;363.0,712.5&gt;-&lt;359.0,709.0&gt;-&lt;354.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EE9 (U+1EE9): B&lt;&lt;181.5,712.5&gt;-&lt;178.0,716.0&gt;-&lt;178.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EEB (U+1EEB): B&lt;&lt;409.0,721.0&gt;-&lt;409.0,716.0&gt;-&lt;405.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EEB (U+1EEB): B&lt;&lt;233.0,709.0&gt;-&lt;228.0,709.0&gt;-&lt;224.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EEB (U+1EEB): B&lt;&lt;224.0,712.5&gt;-&lt;220.0,716.0&gt;-&lt;220.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E79 (U+1E79): B&lt;&lt;367.0,907.0&gt;-&lt;367.0,902.0&gt;-&lt;363.0,898.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E79 (U+1E79): B&lt;&lt;363.0,898.5&gt;-&lt;359.0,895.0&gt;-&lt;354.0,895.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E79 (U+1E79): B&lt;&lt;181.5,898.5&gt;-&lt;178.0,902.0&gt;-&lt;178.0,907.0&gt;&gt; has the same coordinates as a previous segment.

* wacute (U+1E83): B&lt;&lt;407.0,721.0&gt;-&lt;407.0,716.0&gt;-&lt;403.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* wacute (U+1E83): B&lt;&lt;403.0,712.5&gt;-&lt;399.0,709.0&gt;-&lt;394.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* wacute (U+1E83): B&lt;&lt;221.5,712.5&gt;-&lt;218.0,716.0&gt;-&lt;218.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* wgrave (U+1E81): B&lt;&lt;449.0,721.0&gt;-&lt;449.0,716.0&gt;-&lt;445.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* wgrave (U+1E81): B&lt;&lt;273.0,709.0&gt;-&lt;268.0,709.0&gt;-&lt;264.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* wgrave (U+1E81): B&lt;&lt;264.0,712.5&gt;-&lt;260.0,716.0&gt;-&lt;260.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* yacute (U+00FD): B&lt;&lt;398.0,721.0&gt;-&lt;398.0,716.0&gt;-&lt;394.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* yacute (U+00FD): B&lt;&lt;394.0,712.5&gt;-&lt;390.0,709.0&gt;-&lt;385.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* yacute (U+00FD): B&lt;&lt;212.5,712.5&gt;-&lt;209.0,716.0&gt;-&lt;209.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* ygrave (U+1EF3): B&lt;&lt;440.0,721.0&gt;-&lt;440.0,716.0&gt;-&lt;436.5,712.5&gt;&gt; has the same coordinates as a previous segment.

* ygrave (U+1EF3): B&lt;&lt;264.0,709.0&gt;-&lt;259.0,709.0&gt;-&lt;255.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* ygrave (U+1EF3): B&lt;&lt;255.0,712.5&gt;-&lt;251.0,716.0&gt;-&lt;251.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* zacute (U+017A): B&lt;&lt;360.0,721.0&gt;-&lt;360.0,716.0&gt;-&lt;356.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* zacute (U+017A): B&lt;&lt;356.0,712.5&gt;-&lt;352.0,709.0&gt;-&lt;347.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* zacute (U+017A): B&lt;&lt;174.5,712.5&gt;-&lt;171.0,716.0&gt;-&lt;171.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;442.0,222.0&gt;--&lt;624.0,112.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;334.0,221.0&gt;--&lt;388.0,28.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;260.0,295.0&gt;--&lt;149.0,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;262.0,401.0&gt;--&lt;56.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;333.0,478.0&gt;--&lt;152.0,584.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;442.0,478.0&gt;--&lt;388.0,669.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;516.0,402.0&gt;--&lt;617.0,577.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;517.0,296.0&gt;--&lt;720.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* gravecomb (U+0300): B&lt;&lt;220.0,547.0&gt;-&lt;220.0,542.0&gt;-&lt;216.5,538.5&gt;&gt; has the same coordinates as a previous segment.

* gravecomb (U+0300): B&lt;&lt;44.0,535.0&gt;-&lt;39.0,535.0&gt;-&lt;35.0,538.5&gt;&gt; has the same coordinates as a previous segment.

* gravecomb (U+0300): B&lt;&lt;35.0,538.5&gt;-&lt;31.0,542.0&gt;-&lt;31.0,547.0&gt;&gt; has the same coordinates as a previous segment.

* acutecomb (U+0301): B&lt;&lt;149.0,547.0&gt;-&lt;149.0,542.0&gt;-&lt;145.0,538.5&gt;&gt; has the same coordinates as a previous segment.

* acutecomb (U+0301): B&lt;&lt;145.0,538.5&gt;-&lt;141.0,535.0&gt;-&lt;136.0,535.0&gt;&gt; has the same coordinates as a previous segment.

* acutecomb (U+0301): B&lt;&lt;-36.5,538.5&gt;-&lt;-40.0,542.0&gt;-&lt;-40.0,547.0&gt;&gt; has the same coordinates as a previous segment.

* uni030F (U+030F): B&lt;&lt;135.0,557.0&gt;-&lt;135.0,552.0&gt;-&lt;131.5,548.5&gt;&gt; has the same coordinates as a previous segment.

* uni030F (U+030F): B&lt;&lt;-41.0,545.0&gt;-&lt;-46.0,545.0&gt;-&lt;-50.0,548.5&gt;&gt; has the same coordinates as a previous segment.

* uni030F (U+030F): B&lt;&lt;-50.0,548.5&gt;-&lt;-54.0,552.0&gt;-&lt;-54.0,557.0&gt;&gt; has the same coordinates as a previous segment.

* uni030F (U+030F): B&lt;&lt;201.0,545.0&gt;-&lt;196.0,545.0&gt;-&lt;192.0,548.5&gt;&gt; has the same coordinates as a previous segment.

* uni030F (U+030F): B&lt;&lt;192.0,548.5&gt;-&lt;188.0,552.0&gt;-&lt;188.0,557.0&gt;&gt; has the same coordinates as a previous segment.

* grave (U+0060): B&lt;&lt;220.0,547.0&gt;-&lt;220.0,542.0&gt;-&lt;216.5,538.5&gt;&gt; has the same coordinates as a previous segment.

* grave (U+0060): B&lt;&lt;44.0,535.0&gt;-&lt;39.0,535.0&gt;-&lt;35.0,538.5&gt;&gt; has the same coordinates as a previous segment.

* grave (U+0060): B&lt;&lt;35.0,538.5&gt;-&lt;31.0,542.0&gt;-&lt;31.0,547.0&gt;&gt; has the same coordinates as a previous segment.

* acute (U+00B4): B&lt;&lt;149.0,547.0&gt;-&lt;149.0,542.0&gt;-&lt;145.0,538.5&gt;&gt; has the same coordinates as a previous segment.

* acute (U+00B4): B&lt;&lt;145.0,538.5&gt;-&lt;141.0,535.0&gt;-&lt;136.0,535.0&gt;&gt; has the same coordinates as a previous segment.

* acute (U+00B4): B&lt;&lt;-36.5,538.5&gt;-&lt;-40.0,542.0&gt;-&lt;-40.0,547.0&gt;&gt; has the same coordinates as a previous segment.

* IJacute (U+E133): B&lt;&lt;578.0,721.0&gt;-&lt;578.0,716.0&gt;-&lt;574.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* IJacute (U+E133): B&lt;&lt;574.0,712.5&gt;-&lt;570.0,709.0&gt;-&lt;565.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* IJacute (U+E133): B&lt;&lt;392.5,712.5&gt;-&lt;389.0,716.0&gt;-&lt;389.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* IJacute (U+E133): B&lt;&lt;283.0,721.0&gt;-&lt;283.0,716.0&gt;-&lt;279.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* IJacute (U+E133): B&lt;&lt;279.0,712.5&gt;-&lt;275.0,709.0&gt;-&lt;270.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* IJacute (U+E133): B&lt;&lt;97.5,712.5&gt;-&lt;94.0,716.0&gt;-&lt;94.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* ijacute (U+E134): B&lt;&lt;578.0,721.0&gt;-&lt;578.0,716.0&gt;-&lt;574.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* ijacute (U+E134): B&lt;&lt;574.0,712.5&gt;-&lt;570.0,709.0&gt;-&lt;565.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* ijacute (U+E134): B&lt;&lt;392.5,712.5&gt;-&lt;389.0,716.0&gt;-&lt;389.0,721.0&gt;&gt; has the same coordinates as a previous segment.

* ijacute (U+E134): B&lt;&lt;283.0,721.0&gt;-&lt;283.0,716.0&gt;-&lt;279.0,712.5&gt;&gt; has the same coordinates as a previous segment.

* ijacute (U+E134): B&lt;&lt;279.0,712.5&gt;-&lt;275.0,709.0&gt;-&lt;270.0,709.0&gt;&gt; has the same coordinates as a previous segment.

* ijacute (U+E134): B&lt;&lt;97.5,712.5&gt;-&lt;94.0,716.0&gt;-&lt;94.0,721.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- _currency_part

- dotlessi_dotbelowcomb

- guillemotleft.case

- guillemotright.case

- prime

- uni01310328

- uni01310330
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, hebrew, tifinagh, coptic, old-permic, tai-le, malayalam, duployan, todhri, canadian-aboriginal, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee, duployan</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, cherokee, math</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: syriac, sunuwar, tifinagh, thai, cherokee, caucasian-albanian, gothic</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, math, greek</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: kaithi, hebrew, armenian, arabic, sora-sompeng, syloti-nagri, coptic, kharoshthi, kayah-li, sundanese, yi, lisu, cham</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+21BA ANTICLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21BB CLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21C4 RIGHTWARDS ARROW OVER LEFTWARDS ARROW: try adding math</li>
<li>U+21C5 UPWARDS ARROW LEFTWARDS OF DOWNWARDS ARROW: try adding math</li>
<li>U+21E7 UPWARDS WHITE ARROW: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+2318 PLACE OF INTEREST SIGN: try adding symbols</li>
<li>U+2325 OPTION KEY: try adding symbols</li>
<li>U+23CE RETURN SYMBOL: try adding symbols</li>
<li>U+23CF EJECT SYMBOL: try adding symbols</li>
<li>U+23E9 BLACK RIGHT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23EA BLACK LEFT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23ED BLACK RIGHT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23EE BLACK LEFT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23F5 BLACK MEDIUM RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+23F8 DOUBLE VERTICAL BAR: try adding symbols</li>
<li>U+23F9 BLACK SQUARE FOR STOP: try adding symbols</li>
<li>U+23FA BLACK CIRCLE FOR RECORD: try adding symbols</li>
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: symbols, yi, mongolian</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, yi, mongolian</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: symbols, yi, mongolian</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, yi, mongolian</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: symbols, yi, mongolian</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, yi, mongolian</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: symbols, yi, mongolian</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: symbols, yi, mongolian</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24B7 CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+24B8 CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+24B9 CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+24BA CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+24BB CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+24BC CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+24BD CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+24BE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+24BF CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+24C1 CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+24C2 CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+24C3 CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+24C4 CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+24C5 CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+24C6 CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+24C7 CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+24C8 CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+24C9 CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+24CA CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+24CB CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+24CC CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+24CD CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+24CE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+24CF CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+24D1 CIRCLED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+24D2 CIRCLED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+24D3 CIRCLED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24D4 CIRCLED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24D5 CIRCLED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24D6 CIRCLED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24D7 CIRCLED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24D8 CIRCLED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24D9 CIRCLED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24DA CIRCLED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24DB CIRCLED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24DC CIRCLED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24DD CIRCLED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24DE CIRCLED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24DF CIRCLED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24E0 CIRCLED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24E1 CIRCLED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24E2 CIRCLED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24E3 CIRCLED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24E4 CIRCLED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24E5 CIRCLED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24E6 CIRCLED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24E7 CIRCLED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24E8 CIRCLED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24E9 CIRCLED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+24EA CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: newa, warang-citi, ahom, javanese, armenian, lepcha, chakma, mongolian, mahajani, pahawh-hmong, syriac, meetei-mayek, adlam, coptic, devanagari, manichaean, psalter-pahlavi, thai, khudawadi, gujarati, kaithi, masaram-gondi, tagalog, khmer, tai-le, duployan, gunjala-gondi, marchen, buginese, kharoshthi, buhid, myanmar, nko, phags-pa, gurmukhi, telugu, dogra, batak, zanabazar-square, bengali, balinese, mende-kikakui, tirhuta, tagbanwa, symbols, kayah-li, tai-tham, brahmi, siddham, miao, tai-viet, caucasian-albanian, yi, syloti-nagri, modi, new-tai-lue, wancho, khojki, cham, sinhala, saurashtra, lao, takri, sharada, limbu, soyombo, old-permic, math, mandaic, music, tifinagh, tibetan, kannada, hanifi-rohingya, sundanese, grantha, canadian-aboriginal, sogdian, hanunoo, hebrew, elbasan, malayalam, bhaiksuki, bassa-vah, osage, rejang, oriya, tamil, thaana</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2606 WHITE STAR: try adding symbols</li>
<li>U+261A BLACK LEFT POINTING INDEX: try adding symbols</li>
<li>U+261B BLACK RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261C WHITE LEFT POINTING INDEX: try adding symbols</li>
<li>U+261D WHITE UP POINTING INDEX: try adding symbols</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261F WHITE DOWN POINTING INDEX: try adding symbols</li>
<li>U+262F YIN YANG: try adding symbols</li>
<li>U+2639 WHITE FROWNING FACE: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+2766 FLORAL HEART: try adding symbols</li>
<li>U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols</li>
<li>U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols</li>
<li>U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols</li>
<li>U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols</li>
<li>U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols</li>
<li>U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols</li>
<li>U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols</li>
<li>U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols</li>
<li>U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols</li>
<li>U+2B1B BLACK LARGE SQUARE: try adding symbols</li>
<li>U+2B1C WHITE LARGE SQUARE: try adding symbols</li>
<li>U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+E133 : not included in any glyphset definition</li>
<li>U+E134 : not included in any glyphset definition</li>
<li>U+E135 : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FB06 LATIN SMALL LIGATURE ST: not included in any glyphset definition</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
<li>U+1F150 NEGATIVE CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F151 NEGATIVE CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F152 NEGATIVE CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F153 NEGATIVE CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F154 NEGATIVE CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F155 NEGATIVE CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F156 NEGATIVE CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F157 NEGATIVE CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F158 NEGATIVE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F159 NEGATIVE CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F15A NEGATIVE CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F15B NEGATIVE CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F15C NEGATIVE CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F15D NEGATIVE CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F15E NEGATIVE CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F15F NEGATIVE CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F160 NEGATIVE CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F161 NEGATIVE CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F162 NEGATIVE CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F163 NEGATIVE CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F164 NEGATIVE CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F165 NEGATIVE CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F166 NEGATIVE CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F167 NEGATIVE CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F168 NEGATIVE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F169 NEGATIVE CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F500 TWISTED RIGHTWARDS ARROWS: not included in any glyphset definition</li>
<li>U+1F501 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F502 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS WITH CIRCLED ONE OVERLAY: not included in any glyphset definition</li>
<li>U+1F503 CLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: try adding symbols</li>
<li>U+1F504 ANTICLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F5A2 BLACK UP POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F5A3 BLACK DOWN POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F7CF HEAVY EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D3 HEAVY TWELVE POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D4 HEAVY TWELVE POINTED PINWHEEL STAR: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* a.blackCircled has a counter-clockwise outer contour

* b.blackCircled has a counter-clockwise outer contour

* blackFrowningFace (U+E135) has a counter-clockwise outer contour

* c.blackCircled has a counter-clockwise outer contour

* d.blackCircled has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide.case has a counter-clockwise outer contour

* divide.case has a counter-clockwise outer contour

* e.blackCircled has a counter-clockwise outer contour

* f.blackCircled has a counter-clockwise outer contour

* four.osf has a counter-clockwise outer contour

* four.tosf has a counter-clockwise outer contour

* g.blackCircled has a counter-clockwise outer contour

* h.blackCircled has a counter-clockwise outer contour

* i.blackCircled has a counter-clockwise outer contour

* invsmileface (U+263B) has a counter-clockwise outer contour

* j.blackCircled has a counter-clockwise outer contour

* k.blackCircled has a counter-clockwise outer contour

* l.blackCircled has a counter-clockwise outer contour

* m.blackCircled has a counter-clockwise outer contour

* n.blackCircled has a counter-clockwise outer contour

* o.blackCircled has a counter-clockwise outer contour

* p.blackCircled has a counter-clockwise outer contour

* q.blackCircled has a counter-clockwise outer contour

* r.blackCircled has a counter-clockwise outer contour

* s.blackCircled has a counter-clockwise outer contour

* t.blackCircled has a counter-clockwise outer contour

* trademark (U+2122) has a counter-clockwise outer contour

* u.blackCircled has a counter-clockwise outer contour

* u1F150 (U+1F150) has a counter-clockwise outer contour

* u1F151 (U+1F151) has a counter-clockwise outer contour

* u1F152 (U+1F152) has a counter-clockwise outer contour

* u1F153 (U+1F153) has a counter-clockwise outer contour

* u1F154 (U+1F154) has a counter-clockwise outer contour

* u1F155 (U+1F155) has a counter-clockwise outer contour

* u1F156 (U+1F156) has a counter-clockwise outer contour

* u1F157 (U+1F157) has a counter-clockwise outer contour

* u1F158 (U+1F158) has a counter-clockwise outer contour

* u1F159 (U+1F159) has a counter-clockwise outer contour

* u1F15A (U+1F15A) has a counter-clockwise outer contour

* u1F15B (U+1F15B) has a counter-clockwise outer contour

* u1F15C (U+1F15C) has a counter-clockwise outer contour

* u1F15D (U+1F15D) has a counter-clockwise outer contour

* u1F15E (U+1F15E) has a counter-clockwise outer contour

* u1F15F (U+1F15F) has a counter-clockwise outer contour

* u1F160 (U+1F160) has a counter-clockwise outer contour

* u1F161 (U+1F161) has a counter-clockwise outer contour

* u1F162 (U+1F162) has a counter-clockwise outer contour

* u1F163 (U+1F163) has a counter-clockwise outer contour

* u1F164 (U+1F164) has a counter-clockwise outer contour

* u1F165 (U+1F165) has a counter-clockwise outer contour

* u1F166 (U+1F166) has a counter-clockwise outer contour

* u1F167 (U+1F167) has a counter-clockwise outer contour

* u1F168 (U+1F168) has a counter-clockwise outer contour

* u1F169 (U+1F169) has a counter-clockwise outer contour

* uni24FF (U+24FF) has a counter-clockwise outer contour

* uni25C6 (U+25C6) has a counter-clockwise outer contour

* uni25CF (U+25CF) has a counter-clockwise outer contour

* uni2776 (U+2776) has a counter-clockwise outer contour

* uni2777 (U+2777) has a counter-clockwise outer contour

* uni2778 (U+2778) has a counter-clockwise outer contour

* uni2779 (U+2779) has a counter-clockwise outer contour

* uni277A (U+277A) has a counter-clockwise outer contour

* uni277B (U+277B) has a counter-clockwise outer contour

* uni277C (U+277C) has a counter-clockwise outer contour

* uni277D (U+277D) has a counter-clockwise outer contour

* uni277E (U+277E) has a counter-clockwise outer contour

* v.blackCircled has a counter-clockwise outer contour

* w.blackCircled has a counter-clockwise outer contour

* x.blackCircled has a counter-clockwise outer contour

* y.blackCircled has a counter-clockwise outer contour

* z.blackCircled has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 9 | 89 | 7 | 125 | 0 | 
| 0% | 0% | 3% | 4% | 38% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
