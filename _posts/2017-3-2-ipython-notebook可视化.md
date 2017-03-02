##### 用ipython notebook来实现在本机上可视化

- 配置密码证书等配置文件
- error Support for specifying --pylab on the command line has been removed.
- 密码：sha1:70823265982e:640b9dca5300cb52b4127c23655ea4d6d3715e45


ipython notebook --profile=nbserver --certfile=/home/zm/.jupyter/mycert.pem

[reference](http://mindonmind.github.io/2013/02/08/ipython-notebook-interactive-computing-new-era/#本地运行)

```
ssh zm@192.168.1.2 -L127.0.0.1:1234:127.0.0.1:8888
```