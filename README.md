# efficiency_work(高效工作整理)

## Xcode 
* 我常用的代码片段 替换路径：open ~/Library/Developer/Xcode/UserData/CodeSnippets （内容见当前目录）
* Xcode 插件：https://github.com/guohongwei719/GHWXcodeExtension
## VSCode 
* settings.json（内容见当前目录）
* 好用的扩展1： Draw.io Integration （scan.drawio.png）

## 常用命令整理

### 在指定时间关机：
```
sudo shutdown -h 10:55                                  
```
### 环境变量修改：
```
open ~/.bash_profile
source ~/.bash_profile

open ~/.zshrc
source ~/.zshrc
```

### zsh
```
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
export PATH=/Users/liaoshaolin/flutter_sdk/1.22.2/bin:$PATH
```

### 查看环境变量值
```
echo $HOME
echo $PATH
```
### 杀掉所有 dart 进程：
```
killall - dart
```
### 终端科学上网测试
```
curl google.com
curl myip.ipip.net
```
### git 邮箱、用户名 查看与修改
```
git config user.email
git config user.name

git config --global user.name 'helloDolin'
git config --global user.email '366688603@qq.com'

git config user.name 'helloDolin'
git config user.email '366688603@qq.com'
(当你想针对特定项目使用不同的用户名称与邮件地址时，可以在那个项目目录下运 行没有 --global 选项的命令来配置。)
```

### 查看 git 配置
```
git config --list


```
### mac finder 支持webp预览
```
curl -L https://raw.github.com/emin/WebPQuickLook/master/install-all.sh | sh
```
### 显示隐藏文件
```
// 显示隐藏文件
defaults write com.apple.finder AppleShowAllFiles Yes && killall Finder 
//不显示隐藏文件
defaults write com.apple.finder AppleShowAllFiles No && killall Finder 
```


