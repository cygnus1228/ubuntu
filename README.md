[MarsLUL视频](https://www.bilibili.com/video/BV1t54y1R7F3)

[VirtualBox官网下载](https://www.virtualbox.org/wiki/Downloads)

[Ubuntu下载](https://cn.ubuntu.com/desktop)

[VSCode官网下载](https://code.visualstudio.com/)

## ubuntu-20.04百度云
```
链接：https://pan.baidu.com/s/1Re8pyPzFPQKXbqT2p3HRYA 
提取码：9o77 
```

```
备用秒传链接：77fc715a283e41d0ad33d6418a9ba128#447f275659e9840ecd754d5bd9a9a157#2785017856#ubuntu-20.04.1-desktop-amd64.iso
```
[安装秒传链接插件](https://www.userscript.zone/search?q=%E7%A7%92%E4%BC%A0%E9%93%BE%E6%8E%A5)
# VirtualBox所需代码
## 设备-安装增强功能
## 打开双向剪切板
```Ctrl+Shift+C  复制```

```Ctrl+Shift+V  粘贴```
## 替换镜像源
###### 复制文件
```sudo cp /etc/apt/sources.list /etc/apt/sources_backup.list```
###### 打开文件
```sudo nano /etc/apt/sources.list```

```Ctrl+shift+6进入选择模式，长按方向键下进行全选，Ctrl+K删除全部内容，Ctrl+X退出```

[Ubuntu软件源](https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/)

###### 更新软件源
```sudo apt update```
###### 安装软件
```sudo apt install curl git openssh-server net-tools```
## 安装 oh-my-zsh
###### 方法一
```
sudo apt install -y zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
###### 方法二
```
sudo apt install -y zsh
sh -c "$(curl -fsSL https://gitee.com/shmhlsy/oh-my-zsh-install.sh/raw/master/install.sh)"
```
###### 方法三
###### 检查是否安装zsh
```zsh --version```
###### 安装zsh
```sudo apt install zsh```
###### 将zsh设为默认
```chsh -s $(which zsh)```
###### 克隆储存库
```git clone https://github.com/ohmyzsh/ohmyzsh.git ~/.oh-my-zsh```
###### 创建一个新的zsh配置文件
```cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc```
###### 更换shell
```chsh -s $(which zsh)```
###### 重启可用

[Mars](https://github.com/MarsWang42/My-Vim-Conf)

## 下载他的仓库
```git clone https://github.com/MarsWang42/My-Vim-Conf.git```
## 进入仓库文件夹
```cd My-Vim-Conf```
## 设置他的系统
```
chmod +x ./setup.sh ./tmux.sh
./setup.sh
```
## 应用更改
```source ~/.zshrc```
