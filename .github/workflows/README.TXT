# 自动更新脚本
# 后续新增插件只需要修改一处
- name: 批量同步配置（在这里填你所有插件）
        run: |
          # 数组格式：插件目录名=上游仓库地址
          declare -A plugin_list=(
            ["luci-app-quickfile-go"]="https://github.com/home16668/luci-app-quickfile-go"
            ["luci-app-vnt"]="此处替换成VNT的上游git地址"
          )
