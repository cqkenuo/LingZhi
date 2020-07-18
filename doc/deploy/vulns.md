> 为了快速体验IAST的漏洞检测效果，我们将逐步提供不同类型的测试用例，用于更快的进行测试。

| 漏洞类型 | docker地址 |
|  ----  | ----  |
| 命令执行/路径穿越/OGNL代码执行 | owef/iast-demo01:v3 |

靶场将逐步完善，欢迎表哥提供优秀的Java靶场地址，靶场通过审核后，表弟将为表哥奉上查克拉。

#### iast-demo01快速接入
1.安装并启动docker

2.拉取最新的容器：`docker pull owef/iast-demo01:v3`

3.启动容器：`docker run -itd -p 8080:8080 --name iast-demo01 owef/iast-demo01:v3`

4.访问靶场地址：
- [命令执行](http://localhost:8080/iast-test01/cmd.jsp?cmd=id)
- [OGNL代码执行](http://localhost:8080/iast-test01/ognl.jsp?exp=T(java.lang.Runtime).getRuntime().exec(%27whoami%27))
- [SQL注入](http://localhost:8080/iast-test01/sql.jsp?page=1&page_size=10)
