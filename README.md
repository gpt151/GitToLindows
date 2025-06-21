<h1 align="center">GitToLindows<br />
<div align="center">
<a href="https://github.com/dockur/windows"><img src="https://github.com/dockur/windows/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>

# 禁止滥用，封了不能怪我


# 在github跑windows/linux!!!

1. 主要思路就是通过 Github Codespaces功能创建一个 blank template 的 codespace，它是一个 Debian或Ubuntu 虚拟机，在这个虚拟机中可以执行 docker-compose -f 配置文件 up 创建一个 Windows/linux 的容器，可以通过端口转发的链接（设置成 public）来访问。

2. 一键启动默认是windows7系统

3. 在指令的"配置文件"可以换成w10.yml或者w11.yml，或者其他系统配置文件

4. 当然，也可以选择 Win11/win10 之外其他的操作系统或软件的容器。比如，搭建一个网站，一个笔记系统等。

# 开始教程(使用)
1. 先登录你的github账号
2. 并拉取本项目
3. 然后点击绿色按钮(Code)
4. 右边的Codepaces
5. 然后点击下面的小加号(+)
6. 等待进入(这个是进入linux环境)
7. 在终端这一行输入指令
8. docker-compose -f "配置文件" up
9. 然后等待，有个端口转发
10. 点击8006端口对应的链接网址
11. 恭喜你完成这次的操作了
12. 等待即可食用windows/linux

# linux系统启动方法
1. 部署好后，新建终端
2. 输入bash start系统.sh
- 比如：
- debian：bash startdeb.sh
- centos：bash startcen.sh

# 支持的系统：
  
  | **Value** | **Version**            | **Size** |
  |---|---|---|
  | `11`   | Windows 11 Pro            | 5.4 GB   |
  ||||
  | `10`   | Windows 10 Pro            | 5.7 GB   |
  ||||
  | `8`   | Windows 8.1 Enterprise    | 3.7 GB   |
  | `7`   | Windows 7 Ultimate        | 3.1 GB   |
  | `vista`   | Windows Vista Ultimate    | 3.0 GB   |
  | `xp`   | Windows XP Professional   | 0.6 GB   |
  | `2000`   | Windows 2000 Professional | 0.4 GB   | 
  ||||  
  | `2022` | Windows Server 2022       | 4.7 GB   |
  | `2019` | Windows Server 2019       | 5.3 GB   |
  | `2016` | Windows Server 2016       | 6.5 GB   |
  | `2012` | Windows Server 2012       | 4.3 GB   |
  |||| 
  | `debian` | debian       | 未知   |
  | `centos` | centos       | 未知   |
  | `macos` | macos       | 未知   |

# 这么做的好处是：
1. 获得免费的 VPS 虚拟机
2. 这个 Windows/linux  容器规格比较大
3. 没有臃肿的预置软件
4. 网络访问没有限制
5. 网速特别快
6. 可以使用 Copilot AI

