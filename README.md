# Web应用版晨间日记 时间管理工具

## 出发点
晨间日记是个人成长的非常好的工具，自己曾使用Excel版的，然后转到了印象笔记版，但还是发现比较繁琐，每天都得复制一套模板更改信息然后才能记录。于是产生了写此Web应用版的。

## 功能
1 简洁实用，最大化的方便自己的记录，每天打开网页即能记录自己的成长。

2 图形化自己的历史记录，记录累计天数，增加自己的成就感及坚持的动力。

3 可以一眼看到一年来自己的记录情况，自由浏览一年来的记录。

4 成长记录保存到当地数据库，只有自己可以查看自己的历史记录。

5 可进行富文本的编辑（例如截图中的G编辑框）。

## 开发环境
Python2.7 + Django1.8.4

## 截图
版块是按照明日-昨日-今日的顺序，提醒理想，回顾反省昨天，把握今天

<img src="https://raw.githubusercontent.com/lanbing510/GTDWeb/master/screenshots/Diray.png" width="100%" height="100%">

## 使用说明
1 安装Python，将python.exe所在目录加入系统环境变量。

2 下载后建议放到D盘（即manage.py的路径为 D:/GTDWeb/manage.py)，如放置其他位置，更改Michael/Micheal/setting.py中的路径即可。

3 运行runserver.bat后再浏览器中输入127.0.0.1:8000/diary/ 即可进行记录。建议设置runserver.bat为开机启动。

4 Ctrl+M可以快捷的在记录项中进行切换。

5 周计划版块会在新的一周进行清空提醒编辑，月和年版块类似，中途需要修改计划双击后进行编辑即可。

6 感兴趣的可以自己开发添加更多功能。


## 其他
本Web应用是自己两周时间内自学Django和JavaScript等知识进行的编写，欢迎大家的意见和反馈。

有时间再编写其他的时间管理Web应用。


不可用于商业用途。
