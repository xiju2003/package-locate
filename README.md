# 食用说明

### 简单介绍
定位网卡中的每个数据包的所属进程以及进程名
```
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x00\x00\x00\x00\x00\x00'
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x00d\xcc\xd9\xf2"\xf7\xd7`\xa8\xc5)x\xa1S\xb6n\x14\x80\xf7'
2018-11-06 17:52:26 - WARNING -   root[line:97] - (('192.168.11.107', 22), ('192.168.11.93', 57720)) - 11783 - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'KEx\xefw\x87\x9622\nSD\xe1\xc9\xdd\x90\xe5\xb9jC'
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x00\x00\x00\x00\x00\x00'
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\xf7\xee\xc4\xa1BO\x11\xb2\\\xc2\xb2$\rOL\x12\xfa\xf4!\xaa'
2018-11-06 17:52:26 - WARNING -   root[line:97] - (('192.168.11.107', 22), ('192.168.11.93', 57720)) - 11783 - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x0e\xea\xaa;\xe9c\xfb~;46\xb8\xdc\x8d-\xb7\xb6\x8f0\x1c'
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x00\x00\x00\x00\x00\x00'
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x8f\t\xe6e\x9b\xbaa\xfdI\xf82\xe5\x86\xd7\x0c\xb2\xf8\x07WQ'
2018-11-06 17:52:26 - WARNING -   root[line:97] - (('192.168.11.107', 22), ('192.168.11.93', 57720)) - 11783 - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'!\xb5\xa7R\x0c\xaf\x15T\xa4\r|q\x0enJo\x96\xd1\xaaj'
2018-11-06 17:52:26 - WARNING -   root[line:102] - (('192.168.11.93', 57720), ('192.168.11.107', 22)) - 11783  - sshd -['sshd: arm@pts/0', '', '', '', '', ''] - arm - b'\x00\x00\x00\x00\x00\x00'
```
### 环境
python 3
psutil

### 使用说明
两种模式
RUN模式:
```
  python3 main.py run
```

DEBUG 模式
```
python3 main.py
```
