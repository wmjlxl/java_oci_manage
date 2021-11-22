目前为公测版本。

一些说明:
使用前请使用 sudo chmod +x sh_java_oci.sh 进行授权
脚本默认为当前目录读取jar 也可接自定义jar包路径（如：bash java_oci.sh /root/xxxx/xxx.jar）
后台运行请执行 screen -S java_oci bash sh_java_oci.sh
查看后台运行情况 screen -r
编辑本脚本的 begin 和 end之间的参数进行开机设定（不开机填不填无影响）

两种使用方式:
1.
  1）下载压缩包 解压文件 tar -zxvf xxx.tar.gz 
  2）sudo chmod +x sh_java_oci.sh
  3）运行 bash sh_java_oci.sh
2.一键运行（运行完后使用bash java_oci.sh可再次运行）
  wget -O linux-oci.tar.gz https://github.com/semicons/java_oci_manage/releases/download/first/linux-oci-1.0.0.tar.gz && tar -zxvf linux-oci.tar.gz && sudo chmod +x   sh_java_oci.sh && ./sh_java_oci.sh
