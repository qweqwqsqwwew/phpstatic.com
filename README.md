# https://phpstatic.com

PHP package able to install at any linux distribution version.

# debian, ubuntu install

```sh
curl -O https://phpstatic.com/php-static-7.3_7.3.13_amd64.deb
dpkg -i php-static-7.3_7.3.13_amd64.deb
systemctl daemon-reload
systemctl enable php-fpm
systemctl start php-fpm
```
# redhat, centos install

