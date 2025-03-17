laragon-portable-env
====================
1. Download [laragon-portable](https://laragon.org/download/)
2. Download [PHP for windows (portable)](https://windows.php.net/download), then unzip to `.\bin\php\php-x.x.xx-Win32-vcxx-x64`
3. Overwrite / add files from this repository to their respective location
4. Edit `./etc/nginx/sites-enabled/00-default.conf`, change the absolute path
5. Edit `./usr/laragon.ini`, change the absolute paths and versions in `[php]` and `[nginx]`
6. `git clone https://XXXXXXX.git www`, `www` is the git repo
7. Run `.\composer-install.cmd`
8. Run `.\bin\php\php-x.x.xx-Win32-vcxx-x64\start-php-cgi.cmd`
9. Run `.\laragon.exe`, the default port `:8080` should not collide


### PHP
- https://windows.php.net/downloads/releases/archives/
  - [php-8.0.0-Win32-vs16-x64.zip](https://windows.php.net/downloads/releases/archives/php-8.0.0-Win32-vs16-x64.zip)

### MariaDB
- https://archive.mariadb.org/mariadb-10.11.10/winx64-packages/
  - https://archive.mariadb.org/mariadb-10.11.10/winx64-packages/mariadb-10.11.10-winx64.zip
