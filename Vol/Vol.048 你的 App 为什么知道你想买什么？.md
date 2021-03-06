# Vol.048 你的 App 为什么知道你想买什么？

数字生活让人疑神疑鬼。

淘宝当然不会窃听你的电话，是你的行为数据让淘宝意识到了你需要婴儿奶粉。

注册一个账号，你需要输入自己的名字，手机号，有时候还会补充性

更重要的，是你的消费记录，打车频率，关注的公众号，玩过的游戏，理财习惯

采集事实标签并不难，难的是建立模型，从杂乱的标签中找到你真正的兴趣，进而构建用户画像。

举个例子，你打开一篇内容标签为美女的文章，并不意味着你真的爱看美女，可能只是不小心点到。这时，就需

这是一个非常初级的内容标签权重算法：

> 行为权重：什么都不干1分，评论+0.5，点赞+0.5，转发+2，收藏+1

> 衰减因子：0-3天内权重为1，3-7天权重为0.85，7-15天权重为0.7，15-30天权重为0.5，30天以上权重为0.1

![img](https://mmbiz.qpic.cn/mmbiz_gif/U6yR

![img](https://paperclip.host/static/U6yRaDu1NaaaU49HA2sB5gZVYaK1ZMuz3zVjgQKFG1HCQdNonaC4U1zxVicSIs1OoCONr0ge2VGPRGDlgElu9qg.gif)

数值越高，你对美女就越感兴趣。

除了内容兴趣，这种算法思路可以在消费能力，消费兴趣，社交习惯等多个维度建立模型，计算你的偏好。

![img](https://paperclip.host/static/U6yRaDu1NaaaU49HA2sB5gZVYaK1ZMuz84a9UicPr3P3QmiaH5vtJfzZrfn37k1vc6wCPElbE0HWBTBOgfcbicnhA.png)

但行为数据只能计算偏好，无法判断你的性别、学历等个人属性。

这就需要把已知性别和学历的用户作为样本，一部分用来训练模型，一部分测试准确度。今天各大平台对于用户性别的预测准确度已经可以达到90%以上。

这是腾讯广告投放平台的后台。广告主可以自由组合包含消费水平、婚恋情况、内容兴趣，消费行为在内的上千个定向标签供，最后选定广告位和投放时间，根据系统计算的 1.5 元每千次曝光的建议出价，就完成了一次精准投放。

之后，一个住在北京朝阳有过奶粉消费记录的已婚男青年在即将刷到广告位的那一瞬间，广告平台会发起竞价请求，最后

如果你对这个话题感兴趣，可以在腾讯广告平台的开发者文档，进一步了解你的行为数据被处理到了什么样的程度，比如筛选出“ 2017.7.1 至 2017.7.15 去过上海机场 3 次以上的人”。

另外，通过行为推荐商品的效果往往不如通过同类推荐商品。找到和你一样的人，把他们的的浏览和消费记录推荐给你，往往比直接猜你喜欢什么效果更好。

需要说明的是，微信淘宝们采集的

这意味着， 你就算不注册不登录，你的行为数据一样会被采集。

同时，广告平台也可以根据你的手机识别码在其他 App 上为你投放广告，这样，你刷抖音的时候也能

别太紧张，根据《个人信息安全规范》，商业广告平台的所有标签都应该避免精确定位到个人，以保护你的隐私安全 。

![img](https://paperclip.host/static/U6yRaDu1NaaaU49HA2sB5gZVYaK1ZMuzpjvd3xwgTMQQZXrJibbOt38Nd6OzAVys7mYd94L1TJTTtk2qK3Sj8xg.gif)

!!! note "该文件编辑日志"

	* 	Mar 29, 2020.
		By [parozhao](https://github.com/parozhao)
	
			创建文件 & Markdown 格式化
