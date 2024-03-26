# ssl
证书文件
这是域名的证书，zip文件用 32位密码保护。

国内代理前缀 ：https://gitee.com/joyanhui/ssl/raw/main

```
cd /root
rm -r ssl_zerossl.zip
#wget https://fastly.jsdelivr.net/gh/joyanhui/ssl@main/ssl_zerossl.zip
wget https://gitee.com/joyanhui/ssl/raw/main/ssl_zerossl.zip
if [ ! -f "/root/ssl_zerossl.zip" ]; then
 wget -O/dev/null -q "https://api.day.app/XXXXX/ssl_zerossl-nginxupdate-err/[home]?sound=birdsong&amp;isArchiv>
else
  rm -rf ssl_zerossl
  7z x ssl_zerossl.zip  -pXXXXXXXXXXXXXXXXXXXXXXXX  -ossl_zerossl
fi
rm -r ssl_letsencrypt.zip
#wget https://fastly.jsdelivr.net/gh/joyanhui/ssl@main/ssl_letsencrypt.zip
wget https://gitee.com/joyanhui/ssl/raw/main/ssl_letsencrypt.zip
if [ ! -f "/root/ssl_letsencrypt.zip" ]; then
 wget -O/dev/null -q "https://api.day.app/XXXXX/ssl_letsencrypt-nginxupdate-err/[home]?sound=birdsong&amp;isAr>
else
  rm -rf ssl_letsencrypt
  7z x ssl_letsencrypt.zip  pXXXXXXXXXXXXXXXXXXXXXXXX  -ossl_letsencrypt
fi
nginx -s reload
```

证书最后更新  2023-10-18 03:45:41 zerossl 

证书最后更新  2023-10-18 03:54:07 letsencrypt 

证书最后更新  2023-10-24 21:30:13 letsencrypt 

证书最后更新  2023-10-31 21:28:33 letsencrypt 

证书最后更新  2023-10-31 21:39:41 zerossl 

证书最后更新  2023-11-07 21:28:22 letsencrypt 

证书最后更新  2023-11-07 21:30:05 zerossl 

证书最后更新  2023-11-14 21:30:10 letsencrypt 

证书最后更新  2023-11-14 21:31:42 zerossl 

证书最后更新  2023-11-21 21:31:01 letsencrypt 

证书最后更新  2023-11-21 21:35:27 zerossl 

证书最后更新  2023-11-28 21:31:21 letsencrypt 

证书最后更新  2023-12-05 21:30:30 letsencrypt 

证书最后更新  2023-12-08 22:48:09 letsencrypt 

证书最后更新  2023-12-12 21:32:31 letsencrypt 

证书最后更新  2023-12-19 21:29:34 letsencrypt 

证书最后更新  2023-12-19 21:35:22 zerossl 

证书最后更新  2023-12-26 21:27:39 letsencrypt 

证书最后更新  2023-12-26 21:30:21 zerossl 

证书最后更新  2024-01-02 21:29:27 letsencrypt 

证书最后更新  2024-01-09 21:43:04 zerossl 

证书最后更新  2024-01-16 21:31:04 letsencrypt 

证书最后更新  2024-01-23 21:31:18 letsencrypt 

证书最后更新  2024-01-30 21:26:59 letsencrypt 

证书最后更新  2024-01-30 21:32:33 zerossl 

证书最后更新  2024-02-06 21:28:27 letsencrypt 

证书最后更新  2024-02-06 21:32:42 zerossl 

证书最后更新  2024-02-13 21:27:23 letsencrypt 

证书最后更新  2024-02-20 21:28:28 letsencrypt 

证书最后更新  2024-02-20 21:39:56 zerossl 

证书最后更新  2024-02-27 21:25:52 letsencrypt 

证书最后更新  2024-02-27 21:28:35 zerossl 

证书最后更新  2024-03-05 21:26:15 letsencrypt 

证书最后更新  2024-03-05 21:28:55 zerossl 

证书最后更新  2024-03-12 21:26:06 letsencrypt 

证书最后更新  2024-03-12 21:29:09 zerossl 

证书最后更新  2024-03-19 21:29:51 zerossl 

证书最后更新  2024-03-26 21:27:40 letsencrypt 

证书最后更新  2024-03-26 21:29:24 zerossl 
