# [subDomainsBrute](https://github.com/lijiejie/subDomainsBrute)

> 本工具用于渗透测试目标域名收集。高并发DNS暴力枚举，发现其他工具无法探测到的域名, 如Google，aizhan，fofa。


- 依赖于Python2/genvent

```bash 
pip install gevent -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install dnspython -i https://pypi.tuna.tsinghua.edu.cn/simple
```

## 使用说明

```
Usage: subDomainsBrute.py [options] target.com

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -f FILE               File contains new line delimited subs, default is
                        subnames.txt.
  --full                Full scan, NAMES FILE subnames_full.txt will be used
                        to brute
  -i, --ignore-intranet
                        Ignore domains pointed to private IPs
  -t THREADS, --threads=THREADS
                        Num of scan threads, 200 by default
  -p PROCESS, --process=PROCESS
                        Num of scan Process, 6 by default
  -o OUTPUT, --output=OUTPUT
                        Output file name. default is {target}.txt
```

## 使用示例
```bash



```