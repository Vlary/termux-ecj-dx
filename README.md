# termux-ecj-dx
Termux搭建简单java环境的shell脚本
## 搭建
安装基本软件
```
pkg install ecj dx termux-tools
```
克隆termux-ecj-dx
```
git clone https://github.com/Vlary/termux-ecj-dx.git
```
在任意位置可用
```
cd termux-ecj-dx
mv java /data/data/com.termux/files/usr/bin/java
```
## 使用
例
```
java HelloWorld.java
```
