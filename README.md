HearthStone
===========

HearthStone C#

Q.HearthStone无法编译
A.HearthStone是使用了vNext的ASP.NET项目，Package没有放入Git进行管理

Q.如果我想修改一些资料，怎么办？
A.打开【卡牌整理版本.xls】文件，然后按照需求进行修改，然后运行【卡牌资料生成】工具


Q.我想部署在局域网内
A.将Client.HTML里面的WebSocket里面的 1.0.0.127 改为你的局域网服务器地址即可。

Q.套牌的设置
A.这个版本中可以使用的套牌是写死的，你可以在game.js里面看到一个套牌的字符串，你可以自己修改。

Q.Github代码的编译
A.从GitHub上面取下来的代码，可以直接编译，由于项目使用了一些第三方DLL，
所以，如果出现问题，请自行添加DLL引用，这些DLL放在了DLL文件夹下面了。
