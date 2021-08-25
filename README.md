# docker_final_using


docker run -ti --user root -p 10022:22   -p  8081:8081  -v /home/troila/log:/mnt   --restart=always cd8876bb979e    /bin/bash  


进入docker 
python3 informateion_extract_server.py 

然后输入ctrl+p+q 退出即可. 或者直接关闭xshell也行. docker自己会维护好服务.
