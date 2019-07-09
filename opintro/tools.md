{{indexmenu_n>2}}

# 连接工具

## 连接工具下载安装

默认的ssh工具为putty，可以切换为secureCRT，secureCRT为未注册版本。

![](/images/default.png)

### 1\. Windows客户端

首次登录堡垒机，点击右上角的【工具下载】，下载并安装连接工具，安装目录为Ucenter，进程为rest-server。

    需启动该进程，建议设置为开机自动启动。

使用过旧版连接工具的用户，在安装新版前需卸载旧版，卸载步骤：

  - 1)关闭rest-server进程；
  - 2)使用Ucenter文件夹的Unins000卸载，或直接使用Windows【程序和功能】进行卸载；
  - 3)删除Ucenter文件夹。

Windows连接工具包括：

  - 1)RDP的远程桌面连接；
  - 2)SSH可选Putty或SecureCRT（需自行激活）；文件传输工具WinSCP。

<wrap
em>注意：2016年12月22日前使用的运维审计系统，Windows客户端用户需下载安装新的连接工具，Mac客户端用户无需改变</wrap>

### 2\. Mac客户端

首次登录堡垒机，点击右上角的【工具下载】，下载连接工具，并移动UrmScheme到"应用程序（Application）"文件夹。

此处应注意，查看mac设置-安全性与隐私-允许从以下位置下载的应用，此处需选择中级别【允许Mac App
Store和被认可的开发者】，因为连接工具不是App
Store下载的，是UCloud自研和签名认证。

使用过旧版连接工具的用户，在安装新版前需卸载旧版，卸载步骤：删除【应用程序】文件夹的UrmScheme程序。

Mac连接工具包括：

  - 1)RDP的远程桌面连接；
  - 2)SSH可选Mac终端或SecureCRT（需自行激活）；文件传输工具FileZilla。
