# php-nginx

##　nginxの設定について
サブディレクトリでの配置などについて

下記変数をログで１つ１つ見ていき、推測していく
http://localhost:8080/subdir/sample.phpにアクセスした時

$document_root　ドキュメントルートの値　/usr/share/nginx/html/subdir/public
$request_filename URL上から見に行くファイル名　/usr/share/nginx/html/subdir/public/subdir/sample.php
$fastcgi_path_info 
$fastcgi_script_name　ドメイン直下のURL subdir/sample.php

### 参考リンク
https://skill-up-engineering.com/2021/05/30/nginx%e3%81%a7%e3%81%ae%e8%a8%ad%e5%ae%9a%e3%81%ab%e3%81%a4%e3%81%84%e3%81%a6/

rootとaliasについて<br>
https://qiita.com/oogaki_newmedia/items/749c855ad985c8258e66

nginxの変数について<br>
https://qiita.com/kotarella1110/items/3b0bd84fdb55276f37d9

サブディレクトリの配置について<br>
https://aqua-engineer.com/post-834/<br>
https://qiita.com/yyano/items/a0d141a91ba8d867985e