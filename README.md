# linux_cmd

# 杀死进程名称中包含keyword的所有进程
ps aux|grep keyword|awk '{print $2}'|xargs kill -9
