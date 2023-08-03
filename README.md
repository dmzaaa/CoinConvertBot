<p align="center"><img src="wiki/imgs/logo.png" width="150"></p>

<p align="center">
<a href="https://www.gnu.org/licenses/gpl-3.0.html"><img src="https://img.shields.io/badge/license-GPLV3-blue" alt="license GPLV3"></a>
<a href="https://www.php.net/releases/7_4_0.php"><img src="https://img.shields.io/badge/.NET-6-orange" alt=".net6"></a>
<a href="https://t.me//UU_TRX1"><img src="https://img.shields.io/badge/官方频道-@UU_TRX1-blue" alt="官方频道：@UU_TRX1"></a>
<a href="https://t.me/UUTRXBot"><img src="https://img.shields.io/badge/官方Bot-@UUTRXBot-blue" alt="官方机器人：@UUTRXBot"></a>
</p>

## 兑币机 - Telegram Bot

>一款开源自动化USDT兑换TRX的Telegram机器人！



## AD -- 机器人推广


USDT、TRX交易监控机器人：[USDT、TRX交易监控](https://t.me/UUTRXBot)
> 监控波场地址余额变化，速度比钱包App的推送更快！！！

兑币机 - TRX自动兑换：[兑币机](https://t.me/UUTRXbot)
> 自用兑币机，并不是开源版机器人！！！



## 项目简介
- `UUTRXbot`是一个由`C#语言`编写的私有化部署`USDT-TRC20`全自动兑换`TRX`的机器人。     
- 本项目不依赖任何外部资源，无需另外部署`数据库`，采用轻量化的`sqlite`，也无需`redis`。
- 可实现`USDT-TRC20`入账指定地址，自动向转账地址回款`TRX`，全程无需人工干预！😊 😊 😊
- 私有化搭建使得您的私钥🔑安全无比，同时USDT代币直接进入您的钱包💰
- `UUTRXBot` 遵守 [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) 开源协议!

## 项目特点
- 支持私有化部署，无需担心钱包被盗😁
- `C#语言`跨平台实现，支持x86和arm芯片架构的win/linux/mac设备
- 支持配置多个入账钱包地址，提高资金安全性
- 无需额外环境配置，仅运行一个编译后二进制文件即可使用
- `Telegram`大平台，更多客户，更便捷的使用和快速通知

## 项目结构
```
CoinConvertBot
    ├── src ---> (项目核心目录）
    └── wiki ---> (知识库)
```




## 加入交流/意见反馈
- 交流群组[https://t.me/UU_TRX1](https://t.me/UU_TRX1)

## 设计实现
`CoinConvertBot`的实现方式与其他项目原理类似，都是通过监听`TRC20`网络的api或节点，      
监听钱包地址`USDT`代币入账事件，将入账金额，根据汇率，扣除手续费后，转换为`TRX`
```
支持：自动预支 （可设定条件：是否TG会员，历史兑换记录大于多少，钱包余额大于多少 - 下次兑换时扣除）

支持：手动预支 （管理员给指定钱包地址进行预支trx - 下次兑换时扣除）

支持：手动闪兑 （给钱包补充TRX）

支持：自动群发广告（每个群可以设定不一样的广告内容 - 支持图片）

支持：进群自动欢迎语 （每个群支持不同欢迎内容 - 支持图片）

支持：群内发送z0 查看 当前OTC币价

支持：群内发送任意TG用户名 如：@gd801  查询用户名信息 ID等 [测试版功能 - 稳定性可能不好]

支持：群内用户修改昵称监听(以防修改管理员同款昵称 行骗等)
```





## 声明
`UUTRXBot`为开源的产品，仅用于学习交流使用！       
不可用于任何违反中华人民共和国(含台湾省)或使用者所在地区法律法规的用途。           
因为作者即本人仅完成代码的开发和开源活动(开源即任何人都可以下载使用或修改分发)，从未参与用户的任何运营和盈利活动。       
且不知晓用户后续将程序源代码用于何种用途，故用户使用过程中所带来的任何法律责任即由用户自己承担。            
```
！！！Warning！！！
项目中所涉及区块链代币均为学习用途，作者并不赞成区块链所繁衍出代币的金融属性
亦不鼓励和支持任何"挖矿"，"炒币"，"虚拟币ICO"等非法行为
虚拟币市场行为不受监管要求和控制，投资交易需谨慎，仅供学习区块链知识
```
[![Stargazers over time](https://starchart.cc/LightCountry/CoinConvertBot.svg)](https://starchart.cc/LightCountry/CoinConvertBot)
