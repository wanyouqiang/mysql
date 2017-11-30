《MySQL》
====================

### MySQL允许远程用户登录访问
* 授予权限 GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' IDENTIFIED BY 'youpassword' WITH GRANT OPTION;
* 刷新权限 FLUSH PRIVILEGES
