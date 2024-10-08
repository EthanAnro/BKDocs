## 订阅配置

用户个性化的设置，允许用户根据自己的需求，预先定义一套仪表盘的订阅条件；当满足这些条件时，系统会通过截图功能自动发送订阅通知给用户，从而实现定时查看仪表盘内容的目的；简而言之，订阅配置就是用户自定义的一套规则，用来决定何时接收哪些仪表盘的通知；

![Subscribe-to-push](../media/Subscribe-to-push.png)

### 新建订阅

![New-subscription-them](../media/New-subscription-theme.png)

点击 **`新建`** — 进入「新建订阅主题」页面

![New-subscription-theme1](../media/New-subscription-theme1.png)

![New-subscription-theme2](../media/New-subscription-theme2.png)

1. **订阅信息填写**

**基础信息**：填写订阅主题即推送名称和推送的仪表盘;

​        **`订阅主题`**：即推送名称，在列表中可以直接查询和展示；

​        **`推送的仪表盘`**：选择要推送的仪表盘；

​        **`版本`**：可选择不同版本号进行推送，默认为latest；

​        **`图片宽度`**：因为利用截图功能将仪表盘某一时刻截图进行推送，所以图片提供4中宽度选择分别为1920px、1440px、1366px和1280px选择；

**参数配置**：用户可在参数配置中看到要推送的仪表盘上已配置的所有交互组件，用户可自定义筛选数据，最后截图服务会在参数配置之后进行仪表盘的截图；

**推送规则**：用户可自定义选择推送的模式、渠道及收件人信息;

​          **`推送模式`**：分为 **`一次性`** 和  **`周期性`**，紧随其后设置相应的发送时间点；

​          **`推送渠道`**：分为 **`邮件`** 和  **`企微`**，支持多选；

​                 **`邮件`**：BKVision通过官方或个人邮箱推送订阅件给一个或多个人

​                            `邮件标题`：填写推送邮件的标题，使得接收人一目了然；

​                            `收件人`：填写推送接收人，支持人名自动联想，支持多选；

​                            `密送人`：密送人只能看到自己，无法看到其他收件或密送人；

​                            `附带PDF附件`：支持仪表盘截图以PDF形式发送；

​                  **`企微`**：BKVision通过官方企微号推送订阅件给个人

​                             `收件人`：选择推送接收人，支持人名查找，支持多选；

​                             `额外信息`：可填写对该仪表盘的描述等内容一起发送；

​                  **`企微群聊`**：用户将BKVision官方机器人加到群聊中接收订阅件

​                             `群聊会话ID`：填写企业微信的群聊会话ID，支持多个，逗号分隔；

​                             `额外信息`：可填写对该仪表盘的描述等内容一起发送的文本内容；


2. **推送预览**：当选定推送仪表盘之后，即可在右侧推送预览中展示仪表盘，确保无误；


3. **操作栏**：

​          `提交`：保存并启动当前订阅项

​          `测试推送`：按当前订阅项的配置推送个当前用户，测试推送的最终效果

​          `取消`：清空并退出本次订阅配置