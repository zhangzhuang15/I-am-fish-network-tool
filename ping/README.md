## ping解决的问题
* 判断网络是否通畅

---

## 用法
`ping -4 bilibili.com`
用ipv4向bilibili.com发送4个ping包
> MacOS不支持，请在linux上实验;
> 同理 -6 就是走ipv6;

`ping -c 4 bilibili.com`
向bilibili.com发送4个ping包
效果：
> ![](./ping_c.png)