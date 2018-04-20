以E:EGo1为例说明如何在命令界面进入文件夹
    1.通过“开始->所有程序->附件->命令提示符”进入命令界面。
    2.输入“E:”，然后按下Enter进入E盘。
    3.输入“cd EGo1”，按下Enter后即可进入EGo1文件夹中。


以工程在E:\EGo1为例说明如何安装并运行程序，生成html文档
    1.通过软件管家安装python。（注：需要在Add Python x.x to PATH前打对勾，x.x为安装版本号，例如我安装的为3.6）
    2.通过“开始->所有程序->附件->命令提示符”进入命令界面。
    3.输入“python”，然后按下Enter即可看到python信息。
    4.安装pip；pip的下载地址为：https://pypi.python.org/pypi/pip#downloads，然后左击pip-9.0.1.tar.gz即可下载。
      下载完成后，解压到D盘，重新打开命令界面，然后进入pip-9.0.1文件夹，输入“python setup.py install”,按下
      Enter后即可开始安装pip。
    5.输入“pip”，然后按下Enther即可看到pip信息。
    6.重新打开命令界面，输入“pip install sphinx”，然后按下Enter，开始安装sphinx。
    7.在命令界面进入E盘，然后输入“mkdir EGo1”，按下Enter即可生成EGo1文件夹。
    8.在命令界面进入EGo1文件夹，然后输入“sphinx-quickstart”,按下Enter后会进入一个设置向导，根据向导一步一步
      设置文档项目，其中必填项只有项目名称、作者和版本其他设置都可以一路回车（建议语言设置为“zh_CN”，是简体
      中文的意思），到最后会生成一堆东西，包括conf.py和make等。
    9.根据需要修改conf.py。
    10.编写rst文件，比如默认的index,rst或链接的rst文件。
    11.在命令界面输入“make html”，按下Enter后会看到build目录下生成了html格式的文档。
    12.双击E:\EGo1\build\html目录下的index即可打开生成的html文档。
    13.修改conf.py或者rst文件后，重新操作步骤11即可生成新的html文档。
    
