# webhookspamtool

Webhookでスパムしてくれる何か。悪用厳禁。

# 設置のやり方
1.まずWebサーバー(PHPが使えるもの)を作るか、または契約する<br>
(xreaやstarfreeなどの無料鯖でも可。WixやJindoなどの、無料でサイトを作るようなアレは不可。)<br>
2.上のwebhookspam.phpとwebhookspamtool.phpをサーバーに置く。<br>
(cgi-binでもおｋ。PHPが動くディレクトリに置くこと。)<br>
3.webhookspamtool.phpにアクセスする。やり方は<br>
http://(※サーバーのアドレス)/webhookspamtool.php<br>
※ここはwebhookspamtool.phpとwebhookspam.phpを置いたディレクトリにすること。<br>
例えばcgi-binに置いたのならば、<br>
http://(サーバーのアドレス)/cgi-bin/webhookspamtool.php<br>
/var/www/html/test/に置いたのならば、<br>
http://(※サーバーのアドレス)/test/webhookspamtool.php<br>
となる。<br>

# 使い方
URLのところにはWebhookのURLを貼り付ける。<br>
回数はご自由に。10000とか999でもおｋ。<br>
ただ増やしすぎはサーバーが過負荷になることもあるので調整しましょう。<br>
nameと画像URLは入れなくてもおk。Webhookの名前とアイコンになります。<br>
メッセージには発信したいメッセージを入れる。<br>
everyoneでスパムしたいのなら@everyone spamと入れる。<br>
あとは送信を押せば回数分spamしてくれます。<br>

悪用厳禁。自己責任でお願いします。<br>
あと著作権はないと思われる？<br>
