# MocaPic-on-HoshinoBot
基于HoshinoBot的mocaBot图库功能插件

## 安装与部署

#### 首先你需要正确安装并运行HoshinoBot
关于HoshinoBot的详情见https://github.com/Ice-Cirno/HoshinoBot

确保您的Q群机器人已经能够正常运行，对于HoshinoBot相关的安装部署问题请在其页面寻找解决方案。

#### 安装本插件
可以直接用git clone或者在浏览器上下载本项目代码。

将mocapic整个文件夹及其文件放入HoshinoBot\hoshino\modules目录下。

把HoshinoBot\hoshino\config下的__bot__.py打开，MODULES_ON中添加一项'mocapic'并保存。

重启HoshinoBot


## 使用指令
#### 来点【lp名】

例如：来点伊藤彩沙

Bot会发送对应图片一张
#### 多来点【lp名】

例如：多来点进藤天音

Bot会以合并形式发送对应图片三张

## 昵称关键字说明

LP们的别称均写入在.py文件中的nick_name字典中。

~~由于本人不够D~~，并没有实现丰富的昵称，建议发送全称呼唤LP。

如果有想要被识别的昵称可以自行添加。

**注意！在实际使用中发现即便QQ发送繁体字，插件接收到的也是对应简体，若人名中有繁体字，一定要设置对应的简体昵称。**


## 致谢

本插件使用的图片来源均为 https://image.mocabot.cn/

非常感谢mocaBot的开发者准备了这样一份~~DD~~宝库

同样感谢[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)项目以及[go-cqhttp](https://github.com/Mrs4s/go-cqhttp)项目
