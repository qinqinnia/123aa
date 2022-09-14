**从任何平台过来的朋友们请先阅读此说明！**

# 每日早安推送给别人家的女朋友

这里有[更新说明](./UPGRADE.md)

## 使用说明

在我刚想构思这个教程怎么让不懂编程的朋友很快入门的时候，我考虑到：避免服务器搭建，避免定时任务，避免接触代码。在经历过各种思考后，觉得可以用 Github Actions 来白嫖。。

效果如图。当然，文字是可以修改的。
<img src="https://github.com/1012015643/daily_morning/blob/master/img/img_1.jpg" width="300px" />

首先，按图搜索，测试号，进来之后微信扫码登录！
<img width="1471" src="https://github.com/1012015643/daily_morning/blob/master/img/img_2.png" width="300px" />

按图点击 Fork，创建到自己的仓库下！
<img width="1471" alt="image" src="https://github.com/1012015643/morning/blob/master/img/img_3-1.png">

按下图，创建模板，设置变量，把微信公众平台上的各种字符串按说明创建到 GitHub -> Settings -> Secrets -> Actions 中。
![71bf9d11a876d23ef0f0728645a8ba0](https://github.com/1012015643/daily_morning/blob/master/img/img_4.png)
![381e8ee4a7c5ec6b8c09719f2c7e486](https://github.com/1012015643/daily_morning/blob/master/img/img_5.png)
![48c60750cec7adc546e0ad99e3082b3](https://github.com/1012015643/daily_morning/blob/master/img/img_6.png)
![48c60750cec7adc546e0ad99e3082b3](https://github.com/1012015643/daily_morning/blob/master/img/img_7.png)

启用自己项目下的 Action！
![30a5b1b2b06ba4a40a3d8ef01652409](https://github.com/1012015643/daily_morning/blob/master/img/img_9.png)

如果运行出现错误，按以下方法可以看到错误，在这里 issue 提问也可以，在抖音粉丝群里问也可以
![6b0da6f44e18c2bfd94910c377d13e6](https://github.com/1012015643/daily_morning/blob/master/img/img_10.png)

启用后可以直接运行，看看女朋友的手机有没有收到推送吧！
这个定时任务是每天早晨8点推送，如果会编程的同学可以自己自定义一些东西～

图中的操作，除了各种英文字符串不一样，模板消息中的中文不一样，其他的应该都是一样的，不然程序跑不通的～

Github 的右上角可以点击 star 给我点鼓励吧亲

抖音上点点关注，点点赞，有什么好玩的东西可以at我，我来教你们做

ps. 有一些注意事项在此补充

1. 第一次登录微信公众平台测试号给的 app secret 是错误的，刷新一下页面即可
2. 生日的日期格式是：`05-20`，纪念日的格式是 `2022-08-09`，请注意区分。城市请写到地级市，比如：`北京`，`广州`，`承德`
3. 变量中粘贴的各种英文字符串不要有空格，不要有换行，除了模板之外都没有换行
4. Github Actions 的定时任务，在 workflow 的定义是 `0 0 * * *`，是 UTC 时间的零点，北京时间的八点。但是由于 Github 同一时间任务太多，因此会有延迟
5. 我会偶尔优化一下代码，emm 但现在我自己在做一个完整的平台项目，想让大家更加便捷地上手

## 自我推广

<img src="https://github.com/1012015643/daily_morning/blob/master/img/img.jpg" width="300px" />

如果觉得这个项目对你有用，欢迎给我买杯咖啡

