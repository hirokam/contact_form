# お問い合わせフォーム
## 環境構築
Dockerビルド

　1.[git clone](git@github.com:hirokam/advance_test_kameyamahiroki.git)
 
　2.docker-compose up -d --build

Laravel環境構築

　1.docker-compose exec php bash

　2.composer install

　3..env.exampleファイルから.envファイルを作成し、環境変数を変更

　4.php artisan key:generate

　5.php artisan migrate

　6.php artisan db:seed

## 使用技術

 ・PHP　8.2
 
 ・Laravel 8.83
 
 ・MySQL 8.0

 ## ER図
 ![ER図](ER_Drawing.png)

 ## URL

 ・開発環境：http://localhost/
 
 ・phpMyAdmin：http://localhost:8080/
