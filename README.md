# UrlChecker
![](assets/16407561223312.jpg)

>原项目地址：https://github.com/Ifonly-go2019/UrlChecker 

不过这个GitHub账号我已经弃用了

![](https://cdn.jsdelivr.net/gh/ifonly-go2019/PicGo//images/20201012225747.png)


this is a tool to detect the Web service is ok or not.

写这个小jio本的目的是，在大量子域名或者URL的情况下，不想人为去点每个URL去判断系统正常。虽然有很多大型扫描器有这个功能，比如Xray 的html 导出，但是我就是想写一下。后面慢慢加功能。
## Base on http response status code

200、404、403、500、405

## Multithreading

![](https://cdn.jsdelivr.net/gh/ifonly-go2019/PicGo//images/20201012224014.png)


## TODO

- Output results
- Count the number of OK
- colorful terminal strings 😂

## questions & contact 

https://hack-for.fun/

## Update

- 2021年12月29日。修改默认线程数为10，如果需要修改，可以在代码中修改`max_connections`

