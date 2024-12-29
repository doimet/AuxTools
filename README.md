![AuxTools](https://socialify.git.ci/doimet/AuxTools/image?description=1&descriptionEditable=%E5%9B%BE%E5%BD%A2%E5%8C%96%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7&font=Inter&name=1&pattern=Circuit%20Board&theme=Light)

## 界面截图

![Image](docs/images/screenshot_01.png)

![Image](docs/images/screenshot_02.png)

## 模块列表
|  模块名称 | 功能描述 | 支持系统 | 备注信息 |
|---|---|---|---|
|  Whois查询 | 该模块用于执行 Whois 查询，允许用户查询域名注册信息以及 IP 地址的所有者和相关信息 | windows/linux |  |
|  IP地址查询 | 该模块用于执行 IP 地址查询，允许用户查询指定 IP 地址的地理位置、所有者和其他相关信息 | windows/linux |  |
|  IP解析查询 | 该模块用于查询IP地址对应的域名信息，以确定IP解析出的域名及其相关信息 | windows/linux |  |
|  域名枚举 | 该模块用于枚举可能存在的域名 | windows/linux |  |
|  域名解析 | 该模块用于解析域名，快速获取其对应的IP地址和DNS记录信息 | windows/linux |  |
|  子域名收集 | 该模块用于收集目标域名的子域名信息，帮助发现与主域名相关的所有子域，以便进行安全分析或资产盘点 | windows/linux |  |
|  备案查询 | 该模块用于执行备案查询，允许用户查询指定域名或 IP 地址是否在指定地区进行了备案，并提供备案信息 | windows/linux |  |
|  端口扫描 | 该模块用于执行端口扫描，允许用户扫描指定主机或 IP 地址上的开放端口，以识别可用的服务和应用程序 | windows/linux |  |
|  站点扫描 | 该模块通过发送HTTP请求，分析服务器响应，利用字典和爬虫技术发现目标网站上的隐藏目录和文件 | windows/linux |  |
|  空间测绘 | 该模块使用 Fofa、Shodan 等网络空间测绘引擎进行搜索，帮助用户搜集公开暴露的资产信息 | windows/linux |  |
|  邮箱收集 | 该模块用于收集和提取指定目标中的邮箱地址，常用于情报收集和数据分析 | windows/linux |  |
|  CDN检测 | 该模块用于执行 CDN（内容分发网络）检测，允许用户确定指定域名或 IP 地址是否使用了 CDN 服务，并提供有关 CDN 提供商和配置的信息 | windows/linux |  |
|  HOST碰撞 | 该模块通过生成大量可能的IP地址或主机名组合，并使用主动探测或发现来验证目标主机的存在性 | windows/linux |  |
|  手机号归属地查询 | 该模块用于查询手机号码的归属地信息，包括运营商、省份和城市等信息 | windows/linux |  |
|  手机号注册查询 | 该模块用于查询手机号注册信息，检测号码是否已被用于注册特定平台或服务 | windows/linux |  |
|  泄露密钥利用 | 该模块用于利用泄露的密钥，针对阿里云、腾讯云、华为云等云厂商的泄露密钥进行安全评估和漏洞利用 | windows/linux | 暂不对外开放 |
|  口令爆破 | 该模块用于对服务进行口令爆破攻击，通过尝试大量密码组合来破解账户的登录凭证 | windows/linux |  |
|  快捷方式生成 | 该模块可以将恶意可执行文件（.exe）嵌入到快捷方式（.lnk）文件中，以便在执行快捷方式时同时执行恶意文件 | windows |  |
|  虚拟身份生成 | 该模块用于生成随机身份信息，包括姓名、性别、年龄、地址、身份证号等，适用于测试或数据模拟场景 | windows/linux |  |
|  EXIF信息提取 | 该模块用于提取图像文件中的EXIF（Exchangeable Image File Format）信息，包括拍摄设备、拍摄时间、地理位置等元数据 | windows/linux |  |
|  社工字典生成 | 该模块用于生成社工字典，提供多种常见的社交工程攻击词汇和组合，辅助渗透测试和安全分析 | windows/linux |  |
|  编码解码 | 该模块提供了数据的编码和解码功能，可以将数据转换成特定的格式或从特定的格式解析数据 | windows/linux |  |
|  加密解密 | 该模块提供了加密和解密数据的功能，用于对数据进行保护和恢复 | windows/linux |  |
|  进制转换 | 该模块提供了进制转换功能，可以将数据在不同进制之间进行转换，如二进制、十进制、十六进制等 | windows/linux |  |
|  网段合并 | 该模块提供了网段合并功能，用于将多个网段合并成更大的网段 | windows/linux |  |
|  哈希识别 | 该模块用来识别不同类型的散列加密，进而判断哈希算法的类型 | windows/linux |  |
|  文本比对 | 该模块提供了文本比对功能，用于比较两个文本文件或字符串，找出它们之间的差异和相似之处 | windows/linux |  |
|  关键进程识别 | 该模块用于识别系统进程中的关键进程名称 | windows/linux |  |
|  网络连接分析 | 该模块可用于分析网络连接中IP地址的地理位置 | windows/linux |  |
|  正则提取数据 | 该模块用于使用正则表达式从文本中提取指定格式的数据，可以用于提取如邮箱、URL、IP地址等特定模式的信息 | windows/linux |  |
|  随机字符串生成 | 该模块用于生成指定长度的随机字符串，可用于密码生成、验证码生成等场景 | windows/linux |  |
|  中文转拼音 | 该模块用于将中文文本转换为拼音，以生成用于暴力破解的字典 | windows/linux |  |
|  JSON处理 | 该模块用于对JSON数据进行格式化和美化，提升其可读性，方便查看和调试 | windows/linux |  |
|  UserAgent解析 | 该模块用于解析UserAgent字符串，快速提取设备、操作系统和浏览器等关键信息 | windows/linux |  |
|  文件类型检测 | 该模块用于检测文件类型，快速识别文件的格式和扩展名 | windows/linux |  |
|  谷歌认证码生成 | 该模块用于生成谷歌认证码（Google Authenticator），支持基于时间的一次性密码（TOTP）验证 | windows/linux |  |
|  同形异义字生成 | 该模块用于生成同形异义字，支持替换字符以模拟相似文本变体 | windows/linux |  |
|  二维码解析 | 该模块用于解析二维码，提取其中包含的文本或链接信息 | windows/linux |  |

## 问题列举
1. 在虚拟机里运行, 运行程序显示空白?   
解决方法如下:   
VMware虚拟机->编辑虚拟机设置->显示器->3D图形->取消勾选3D加速图形 

## 使用声明
本工具仅用于安全测试目的   
用于非法用途与开发者无关     
