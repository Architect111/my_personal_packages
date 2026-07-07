# my_personal_packages
我的插件包
# quickfile_go
cortexa53/ARM64版打开报错Failed to fetch，提示：当前目录为空或无权限读取
:我还没有兼容 HTTPS，你在设置里auto → 0.0.0.0:8989就可以了，或者 ssh 命令输入
uci set quickfile-go.main.listen_addr='0.0.0.0'
uci set quickfile-go.main.listen_port='8989'
uci commit quickfile-go
/etc/init.d/quickfile-go restart
# vnt
# 撤销所有上游同步，回到上一次稳定提交
git reset --hard HEAD^
# 推送覆盖线上仓库
git push -f
