# filter_knife
HoshinoBot PCR筛刀插件



安装方法和其他插件一样

安装完了要修改yobot_url为自己的机器人网页URL，还有DB_PATH修改为自己的yobot出刀数据库路径

上边两个参数和会战报告插件的一样





### 公会战筛刀插件指令

开始筛刀-----------------清空以前的筛刀数据

筛刀 伤害值 @群友---把筛刀数据报给机器人，如果手里有多个账号可以用@代报，自己的筛刀不需要@

筛刀信息-----------------显示现在的筛刀信息

结算 编号----------------提醒筛刀信息里某人结算出刀，编号是筛刀信息里的编号

结束筛刀-----------------清空当前筛刀数据

筛刀帮助-----------------查看帮助

注意筛刀信息没有做持久化，如果筛刀过程中机器人重启会丢失当前筛刀数据

筛刀时会读取出刀数据获取boss当前生命值，所以当前公会战至少要报过一刀有出刀数据才行

注意新创建的公会有时候会获取不到apikey
