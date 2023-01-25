# verecl无成本反向代理Jsdelivr
自从 jsdelivr 的备案被吊销后，其在我国大陆地区的速度相较于此前慢了非常多，幸亏有大佬无私分享了他反代的 jsd ，所以我的博客并没有受到太大的影响。
为了保证持续性，建议自建反代

## 部署
fork本项目，并在vercel上部署（因为vercel支持php）

## 使用
访问你解析的域名+该文件名，在后面输入要反代的链接即可。

比如我下面这个链接：

```Code
https://xxx.vercel.app?url=https://cdn.jsdelivr.net/npm/@fancyapps/ui/dist/fancybox.css
```
速度通常在几百毫秒以上，如果一次引入较多可能会拖慢速度
![](https://i0.hdslb.com/bfs/album/35a730ec932282877444e23e9ea70e0e882da03c.png）

#售后服务
可以加Q群671637324，和大家一起交流
