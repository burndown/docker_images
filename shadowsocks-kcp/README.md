## HOW TO USE

```
docker run -e FASTOPEN='' -e UDP='' -e KCP_NOCOMP=--nocomp --net=host endoffight/shadowsocks-kcp
```
ENV SERVER_ADDR=0.0.0.0 \
SERVER_PORT=3721 \
PASSWORD=laogao \
METHOD=aes-256-cfb \
TIMEOUT=300 \
FASTOPEN=--fast-open \
UDP_RELAY=-u \
USER=nobody \
DNS_ADDR=8.8.8.8 \
DNS_ADDR_2=8.8.4.4


ENV KCP_LISTEN=3824 \
KCP_PASS=phpgao \
KCP_ENCRYPT=aes-192 \
KCP_MODE=fast \
KCP_MUT=1350 \
KCP_NOCOMP=''

## UPDATE_LOG

20170322：

 1. ADD MORE ENV
 2. SS RUNs IN nobody
 3. UPDATE server_linux_amd64 TO v20170315
