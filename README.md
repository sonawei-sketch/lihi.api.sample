# lihi
sample code

終端機指令版本
1. 到 lihi 短網址後台找 api key 金鑰 
2. 把下方的 7bKRlQTAFjf0Bs4qN25hM0rvTOrCgxtiXeUXXXXX 取代成你的 api key 
3. 把下方的 https://google.com 取代成你的長網址
4. 把下方代碼貼到終端機 press Enter
```
curl -X POST \
  https://app.lihi.io/api/v1/url \
  -H 'Authorization: x-api-key:OTMNfmM2k8FqM1afVlXDJMJdLiGwsNLTwPno4602' \
  -H 'Content-Type: application/x-www-form-urlencoded' \
  -H 'cache-control: no-cache' \
  -d 'longUrl=[https://google.com](https://www.select99.com/events/%E6%B2%99%E6%A3%98-%E6%AF%8D%E8%A6%AA%E7%AF%80?order-coupon=ED4823A8&rcode=JYYTPP7Y&affiliate-code=JYYTPP7Y&utm_source=77-%E8%9D%A6%E5%A4%AA%E5%A4%AA&utm_medium=1043-2605-%E6%B2%99%E6%A3%98%E6%AF%8D%E8%A6%AA%E7%AF%80&utm_campaign={lihi}&)'
```

Updated at 2019-03-31
