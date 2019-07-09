{{indexmenu_n>2}}

# 架构和原理简介

## 堡垒机架构简介

### 一、公有云架构

![](/images/architecture01.png)

利用UHAS管理中小型企业在商业云上租用的资源。

### 二、托管云架构

![](/images/architecture02.png)

可利用UHAS管理企业托管的服务器、网络设备。

## 堡垒机原理简介

运维审计系统（堡垒机）是UCloud推出的一款主机安全内控产品，为用户提供了一套运维管理解决方案，使得管理人员可以对云主机进行集中账号管理、细粒度的权限管理和审计，帮助用户提升风险内控水平。

![](/images/principle.png)

使用堡垒机之前，用户直接登录主机进行管理和控制。使用堡垒机之后，用户登录主机之前需要先登录堡垒机，堡垒机将记录用户对主机所有的操作，并将这些操作返回给管理员。管理员可以查看任何用户的操作历史，然后根据这些操作进行追责或者提出整改要求。

![](/images/before_after.png)