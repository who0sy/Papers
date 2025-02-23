
# Papers
近几年的一些文章和工具

# List

| 时间 | 文章 |
| ---  | --- |
| 2018.04 | FuzzScanner：信息搜集开源小工具.pdf |
| 2018.09 | Tide(潮汐)网络空间探测平台建设思路分享.pdf |
| 2018.12 | Web弱口令通用检测方法探究.pdf |
| 2019.03 | Proxy_Pool自动化代理搜集+评估+存储+展示工具.pdf |
| 2019.04 | 渗透测试团队技术评级那些事儿.pdf |
| 2019.05 | Web指纹识别技术研究与优化实现.pdf |
| 2019.05 | 分布式web漏洞扫描平台WDScanner.pdf |
| 2019.05 | 智能摄像头安全分析及案例参考.pdf |
| 2019.11 | 使用peach进行模糊测试从入门到放弃.pdf |
| 2019.12 | Tide安全团队2019年度总结.pdf |
| 2019.12 | 一文解密所有weblogic密文.pdf |
| 2020.02 | 远控免杀从入门到实践(1)-基础篇.pdf |
| 2020.03 | 远控免杀从入门到实践(2)-工具总结篇.pdf |
| 2020.03 | 远控免杀从入门到实践(3)-代码篇-C-C++.pdf |
| 2020.03 | 远控免杀从入门到实践(4)-代码篇-C#.pdf |
| 2020.04 | 远控免杀从入门到实践(5)-代码篇-Python.pdf |
| 2020.04 | 远控免杀从入门到实践(6)-代码篇-Powershell.pdf |
| 2020.04 | 远控免杀从入门到实践(7)-代码篇-Golang+Ruby.pdf |
| 2020.05 | 远控免杀从入门到实践之白名单（113个）总结篇.pdf |
| 2020.06 | Mimikatz的18种免杀姿势及防御策略.pdf |
| 2020.06 | Tide-Mars：一款资产管理与威胁监测平台.pdf |


# Content

