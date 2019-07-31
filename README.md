# curl_android_demo

CURL Download test with android

## libcurl中curl_easy_perform卡死问题

https://www.freehacker.cn/tools/libcurl-curl_easy_perform-blocking-problem/

But I cannot produce it 

Turn off network, and click button to download file
```
curl_easy_perform:6
```

Click button to download file, then turn off network 

```
2019-07-31 15:39:46.171 21701-23585/net.maytrue.openssl D/curl: length:1436
2019-07-31 15:39:46.171 21701-23585/net.maytrue.openssl D/curl: dltotal:34412430.000000, dlnow:824798.000000
2019-07-31 15:39:46.171 21701-23585/net.maytrue.openssl D/curl: dltotal:34412430.000000, dlnow:824798.000000
2019-07-31 15:39:46.560 21701-23585/net.maytrue.openssl D/curl: dltotal:34412430.000000, dlnow:824798.000000
2019-07-31 15:39:46.560 21701-23585/net.maytrue.openssl D/curl: curl_easy_perform:56
```

curl exist download loop successfully 


