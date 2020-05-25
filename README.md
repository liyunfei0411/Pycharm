# Pycharm
官网 ：https://www.jetbrains.com/pycharm/download/index.html#section=windows
不同版本下载：https://www.jetbrains.com/pycharm/download/previous.html

我的安装的是： 2018.2.8
(不同版本对后来的激活有影响，在使用2018.3.5 / 2019.1.2 版本上 并不能激活成功)

安装完成 不要打开直接关闭。
1. 载下来后，将补丁copy至Pycharm安装目录的bin目录下



2.在Pycharm安装目录的bin目录中找到pycharm.exe.vmoptions和pycharm64.exe.vmoptions 这两个文件，用记事本打开，在文件最后追加一行内容：-javaagent:Pycharm安装路径\bin\JetbrainsCrack-release-enc.jar，最后记得保存退出。

例如我的安装路径是：D:\Program Files\JetBrains\PyCharm 2018.3.5

所以添加内容为：-javaagent:D:\Program Files\JetBrains\PyCharm 2018.3.5\bin\JetbrainsCrack-release-enc.jar


3.打开Pycharm，选择激活码激活，将下面的内容拷贝到激活框内，点击ok

ThisCrackLicenseId-{

“licenseId”:”11011”,

“licenseeName”:”Wechat”,

“assigneeName”:”Naked sleep of pig”,

“assigneeEmail”:”1113449881@qq.com”,

“licenseRestriction”:””,

“checkConcurrentUse”:false,

“products”:[

{“code”:”II”,”paidUpTo”:”2099-12-31”},

{“code”:”DM”,”paidUpTo”:”2099-12-31”},

{“code”:”AC”,”paidUpTo”:”2099-12-31”},

{“code”:”RS0”,”paidUpTo”:”2099-12-31”},

{“code”:”WS”,”paidUpTo”:”2099-12-31”},

{“code”:”DPN”,”paidUpTo”:”2099-12-31”},

{“code”:”RC”,”paidUpTo”:”2099-12-31”},

{“code”:”PS”,”paidUpTo”:”2099-12-31”},

{“code”:”DC”,”paidUpTo”:”2099-12-31”},

{“code”:”RM”,”paidUpTo”:”2099-12-31”},

{“code”:”CL”,”paidUpTo”:”2099-12-31”},

{“code”:”PC”,”paidUpTo”:”2099-12-31”}

],

“hash”:”2911276/0”,

“gracePeriodDays”:7,

“autoProlongated”:false}



到这里就算是激活成功了，我们可以在pycharm主菜单页面，点击“Help-About”查看激活信息。
