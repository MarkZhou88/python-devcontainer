## Just Fun

### 启用github copilot插件提示
安装插件，点击图标启用
copilot小技巧，就是输入“//q: XXXX”可以向copilot询问有关代码的问题，然后按下回车他就会回答"//a: XXX"来回答你
//q: Bytebuffer合并数组
//a: bytes.Join([][]byte{b1, b2}, []byte{})

#### 操作系统
AlpineLinux

#### 切换root用户
sudo -i

### chatgpt

#### 安装go
apk add go

#### 设置环境变量
export OPENAI_API_KEY=xxx
查看是否生效
env | grep OPENAI_API_KEY

#### 到持久化目录，这个目录在codespaces停止不会被删除
cd /workspaces
git clone https://github.com/j178/chatgpt.git
cd chatgpt
go run cmd/main.go

### 安装管理软件

#### 进程查看
apk add procs

#### htop
apk add htop

#### vim
apk add vim

#### bat
apk add bat

#### 安装neofetch
apk add neofetch


### 检查网络
#### 工程地址: https://github.com/yeahwu/check
wget -qO- https://github.com/yeahwu/check/raw/main/check.sh | bash
