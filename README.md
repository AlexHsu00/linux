# linux
## grep
#### 基本語法
```
grep 關鍵字 檔案1 檔案2 ...
```
#### 在 /etc/os-release 檔案中搜尋 Ubuntu 關鍵字
```
grep Ubuntu /etc/os-release
```
#### 在 /etc/*.conf 中搜尋 network 關鍵字
```
grep network /etc/*.conf
```
#### 篩選含有 network 關鍵字的檔案名稱
```
ls /etc/ | grep network
```
#### 不分大小寫 -i
```
grep -i Ubuntu /etc/os-release
```
#### 標示行號
```
grep -n Ubuntu /etc/os-release
```
#### -r 遞迴，在 /etc/ 下所有檔案中搜尋 ubuntu 
```
grep -r ubuntu /etc/
```
https://blog.gtwang.org/linux/linux-grep-command-tutorial-examples/

https://juejin.cn/post/6844903586128723981

## find
```
find -iname log -type d
```

## 背景執行
nohup ../../bin/standalone.sh > /dev/null 2>&1 &



