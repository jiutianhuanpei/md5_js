# md5_js


通过调用 md5(str) 来获取字符串 str 的md5值。

本来找这个是用来在 postman 的 Pre-request Script 里获取md5值用的，但后来又找到了一下更好用的:


var md5Str = CryptoJS.MD5(str).toString();
