# TinySegmenter-Python

MeCabの開発者工藤さんがJavascriptで作成した<a href="http://chasen.org/~taku/software/TinySegmenter/">TinySegmenter</a>を、Pythonで作成したもの。
TinySegmenter.pyと同じディレクトリに置くなどして import して使えます。<br>
sample code<br>
<code>
from TinySegmenter import TinySegmenter
sentence = "私は元気です。"
segmenter = TinySegmenter()
print( segmenter.segment(sentence) )
</code>

© 2008 Taku Kudo <taku@chasen.org>
