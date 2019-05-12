nginx -c /etc/nginx/nginx.conf
Nginx -s stop
Nginx -s stop


 if ($request_uri =~ ^/school/ ) {
       proxy_pass http://127.0.0.1:4301$request_uri;
 }


检查语法
nginx -t


Qing Cloud

sudo service nginx restart
vim /etc/nginx/sites-enabled/coigre.com
/etc/init.d/nginx restart 
fuser -k -n tcp 3000



7758991
