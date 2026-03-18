# Discord


1. 前提：Discord 账号、管理权限的服务器
2. 前往 [Discord 开发者门户](https://discord.com/developers/home) → 应用 → 新建应用
![](Pasted%20image%2020260318015402.png)

3. 进入应用，在“Bot”部分：添加Bot，然后复制机器人令牌(Bot token)，添加到产品页面，并填写目标 Server ID 和 Channel ID 

![](Pasted%20image%2020260318015134.png)

![](Pasted%20image%2020260318015147.png)


4. 在 Bot → Privileged Gateway Intents 中启用 Message Content Intent 和 Server Members Intent
![](Pasted%20image%2020260318015231.png)

5. 在 OAuth2 → URL Generator：选择 "bot" + "applications.commands"，添加"Send Messages"权限
![](Pasted%20image%2020260318015243.png)

6. 使用生成的 URL 邀请机器人加入您的服务器
![](Pasted%20image%2020260318015258.png)








