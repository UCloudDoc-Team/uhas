

# 秘钥云主机的导入

除了密码登录方式，堡垒机对 Linux 主机还支持 SSH Key 秘钥代理登录方式，用户可通 过第三方工具（例如 putty）或 Linux
系统命令 ssh-keygen 生成秘钥对。将生成的公钥导入被管 控主机的登录账户目录下的 authorized\_keys
文件内（如/root/.ssh/authorized\_keys），私钥内容 和私钥对应的 passphrase
填写到堡垒机系统中的资源账户内，如图所示

![](/images/faq_super/秘钥填写.png)
