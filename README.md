<h1 align="center">灵芝 🎉🎉🎉</h1>

> 一款交互式应用安全评估工具（被动式）

## 一、简介
1.灵芝IAST属于被动式IAST，不需要重放数据包，不产生脏数据；

2.被动式IAST具有近实时检测、高检出率、低误报率、低漏报率等特点；理论上可以实现0误报，但是，在复杂场景下，会出现污点链路不准确、误报等情况，尤其是使用了自定义的过滤函数



## 二、🚀 灵芝极速体验
- 第一步：获取`IAST-TOKEN`
- 第二步：部署AGENT并启动WEB应用

#### 获取IAST-TOKEN
##### 1.注册成为火线白帽
访问[火线官网](https://www.huoxian.club/#/index)进行注册

##### 2.访问火器获取
登录火线后，访问“火器-灵芝IAST”，点击“下载安装灵芝”即可看到“IAST Token”

![get_iast_token](doc/assets/tutorial/get_iast_token.gif)

#### 部署AGENT
方式1：没有Java环境，想试试，那就访问[【火器】“灵芝IAST”交互式应用安全测试工具使用姿势](https://mp.weixin.qq.com/s/VRZE5eRfjGK66yyTK4UkbA) 查看快速使用姿势吧

方式2：有环境，有WEB应用，可以前往release下载agent.jar，然后配置`IAST-Token`使用



## 三、检测能力

#### 社区版安全风险检测能力

- [x] 命令执行
- [x] SQL注入，支持常见数据库的sql注入检测，包括mysql、mssql等
- [x] LDAP注入
- [x] SMTP注入
- [x] XPATH注入
- [x] EL表达式注入
- [x] Hql注入
- [x] NoSql注入
- [x] header头注入
- [x] XXE
- [x] 不安全的readline
- [x] 不安全的重定向
- [x] 不安全的转发
- [x] 路径穿越
- [x] 弱加密算法
- [x] 弱哈希算法
- [x] 弱随机数算法
- [x] 信任边界
- [x] Cookie未设置secure

#### 社区版安全风险待补充的列表

- [ ] 反射注入
- [ ] 第三方组件收集及漏洞检测



## 四、问答区
#### 1.火线平台地址是什么？

https://www.huoxian.club/#/index

#### 2.火线注册邀请码怎么获得？

方式1：提交src的漏洞，在漏洞标题中注名“火线”，然后拿截图联系火大表姐兑换

方式2：向火大表姐投稿一片技术文章，包括挖洞姿势、渗透测试、漏洞分析等

方式3：联系火线平台的表哥购买，火线平台邀请码99个查克拉

方式4：前往评论区联系🔥表弟

#### 3.灵芝IAST只支持Linux吗？

Windows也支持的哦，Windows下的使用教程正在赶来的路上，表哥们喝杯咖啡先～

#### 4.灵芝支持Dubbo、微服务吗？

IAST与框架本身无关，理论上只要在节点上都安装agent就可以支持，但是，只有经过充分的测试才可以对外公布，所以，暂时不支持，分布式框架测试的已在排期中，表哥等等弟弟

如果表哥有任何疑问，请前往讨论区联系火表弟，火表弟会及时的给表哥解答疑惑。



## 五、贡献一波😏
1.贡献Agent的报错信息；

2.贡献不兼容的操作系统、JDK版本、第三方框架/组件；

3.贡献第三方框架的过滤函数；

4.贡献好的想法，请前往讨论区，添加表弟微信进行反馈，表弟帮你实现它💪💪💪

[贡献榜]()



## 六、讨论区
1.Github issue: https://github.com/huoxianclub/LingZhi/issues

2.微信群：需要邀请码或想进群交流的表哥们，请扫描二维码加🔥表弟的个人微信，表弟会把大家拉进技术交流群

![看不到图片了吗？微信搜索“owefsad”试试啦](doc/assets/aboutus/wechat.jpeg)