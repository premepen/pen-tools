# [dnsmaper](https://github.com/le4f/dnsmaper)
> dns枚举工具



## 使用说明
```
[root@localhost dnsmaper]# python ./dnsmaper.py -h

 ____  _   _ ____  __  __
|  _ \| \ | / ___||  \/  | __ _ _ __   ___ _ __
| | | |  \| \___ \| |\/| |/ _` | '_ \ / _ \ '__|
| |_| | |\  |___) | |  | | (_| | |_) |  __/ |
|____/|_| \_|____/|_|  |_|\__,_| .__/ \___|_|
                               |_|
 =# Author: le4f.net
 =# Mail  : le4f#xdsec.org

Usage: dnsmaper.py [options] target

Options:
  -h, --help            show this help message and exit
  -c THREAD_COUNT, --thread_count=THREAD_COUNT
                        [optional]number of lookup theads,default=17
  -s SUBS, --subs=SUBS  (optional)list of subdomains,  default='./db/subs.db'
  -r RESOLVERS, --resolvers=RESOLVERS
                        (optional)list of DNS
                        resolvers,default='./db/resolvers.db'
```