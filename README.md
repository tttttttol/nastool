脚本特点 ：
1、采取docker方式安装Nas-tools、chinesesubfinder、chinesesubfinder、jackett、qbittorrent依旧

2、脚本支持Rclone一键挂载网盘并实现开机自动挂载（通过systemd实现）

3、通过Gclone获取GD网盘APITOKEN

4、一键反代nas-tools服务（可选nginx或者cloudflared tunnel），其中nginx反代暂时只支持vps环境使用

执行脚本：
 bash <(curl -sL http://ghproxy.com/https://github.com/tttttttol/nastool/blob/main/nas-tools.sh)
