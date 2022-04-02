# 恶意爬虫IP段  

#### 介绍  
恶意爬虫IP段

#### 使用说明  
这些都是没用的恶意爬虫可以直接拦截  


#### 常见爬虫 user-agent  
以下爬虫经常被伪造  
如果遇到疑似伪造的恶意爬虫可以反查一下IP  

linux下执行:  
host 116.179.32.234  
如果返回类似的  
234.32.179.116.in-addr.arpa domain name pointer baiduspider-116-179-32-234.crawl.baidu.com.  
则表示这个IP是真正的百度爬虫   


百度:  
user agent:Mozilla/5.0 (compatible; Baiduspider/2.0; +http://www.baidu.com/search/spider.html)  
user agent:Mozilla/5.0 (Linux;u;Android 4.2.2;zh-cn;) AppleWebKit/534.46 (KHTML,like Gecko) Version/5.1 Mobile Safari/10600.6.3 (compatible; Baiduspider/2.0; +http://www.baidu.com/search/spider.html)  

反查IP: baiduspider-{ip}.crawl.baidu.com.  
常用IP段:  
220.181.108.*  
116.179.32.*  



谷歌:  
user agent:Mozilla/5.0 (Linux; Android 6.0.1; Nexus 5X Build/MMB29P) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/100.0.4896.60 Mobile Safari/537.36 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)  
反查IP:crawl-{ip}.googlebot.com.  
常用IP段：    
66.249.79.*  

bing:  
user agent:Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm)  

反查IP: msnbot-{ip}.search.msn.com.  





#### 常见没用的爬虫 user-agent  
Mozilla/5.0 (compatible; AhrefsBot/7.0; +http://ahrefs.com/robot/)  
Mozilla/5.0 (compatible; BLEXBot/1.0; +http://webmeup-crawler.com/)  
Mozilla/5.0 (compatible; Barkrowler/0.9; +https://babbar.tech/crawler)  
Mozilla/5.0 (compatible; DataForSeoBot/1.0; +https://dataforseo.com/dataforseo-bot)  
Mozilla/5.0 (compatible; MJ12bot/v1.4.8; http://mj12bot.com/)  
Mozilla/5.0 (compatible; SemrushBot/7~bl; +http://www.semrush.com/bot.html)  
