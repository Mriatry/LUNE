mkdir /linux
touch /hello.txt
cp /hello.txt /linux/1.txt
rm /hello.txt
mkdir -p /home/headless
echo 'Hello,Linux!' > /home/headless/test.txt
touch /root/oldFile1 /root/oldFile2 /root/oldFile3 /root/oldFile4
chmod u=x /root/oldFile1       # 所有者权限设为可执行
chmod g-r /root/oldFile2       # 同组删除可读
chmod o+x /root/oldFile3       # 其他组添加可执行
chmod u=r,g=w,o=x /root/oldFile4  # 所有者可读/同组可写/其他可执行