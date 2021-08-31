2个文件都放在DLAAS平台中，比如/workspace/Groupshare中
# 拷贝配置文件
cp config.json /root/.mc/config.json 
# 查看网盘中的文件
./mc ls s3-ai/ch-videos-smtc/
# 复制文件到可操作目录
./mc cp s3-ai/ch-videos-smtc/freespace2020.tar.gz /workspace/LocalCache/
