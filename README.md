# php环境一键安装包 #

### 注意事项： ###
1. 支持系统是centos6
2. 这个脚本设计的初衷是为了线上环境部署，因此默认需要root权限
3. 由于隐私问题，将ssl证书与httpd-vhosts.conf去除了，需要的需要自行配置
4. 这个脚本的mysql仅正常装至mysql初始化，会在会话中给出一个初始密码，需要自行更改
5. 更改完后通过service httpd start与service mysqld start启动服务
6. 本脚本暂不支持部署nginx。
7. apache指向目录: /data/www
8. mysql数据库目录： /data/mysql
9. 所有的包安装好后都放在 /usr/local 目录下

2017-08-12 - created by szitv
