
## Replit容器部署xray核心代理
### 详见[视频教程](https://www.youtube.com/playlist?list=PLMgly2AulGG-peT3CZoJFY68KbVg_D_lB)
-----------------------------------------------------------------------------------
### 提示：新建项目名称勿出现xray/v2ray等任何的协议字样，大流量使用必被限制！
### 2023.4.4更新：
#### 0、恢复replit官方平台在线fork功能，每run一次，自动拉取脚本更新哦！[项目地址](https://replit.com/@ygkkkk?tab=repls)，怎么操作？不用说了吧？

1、分享网页链接格式：replit域名地址/变量uuid值.html

2、伪装网页默认为随机，可设置www变量指定伪装网页（取值范围1-9）

3、分享页面中的三大协议支持一键复制链接

4、加入苹果oneclick免费客户端支持，须设置ver变量，值为任意字符，此时xray版本为1.4.3

--------------------------------------------------------------------------------

### 本地上传操作流程：

点击首页右上角蓝色加号New Repl，搜索模版：Blank Repl，随意输入项目名称Title（不要出现代理协议的任何字眼），点击创建Create Repl，然后下载Github备份地址中的压缩文件（vmvltrssso-nginx-pro），并解压。再把解压后的4个文件全部拖到左侧文件栏内进行覆盖，等待几十秒后提示覆盖点确定，最后点击RUN

--------------------------------------------------------------------------------------------
#### 以下变量都为非必选变量，按需求添加（点击replit左侧Tools ，选择Secrets，详见教程）

| 变量含义 | 变量名称| 变量规范值| 不添加该变量名称时，最终默认结果|
| :--- | :--- | :--- | :--- |
| 各协议uuid或密码 | uuid |可在V2raN上随机生成，或者自定义uuid格式|随机生成的uuid|
| 伪装网页 | www |数字1-9任选一个数字，共9个伪装网页可选择|随机伪装网页|
|Xray1.4.3版支持苹果oneclick免费客户端|ver|任意字符|自动安装最新版Xray|
|更新中……|更新中……|更新中……|更新中……|


----------------------------------------------------------------------------------------------------
![682aec9151f00ed0cba7e8c8026ff06](https://user-images.githubusercontent.com/121604513/229277596-6d6bfcd4-2f91-42d3-8ebd-e27cbe9619a1.png)
![7682b5d1e8862ca8d1e119122e02c73](https://user-images.githubusercontent.com/121604513/229277602-f6311191-1044-4612-bdad-d45230462a31.png)
![799d196f38533f309f049e8bb480533](https://user-images.githubusercontent.com/121604513/229277603-c17c8bef-d85c-4bc3-91d9-e73949913ede.png)



### 参考项目：[hiifeng](https://github.com/hiifeng/V2ray-for-Replit)
