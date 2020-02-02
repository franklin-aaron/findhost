# findhost
Look up domain names via IP

＃只支持windows

使用方式：
  选项：
          -host        域名、IP地址
          -p           查询旁站
          -c           查询整个C段
          -t           调用查询接口的超时时间,默认5秒
          -m           最大线程数,默认线程数为1,最大限制为30,建议设置到20
          -o           保存域名到到指定的文档
  Example:
          findhost.exe -host www.xxx.xom -p /**查询旁站域名**/
          findhost.exe -host www.xxx.com -c -m 20 /**查询C段域名**/
          findhost.exe -host www.xxx.com -c -m 20 -o d:\hosts.txt

不得使用在非法途径!所产生的法律风险与本人无关！
