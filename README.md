# iRingo
Committed to providing a complete Apple service experience.  
以下模块在macOS 12.0 beta 10, iOS 15.0.2, iOS 14.7.1 测试通过  

---

> 目录

* [定位服务](#Location%20Services)  
* [Siri与搜索](#Siri%20&amp;%20Search)    

---

### <a id="Location Services"> 定位服务 </a>
[Geo_Services.sgmodule](./sgmodule/Geo_Services.sgmodule " Rewrite Apple Geo Services Country Code")   
安装链接: https://raw.githubusercontent.com/VirgilClyne/iRingo/main/sgmodule/Geo_Services.sgmodule   
启用模块后打开一次地图即可切换区域至US  
macOS/iOS适用  
无需飞行模式、关闭定位、更改国家地区语言  
    作用:  
    - [x] 更改为海外版Apple Maps    
    - [x] 激活Apple News    
    - [x] 激活「来自APPLE的内容\来自APPLE的建议\Siri建议」   

---

### <a id="Siri & Search"> Siri与搜索 </a>  
[Siri_Suggestions.sgmodule](./sgmodule/Siri_Suggestions.sgmodule " Location-Based Siri Suggestions for Spotlight & Look Up & Safari")  
安装链接: https://raw.githubusercontent.com/VirgilClyne/iRingo/main/sgmodule/Siri_Suggestions.sgmodule  
启用模块即可保持「来自APPLE的内容(CONTENT FROM APPLE)\来自APPLE的建议(SUGGESTIONS FROM APPLE)\Siri建议\Siri Suggestions」持续可用   
macOS/iOS适用  
可能需要启用Geo_Services.sgmodule模块激活一下此功能，激活后可关闭Geo_Services.sgmodule  
    作用:  
    - [x] Siri资料(Siri Knowledge)  
    - [x] Siri建议的网站(siri Suggested Websites)   
    - [x] 维基百科  
    - [x] 比赛比分  
    - [x] 股票信息
    - [x] App Store\Mac App Store   
    - [x] 电影  
    - [x] 音乐  
    - [x] 新闻  
注：对北美地区「Siri建议」服务器无效(SSL Pinning)  
https://api.smoot.apple.com             （有效）  
https://api-aka-*.smoot.apple.com       （有效）  
https://api-glb.smoot.apple.com         （有效）  
https://api-glb-usw*.smoot.apple.com    （北美地区：无效）  
https://api-glb-euc*.smoot.apple.com    （欧洲地区：有效）  
https://api-glb-apne*.smoot.apple.com   （亚太地区：有效）  