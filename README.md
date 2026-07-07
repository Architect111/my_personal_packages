# my_personal_packages
我的插件包
# quickfile_go
我还没有兼容 HTTPS，你在设置里auto → 0.0.0.0:8989就可以了，或者 ssh 命令输入
uci set quickfile-go.main.listen_addr='0.0.0.0'
uci set quickfile-go.main.listen_port='8989'
uci commit quickfile-go
/etc/init.d/quickfile-go restart
