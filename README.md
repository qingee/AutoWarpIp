# AutoWarpIp
全自动切换到可以解锁奈飞ip脚本


1、全自动切换到可以解锁奈飞ip脚本

curl -fsSL -o AutoWarpIp.sh  https://raw.githubusercontent.com/qingee/AutoWarpIp/master/AutoWarpIp.sh && chmod +x AutoWarpIp.sh && clear && ./AutoWarpIp.sh
2、添加crontab脚本任务

crontab -e
* */1 * * * /bin/bash /root/AutoWarpIp.sh
