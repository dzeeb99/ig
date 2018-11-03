Bot-Auto Register Account Instagram [PHP - CLI] 
Penggunaan di Windows :
1. Pake XAMPP install php Curl nya dulu ,Tutor https://www.petanikode.com/php-curl/
2. Download File nya 
3. Jalanin deh
Penggunaan di Linux :
$ apt install php php-curl -y
$ apt-get update
$ git clone 
$ chmod -R 777 ggwp/ && cd ggwp
$ php bot-reg-ig.php
Penggunaan di Termux :
$ pkg install php php-curl
$ git clone 
$ chmod -R 777 ig/ && cd ig
$ php bot-reg-ig.php

Edit Data dibawah ini di Line 186 - 189 
$email = "(emailo)".rand(000000,9999)."@gmail.com"; /// Edit Sama email Lo
$username = "risman.id_".rand(000000,9999);  /// Edit Username yg u inginkan
$password = "f0xbase123";  /// Edit password yg u inginkan

Edit Data dibawah ini di Line 225 
$loop = 10; //Edit Loop untuk Creat Berapa Akun yg ingin di create