- **《2018.04-FuzzScanner：信息搜集开源小工具》**
    
    为了hw临时写的一个工具，主要是使用python调用了多个工具对目标进行自动化的信息搜集并分析结果，主要包括网站子域名、开放端口、端口指纹、c段地址、敏感目录、链接爬取等信息。
    
    [https://github.com/TideSec/FuzzScanner](https://github.com/TideSec/FuzzScanner)

- **《2018.09-Tide(潮汐)网络空间探测平台建设思路分享》**
    
    花费了两三个月做了一个类似fofa、钟馗之眼的网络空间探测平台，文章介绍了基本的思路和实现方法，开始是计划开源的，因为政策监管问题目前只是内部在使用。

    [https://github.com/TideSec/Tide](https://github.com/TideSec/Tide)

    
- **《2018.12-Web弱口令通用检测方法探究》**
    
    提供了一个通用web弱口令破解思路，最初是为了批量探测管理后台，后来加入了管理后台弱口令的探测，旨在批量检测那些没有验证码的管理后台，有验证码的除了OCR、卷积神经网络或者人工打码平台，目前还没法有效解决。
    
    [https://github.com/TideSec/web_pwd_common_crack](https://github.com/TideSec/web_pwd_common_crack)

    
- **《2019.03-Proxy_Pool自动化代理搜集+评估+存储+展示工具》**

    Proxy_Pool（代理资源池），一个小巧的代理ip抓取+评估+存储+展示的一体化的工具，包括了web展示和接口。
    
    [https://github.com/TideSec/Proxy_Pool](https://github.com/TideSec/Proxy_Pool)
    
- **《2019.04-渗透测试团队技术评级那些事儿》**

    根据我们内部的技术评级写了个渗透测试团队的技术评级方案，主要原则是：透明原则、引导技术为王的风气、尽量保证所有项都能被量化、多套考核相结合，从这份技术评级开始也慢慢完善了我们的绩效体系。
    
- **《2019.05-Web指纹识别技术研究与优化实现》**

    潮汐指纹平台的实现原理，汲取整合了多个web指纹库，结合了多种指纹检测方法，让指纹检测更快捷、准确。在线平台也断断续续的更新和完善，不过有时工作忙起来可能几个月也不看一次了。

    [https://github.com/TideSec/TideFinger](https://github.com/TideSec/TideFinger)

- **《2019.05-分布式web漏洞扫描平台WDScanner》**

    算是自己最早期写的一个平台了，php+python实现的，代码写的比较烂，不过功能全是比较全面的，一直打算重新升级改造一些，一直没时间动手，看现在市面上相似的平台更多，更是没动力去写了。
    
    [https://github.com/TideSec/WDScanner](https://github.com/TideSec/WDScanner)

- **《2019.05-智能摄像头安全分析及案例参考》**

    2018年左右的时候对一款摄像头做的安全分析，涉及了云端、手机端、摄像头设备、协议四个方面，那时候的逆向分析能力还比较Low（当然现在依旧Low），有些点都是浅尝辄止。
    
- **《2019.11-使用peach进行模糊测试从入门到放弃》**

    2019年研究工控安全的时候顺便学习了一些开源模糊测试框架Peach，文章系统介绍了Peach的结构、原理及pit文件编写方法，旨在帮助对模糊测试感兴趣的小伙伴能快速入门peach，最后以常见的http协议和工控Modbus协议为例进行了实验。
    
    [https://github.com/TideSec/Peach_Fuzzing](https://github.com/TideSec/Peach_Fuzzing)

- **《2019.12-Tide安全团队2019年度总结》**
    
    2019年算是Tide安全团队正式对外发文章、做开源、写平台的一年，一年下来收获还是不小的，感慨之余写了这篇总结，惟愿每年都有新的进步。
    
- **《2019.12-一文解密所有weblogic密文》**

    因为实战中遇到不少weblogic配置文件包含加密字段的情况，所以搜集了市面上绝大部分weblogic解密方式，整理了7种解密weblogic的方法及响应工具。
    
    [https://github.com/TideSec/Decrypt_Weblogic_Password](https://github.com/TideSec/Decrypt_Weblogic_Password)

- **2020.02-远控免杀从入门到实践**
    
    从2020年1月份开始到2020年6月，陆陆续续写了六七十篇关于免杀的文章，主要包括四部分内容：工具篇、代码篇、白名单篇、其他（实战）篇。2021年本来也打算再更新一些免杀新姿势，由于各种原因一拖再拖。
    
    [https://github.com/TideSec/BypassAntiVirus](https://github.com/TideSec/BypassAntiVirus)
    
    从中精选了部分内容：
    ```
    《2020.02-远控免杀从入门到实践(1)-基础篇》
    《2020.03-远控免杀从入门到实践(2)-工具总结篇》
    《2020.03-远控免杀从入门到实践(3)-代码篇-C-C++》
    《2020.03-远控免杀从入门到实践(4)-代码篇-C#》
    《2020.04-远控免杀从入门到实践(5)-代码篇-Python》
    《2020.04-远控免杀从入门到实践(6)-代码篇-Powershell》
    《2020.04-远控免杀从入门到实践(7)-代码篇-Golang+Ruby》
    《2020.05-远控免杀从入门到实践之白名单（113个）总结篇》
    ```

- **《2020.05-Mimikatz的18种免杀姿势及防御策略》**
    
    针对Mimiktaz进行免杀的研究，主要是想研究学习一下比较通用的exe的免杀方式，涉及源码免杀、无源码免杀、powershell免杀、加载器分离免杀、白名单免杀等方面，共18种免杀姿势。

- **《2020.06-Tide-Mars：一款资产管理与威胁监测平台》**
    
    Mars(战神)，设计初衷是想做个专门挖SRC的平台，能自动化的比较全面的搜集资产信息并能监测资产的变化情况，及时发现新应用或新服务，并能自动化匹配POC进行检测，进而提高SRC漏洞挖掘效率，所以在资产发现、指纹探测、变更监测方面做的稍微细致一些。
    
    [https://github.com/TideSec/Mars](https://github.com/TideSec/Mars)

# About Me

- [Tide安全团队](http://www.tidesec.com/) 创建者&&核心成员
- Web/工控/免杀 安全爱好者
- 在偏离攻防实战的路上越走越远
- 偶尔写写代码，关注自动化漏洞扫描技术
- 联系我: xyguest@gmail.com
