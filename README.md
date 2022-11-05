## URL Redirect
```
RewriteEngine On
RewriteCond %{HTTPS} !=on
RewriteRule ^/?(.*) https://www.w3schools.com//$1 [R,L]
```
