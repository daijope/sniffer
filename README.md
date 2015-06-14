# sniffer
A network sniffer program Based on the libcap

gcc -o sniffex sniffex.c -lpcap

gcc -o ftp ftp.c

gcc -o get get.c

gcc -o rst rst.c

./sniffex eht1 "host 112.74.91.22"

./ftp 112.74.91.22 112.126.64.104

./get 112.74.91.22 112.126.64.104

./rst 112.74.91.22 112.126.64.104 184632080 1276236248  22 43437 

./sniffex eth1 "host 123.56.108.251 and port 80"
