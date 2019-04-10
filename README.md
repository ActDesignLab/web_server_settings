# web_server_settings

## nginxの設定ファイル
```
sudo cp nginx.conf /etc/nginx/
sudo cp conf.d/server.80.conf /etc/nginx/conf.d/
sudo service nginx restart
```

## php-fpmの設定ファイル
```
sudo mkdir /var/run/php-fpm
sudo cp php-fpm/www.conf /etc/opt/remi/php73/php-fpm.d/
sudo service php73-php-fpm restart
sudo service php73-php-fpm status
```
