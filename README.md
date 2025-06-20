在github跑windows!!!

主要思路就是通过 Github Codespaces功能创建一个 blank template 的 codespace，它是一个 Debian或Ubuntu 虚拟机，在这个虚拟机中可以执行 docker-compose -f win11.yml up 创建一个 Win11 的容器，可以通过端口转发的链接（设置成 public）来访问。

当然，也可以选择 Win11 之外其他的操作系统或软件的容器。比如，搭建一个网站，一个笔记系统等。

这么做的好处是：
获得免费的 VPS 虚拟机
这个 Win11  容器规格比较大
没有臃肿的预置软件
网络访问没有限制
网速特别快
可以使用 Copilot AI

