# 意識高い（？）つぶやきをするbot
##概要
###chatGPTにカタカナビジネス用語を用いた文章を生成してもらい(/static/txt/test.txt)、それを形態素解析とマルコフ連鎖を用いて、意味を破綻させています。
###これにより、難しい言葉を使いたいけど使いこなせていない人物を模したbotを作成しました。

##使い方
###playで文章生成、resetでリセット、voiceでずんだもんが新しい文章を読み上げてくれます。

##使用した言語、ライブラリ
###言語はPythonです。
###flaskを使用して作成しています。
###Mecab,markovify,voicevoxなど様々なライブラリを使用しています。必要なライブラリは適宜ダウンロードするようお願いします。


##参考にさせていただいたサイト
[形態素解析、マルコフ連鎖](https://gakogako.com/python_hiroyuki/)
[voicevox(youtube)](https://www.youtube.com/watch?v=ZkYW73bqAmI&t=551s)
[イラスト](https://www.irasutoya.com/2015/05/blog-post_722.html)


