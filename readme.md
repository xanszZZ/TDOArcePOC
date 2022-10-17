## TDOArcePOC

通达OA v11.9 getdata接口存在任意命令执行漏洞，攻击者通过漏洞可以执行服务器任意命令控制服务器权限

## 安装

```
git clone https://github.com/xanszZZ/TDOArcePOC
cd TDOArcePOC
```

## 使用

因为本工具是根据pocsuite3框架的开发规范编写的poc

在使用前请下载pocsuite3

项目地址

```
https://github.com/knownsec/pocsuite3
```

环境

```
Python 3.7+
Works on Linux, Windows, Mac OSX, BSD, etc.
```

pip安装

```
pip3 install pocsuite3

# use other pypi mirror
pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple pocsuite3
```

poc

```
pocsuite -r pocs/TDOArcePOC.py -f xxx.txt
```



## 免责声明🧐

本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建测试环境。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。