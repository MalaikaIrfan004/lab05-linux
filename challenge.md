Question 1
Answer: malaikairfan004, /home/malaikairfan004/lab05-linux
Commands: whoami, pwd

Question 2
Answer: ubuntu, PRETTY_NAME="Ubuntu 26.04.1 LTS"
NAME="Ubuntu"
Commands: hostname, cat /etc/os-release | head -2

Question 3
Answer: 1.6Gb, 2.4G
Commands: free -h, df -h /

Question 4
Answer: root:x:0:0:root:/root:/bin/bash
malaikairfan004:x:1000:1000:Malaika Irfan:/home/malaikairfan004:/bin/bash
Command: `grep '/bin/bash' /etc/passwd`

Question 5
Answer: 241
Command: `ps aux | wc -l`

Question 6: lab5user Creation and Deletion Times
Answer: The first creation was recorded at 2026-10-16 04:35:59 UTC, and the first deletion >
Command: sudo grep lab5user /var/log/auth.log
