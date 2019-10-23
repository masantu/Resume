{% raw %}<div class="style-example example">{% endraw %}

<br>

<ul class="pure circle center about"><li><img src="/images/imoyao.jpg"></li></ul>

<h3><b><center>马尧 | Python 开发工程师</center></b></h3>
#### <center><i class="fa fa-laptop" aria-hidden="true"></i> 在职，求职中……</center>

<center><p>`4` 年开发工作经验</p></center>

<p style="text-align:center">现就职于<span>[北京鲸鲨软件科技有限公司](http://www.estor.com.cn/)</span></p>


<br>

{% raw %}</div>{% endraw %}

## <i class="fa fa-info"></i> 个人信息

<table><tbody><tr><td>性别</td><td>男</td><td>英语</td><td>CET4</td></tr><tr><td>年龄</td><td>26</td><td>学历</td><td>本科</td></tr></tbody>
</table>


## <i class="fa fa-briefcase"></i> 专业技能

- 熟练 `Python` 语言开发，熟悉语法使用及常用内置库及方法；
- 熟悉 `Flask`、`Web.py`，了解 `Django`、`Tornado` 等 `Web` 开发框架的使用及开发；理解 `RESTful`，熟悉 `Celery` 分布式任务队列框架的使用；
- 熟悉 `MySQL` 关系型数据库，掌握常用 `SQL` 语句的使用以及数据库的设计，熟悉 `Redis` 缓存，了解`MongoDB` 等 `NoSQL` 数据库的应用；
- 熟悉面向对象编程及面向过程编程思想；
- 具有较丰富的云存储开发经验，熟悉块存储、文件存储、网络文件系统等；
- 熟悉 `Linux` 操作系统及常用操作命令、工具以及多线程、多进程系统编程；
- 熟悉 `Linux` 系统的网络通信技术，熟悉 `TCP/IP` 协议以及 `Socket` 编程；
- 熟悉 `HTML`、`CSS`、`Javascript` 前端开发语言，以及 `jQuery`、`Element UI`、`Vuejs` 框架并在项目中实际应用；
- 具备良好的英文文档阅读能力，善于使用 `Stack Overflow` 和搜索引擎解决项目中实际遇到的各种问题；
- 熟悉使用`Nginx`和云服务器部署应用流程； 
- 熟练 `PyCharm`、`Sublime Text`、`Vim` 等编辑器的使用；
- 熟悉 `SVN`、`Git` 等版本控制工具的使用。

## <i class="fas fa-user-tie"></i> 工作经历


### 2017.03 – 至今         <span>|</span>          北京鲸鲨软件科技有限公司           <span>|</span>       云计算研发工程师

#### 工作内容

- 负责公司云平台产品功能实现设计及开发；
- 公司管理系统`Mantis`平台日常`Bug`维护及修复；
- 带领新员工熟悉业务及功能不明确时进行问题分析；
- `Gerrit`平台团队代码评审及日常代码合并；
- 产品数据库设计及优化；
- 开发技术文档的编辑与整理及其他需要临时交付的任务。

### 2015.06 - 2017.02      <span>|</span>          西安桔家软件科技有限公司         <span>|</span>         软件开发工程师   

#### 工作内容

- 负责网站部分数据库的设计，网站后端维护及优化；
- 负责公司产品发布，信息更新及其他后台相关管理工作；
- 配合开发人员做好 `API` 接口开发、对接及简单功能测试；
- 部分技术文档的日常维护及更新。

## <i class="fas fa-award"></i> 项目展示

### 项目名称：生产专用统一测试平台           <span>|</span>        2019.05-2019.08

#### 项目描述

使用 Flask 和 Vue 搭建前后端分离的 `RESTful` 后端管理系统。主要实现设备批量管理，软/硬件信息概览，系统功能，用户登录及设备性能测试等；

**技术关键词**：Flask + Vue + Element UI + Celery + MySQL+ Nginx

**项目模块**

1.系统概览 2.硬件信息概览 3.软件信息配置管理 4.系统工具 5.系统配置 

#### 责任描述

数据库设计及技术选型；使用 `Linux` 平台管理工具实现硬件信息获取并使用 `Celery` 定时任务保存到数据库，通过异步任务处理前端下发的指令并返回结果进行页面展示。

### 项目名称：虚拟化云存储高可用双控管理系统     <span>|</span>                 2017.03-至今

#### 项目描述

使用 `Web.py` 搭建支持块存储/文件存储的管理系统。可实现管理磁盘/磁盘阵列功能以及 `LVM` 权限/配额管理功能。基于 `RBAC` 实现访问控制，`IPSAN` 和 `FCSAN` 可选协议构建灵活的 `SAN` 存储网络，基于 `NFS` 和 `SAMBA` 搭建 `NAS` 服务。利用 `DRBD` 实现数据远端备份，`HA` 技术实现主备双活，提高系统可靠性及可用性。`Rsync` 实现备份。

**技术关键词**：Web.py + RAID + IPSAN + FCSAN + DRBD + HA + wxPython

**项目模块**    

1.系统概览 2.网络设置 3.磁盘管理 4.磁盘管理 5.`NAS` 管理 6.`SAN` 管理 7.系统工具 8.报警设置 9.日志管理 10.用户权限管理 11.远程镜像等；

#### 责任描述

使用 `DRBD` 开发实现数据容灾，支持主备热切换以及数据镜像备份与恢复；实现基于 `RBAC` 的权限管理模块的数据库设计、前端界面及后端逻辑代码编写及功能测试；日常 `bug` 修复及模块功能调优；新功能的需求分析，帮助新组员理解业务功能以及对较难实现的部分进行功能分析及复杂问题拆分；技术文档的整理及完善。
<fancybox>
![1.PNG](/images/estor/Snipaste_2019-09-26_21-31-02.png)&nbsp;
![2.PNG](/images/estor/Snipaste_2019-09-26_21-36-10.png)&nbsp;
![3.PNG](/images/estor/Snipaste_2019-09-26_21-40-07.png)&nbsp;
![4.PNG](/images/estor/Snipaste_2019-09-26_21-40-55.png)&nbsp;
![5.PNG](/images/estor/Snipaste_2019-09-26_21-41-43.png)&nbsp;
![6.PNG](/images/estor/Snipaste_2019-09-26_21-42-28.png)
</fancybox>

<figcaption> **注意**：以上图片仅供项目展示，所有权利归原公司所有 </figcaption>

### 项目名称：`O2O` 钟点房预订系统            <span>|</span>                    2015.07-2017.01

#### 项目描述

后端使用 `Django` 及 `Tornado` 框架为用户精准呈现实时房屋信息并实现酒店预订功能，为商户提供房源信息发布和订单管理功能。使用第三方接口实现商品图片信息存储以及图片验证码+短信验证码实现用户的注册验证，`MySQL` 数据库存储并使用 `Redis` 缓存热点数据，使用 `Whoosh` 全文检索引擎实现商品搜索功能，服务端使用 `Nginx` 反向代理实现部署。

**技术关键词**：Django + MySQL + Nginx + Redis + Bootstrap + 七牛云存储

**项目模块**

1.用户管理模块 2.房屋信息维护与展示模块 3.房屋信息检索与预订模块 4.订单管理模块 5.房屋评论系统

**责任描述**

参与前期数据库结构的设计，并使用第三方接口实现用户注册短信验证码验证及用户信息登记，完成用户登录及个人信息管理;负责实现各详细分类下的具体商品按照查询条件排序展示、商品列表页分页以及 `Redis` 缓存实现数据存储优化，从而实现商品列表的快速展示，配合前端完成接口对接与协调开发。

## <i class="fab fa-github"></i> 开源贡献

### 使用 `Vue` 和 `Flask` 搭建前后端分离的 `RESTful` 个人博客

### 主要功能

- 博文管理（创建、更新、删除）以及不同方式的展示（分类、归档、标签）；
- 用户认证（注册、登录、找回密码）；
- 基于百度翻译`API`的文章`slug`生成；
- 基于`Celery`的邮件发送以及博客数据的备份（异步任务及定时任务）；
- 云服务器部署等。

[`IdealYard`项目源码](https://github.com/imoyao/idealyard)  
[线上预览地址](http://140.143.249.136/)

<fancybox>
![IdealYard](/images/blog-overview.jpg)
</fancybox>


## <i class="fa fa-edit"></i> 博客交流

- [别院牧志](https://imoyao.github.io/)

## <i class="fas fa-user-graduate"></i> 教育背景

**2011.09 - 2015.06             河南工业大学               本科-自动化**

## <i class="fas fa-phone-alt"></i> 与我联系

<i class="fas fa-envelope fa-fw"></i> imsantu.ma@gmail.com

<p></p>

更多联系方式请在`Python interpreter`中运行以下代码获取：
```python
import base64


def no_disturbance_if_you_do_not_mean_that(str_info):
    ret = eval(base64.b64decode(str_info))
    return ret
    
if __name__ == '__main__':
    hard_read = b'eyJRUSI6IjQ0NTU2Nzg4OSIsInBob25lIjoiMTgyMzY5NTY3ODYiLCJlbWFpbCI6Imltc2FudHUubWFAZ21haWwuY29tIiwid2VjaGF0IjoiaW1veWFvIn0='
    
    print(no_disturbance_if_you_do_not_mean_that(hard_read))
```

## <i class="fa fa-info-circle"></i> 自我评价

本人熟练使用 `Python` 语言进行编程开发，代码风格遵守 `PEP8` 编码规范及[`Google`开源项目风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/contents/)，致力于写出 `Pythonic` 的代码，热爱开源文化。具备较强的逻辑思维和良好的沟通能力；善于团队合作协调开发并推动项目的顺利进行。希望通过学习新知识提高自我，具备较强的书面表达和文档编写能力。工作上具有拼搏进取精神，敢于挑战自我，拥有良好的职业素养和较强的工作抗压能力。

<br><br><br><br>
<center>**十分感谢您百忙之中抽出时间查看我的简历，希望有幸能与您共事！**</center>
