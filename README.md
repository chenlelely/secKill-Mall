## 高并发商城秒杀系统

## 项目描述
1. 使用分布式Seesion，让多台服务器可以响应。
2. 使用redis做缓存提高访问速度和并发量，减少数据库压力。
3. 使用页面静态化，缓存页面至浏览器，前后端分离降低服务器压力。
4. 使用消息队列完成异步下单，提升用户体验，削峰和降流。
5. 安全性优化：双重md5密码校验，秒杀接口地址的隐藏，接口限流防刷，数学公式验证码。

## 图片演示
登录页面

![Image text](https://github.com/pitt1997/miaosha_idea/blob/master/showimgs/login.png)

商品列表页面

![Image text](https://github.com/pitt1997/miaosha_idea/blob/master/showimgs/list.png)

商品详情页面

![Image text](https://github.com/pitt1997/miaosha_idea/blob/master/showimgs/goodsdetail.png)

商品秒杀倒计时

![Image text](https://github.com/pitt1997/miaosha_idea/blob/master/showimgs/wait.png)

成功秒杀页面

![Image text](https://github.com/pitt1997/miaosha_idea/blob/master/showimgs/miaoshasuccess.png)


