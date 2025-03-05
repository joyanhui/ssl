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

证书最后更新  2024-04-02 21:27:57 letsencrypt 

证书最后更新  2024-04-09 21:27:45 letsencrypt 

证书最后更新  2024-04-09 21:29:53 zerossl 

证书最后更新  2024-04-16 21:31:32 zerossl 

证书最后更新  2024-04-23 21:27:11 letsencrypt 

证书最后更新  2024-04-23 21:29:32 zerossl 

证书最后更新  2024-04-30 21:25:53 letsencrypt 

证书最后更新  2024-04-30 21:31:30 zerossl 

证书最后更新  2024-05-07 21:25:57 letsencrypt 

证书最后更新  2024-05-07 21:28:25 zerossl 

证书最后更新  2024-05-14 21:29:42 letsencrypt 

证书最后更新  2024-05-14 21:31:32 zerossl 

证书最后更新  2024-05-21 21:31:43 letsencrypt 

证书最后更新  2024-05-21 21:34:08 zerossl 

证书最后更新  2024-05-28 21:29:33 letsencrypt 

证书最后更新  2024-05-28 21:31:44 zerossl 

证书最后更新  2024-06-04 21:29:50 letsencrypt 

证书最后更新  2024-06-04 21:32:38 zerossl 

证书最后更新  2024-06-11 21:30:45 letsencrypt 

证书最后更新  2024-06-11 21:32:11 zerossl 

证书最后更新  2024-06-18 21:30:28 letsencrypt 

证书最后更新  2024-06-18 21:32:25 zerossl 

证书最后更新  2024-06-25 21:30:21 letsencrypt 

证书最后更新  2024-06-25 21:32:16 zerossl 

证书最后更新  2024-07-02 21:30:15 letsencrypt 

证书最后更新  2024-07-02 21:32:23 zerossl 

证书最后更新  2024-07-09 21:30:14 letsencrypt 

证书最后更新  2024-07-09 21:31:49 zerossl 

证书最后更新  2024-07-16 21:26:14 letsencrypt 

证书最后更新  2024-07-16 21:28:49 zerossl 

证书最后更新  2024-07-23 21:30:58 letsencrypt 

证书最后更新  2024-07-23 21:33:48 zerossl 

证书最后更新  2024-07-30 21:31:32 letsencrypt 

证书最后更新  2024-08-06 21:33:23 letsencrypt 

证书最后更新  2024-08-06 21:34:38 zerossl 

证书最后更新  2024-08-13 21:32:27 letsencrypt 

证书最后更新  2024-08-13 21:35:27 zerossl 

证书最后更新  2024-08-20 21:33:20 letsencrypt 

证书最后更新  2024-08-20 21:35:10 zerossl 

证书最后更新  2024-08-27 21:32:56 letsencrypt 

证书最后更新  2024-08-27 21:37:31 zerossl 

证书最后更新  2024-09-03 21:37:13 letsencrypt 

证书最后更新  2024-09-03 21:38:43 zerossl 

证书最后更新  2024-09-10 21:35:11 letsencrypt 

证书最后更新  2024-09-10 21:38:12 zerossl 

证书最后更新  2024-09-17 21:38:44 zerossl 

证书最后更新  2024-09-17 22:15:43 letsencrypt 

证书最后更新  2024-09-24 21:37:50 letsencrypt 

证书最后更新  2024-09-24 21:40:29 zerossl 

证书最后更新  2024-10-01 21:38:33 letsencrypt 

证书最后更新  2024-10-01 21:41:34 zerossl 

证书最后更新  2024-10-08 21:37:01 letsencrypt 

证书最后更新  2024-10-08 21:39:10 zerossl 

证书最后更新  2024-10-15 21:38:36 letsencrypt 

证书最后更新  2024-10-22 21:38:43 letsencrypt 

证书最后更新  2024-10-22 21:40:54 zerossl 

证书最后更新  2024-10-29 21:39:24 letsencrypt 

证书最后更新  2024-10-29 21:41:26 zerossl 

证书最后更新  2024-11-05 21:36:07 letsencrypt 

证书最后更新  2024-11-05 21:38:29 zerossl 

证书最后更新  2024-11-12 21:39:00 zerossl 

证书最后更新  2024-11-12 22:35:51 letsencrypt 

证书最后更新  2024-11-19 21:41:25 letsencrypt 

证书最后更新  2024-11-19 21:44:56 zerossl 

证书最后更新  2024-11-26 21:40:28 letsencrypt 

证书最后更新  2024-11-26 21:44:29 zerossl 

证书最后更新  2024-12-03 21:41:32 letsencrypt 

证书最后更新  2024-12-03 21:44:22 zerossl 

证书最后更新  2024-12-10 21:41:29 letsencrypt 

证书最后更新  2024-12-10 21:45:14 zerossl 

证书最后更新  2024-12-17 21:41:06 letsencrypt 

证书最后更新  2024-12-17 21:45:12 zerossl 

证书最后更新  2024-12-24 21:34:14 letsencrypt 

证书最后更新  2024-12-24 21:37:30 zerossl 

证书最后更新  2024-12-31 21:33:54 letsencrypt 

证书最后更新  2024-12-31 21:40:42 zerossl 

证书最后更新  2025-01-07 21:43:03 letsencrypt 

证书最后更新  2025-01-07 22:29:05 zerossl 

证书最后更新  2025-01-14 21:33:12 letsencrypt 

证书最后更新  2025-01-14 21:37:27 zerossl 

证书最后更新  2025-01-21 21:34:25 letsencrypt 

证书最后更新  2025-01-21 21:38:24 zerossl 

证书最后更新  2025-01-28 21:38:00 letsencrypt 

证书最后更新  2025-01-28 21:38:20 zerossl 

证书最后更新  2025-02-04 06:52:11 letsencrypt 

证书最后更新  2025-02-04 07:17:12 zerossl 

证书最后更新  2025-02-06 11:16:34 zerossl 

证书最后更新  2025-02-06 11:58:46 zerossl 

证书最后更新  2025-02-06 14:18:42 zerossl 

证书最后更新  2025-02-06 16:13:55 zerossl 

证书最后更新  2025-02-06 16:26:59 zerossl 

证书最后更新  2025-02-06 16:43:41 zerossl 

证书最后更新  2025-02-25 10:35:26  

证书最后更新  2025-03-03 11:37:10 zerossl 

证书最后更新  2025-03-04 02:56:32 zerossl 

证书最后更新  2025-03-04 03:33:06 zerossl 

证书最后更新  2025-03-04 03:41:07 zerossl 

证书最后更新  2025-03-04 04:14:23 zerossl 

证书最后更新  2025-03-05 23:14:17 zerossl 
