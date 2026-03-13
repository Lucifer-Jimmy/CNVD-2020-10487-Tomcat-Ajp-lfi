# CNVD-2020-10487-Tomcat-Ajp-lfi
Tomcat-Ajp 协议文件读取漏洞以及文件包含漏洞，可以执行服务器的 jsp 文件。

```bash
usage: CNVD-2020-10487-Tomcat-Ajp-lfi.py [-h] [-p PORT] [-f FILE] [-e] target

positional arguments:
  target                Hostname or IP to attack

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  AJP port to attack (default is 8009)
  -f FILE, --file FILE  file path :(WEB-INF/web.xml)
  -e, --eval            Execute jsp
```

