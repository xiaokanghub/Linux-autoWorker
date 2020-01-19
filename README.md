# Linux-autoWorker
Linux 服务开机自启动\n
将service文件放入/usr/lib/systemd/system目录下\n
chmod +x apache.service\n
# 启动服务
systemctl enable apache\n
systemctl start apache\n
# 关闭服务
systemctl stop apache\n
systemctl disable apache\n
