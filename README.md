# Printed
A Print Friendly CSS Library.

Printed is a helpful little CSS library. Just include it within your project; and it'll ensure your layout is Print-Friendly, works for PDF printers, and your projects remain as ecologically viable as possible on visitors ink and paper supplies. You can stick with the default settings, or throw in some custom CSS for powerful formatting control. Below if you see "html[data-", it identifies an attribute and value you can provide to the root HTML element. If you see a (.value) then that value can be utilized on any element in your document.

Features:
* Complete HTML5 Element Support
* Text-Only Mode: html[data-theme=print-min]
* Advanced Url Pseudo & MIME Support
* Add Page Break After Title Cover (.cover)
* Hide Or Show Content (.hide) & (.show)
* Ten Built-In CSS3 Image Filter Properties:
  * (.blur), (.brightness), (.contrast)
  * (.invert), (.monochrome), (.saturate), (.sepia)
  * (.hue-90), (.hue-180), (.hue-270)
* Print Single, Full-Page Or Image Gallery:
  * html[data-img=value] + .value
  * (full-page), (gallery), (individual)
* Set Page Break Structure (.page-break)
* Dark Paper Mode: html[data-paper=dark]
* Exact Color Match: html[data-color=exact]
* Paper Size Sectioning:
  * html[data-paper=value] .paper-size
  * ledger, legal, letter
  * A3, A4, A5, B4, B5, JIS-B4, JIS-B5
* Landscape Columns:
  * html[data-col=value] .column
  * two, three, four
