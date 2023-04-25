# ChainLink_API

Folllow the steps mentioned at :
https://docs.chain.link/any-api/get-request/examples/single-word-response

This code fetches data from : https://httpbin.org/get?Test=123ABC

Which returns : 
<i>
{
  "args": {
    "Test": "123ABC"
  }, 
  "headers": {
    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7", 
    "Accept-Encoding": "gzip, deflate, br", 
    "Accept-Language": "en-GB,en-US;q=0.9,en;q=0.8", 
    "Cache-Control": "max-age=0", 
    "Host": "httpbin.org", 
    "Sec-Ch-Ua": "\"Chromium\";v=\"112\", \"Google Chrome\";v=\"112\", \"Not:A-Brand\";v=\"99\"", 
    "Sec-Ch-Ua-Mobile": "?0", 
    "Sec-Ch-Ua-Platform": "\"macOS\"", 
    "Sec-Fetch-Dest": "document", 
    "Sec-Fetch-Mode": "navigate", 
    "Sec-Fetch-Site": "none", 
    "Sec-Fetch-User": "?1", 
    "Upgrade-Insecure-Requests": "1", 
    "User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36", 
    "X-Amzn-Trace-Id": "Root=1-6447907e-786ffa7762c53b80337d0602"
  }, 
  "origin": "110.226.183.156", 
  "url": "https://httpbin.org/get?Test=123ABC"
} <i>


We are extracting   :
<b>
"args": {
    "Test": "123ABC" </b>
    
    From the data. 
    
Follow the Video : 
