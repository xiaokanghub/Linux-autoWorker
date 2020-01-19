# Linux-autoWorker
Linux 服务开机自启动
将service文件放入/usr/lib/systemd/system目录下
chmod +x apache.service
# 启动服务
systemctl enable apache
systemctl start apache
# 关闭服务
systemctl stop apache
systemctl disable apache
