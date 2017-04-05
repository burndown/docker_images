## HOW TO USE

```
docker run -e FASTOPEN='' -e UDP='' -e KCP_NOCOMP=--nocomp --net=host endoffight/shadowsocks-kcp
```
ENV 
SS_SERVER_ADDR=0.0.0.0 \
SS_SERVER_PORT=3721 \
SS_PASSWORD=laogao \
SS_METHOD=aes-256-cfb \
SS_TIMEOUT=300 \
SS_FASTOPEN=--fast-open \
SS_UDP_RELAY=-u \
SS_USER=nobody \
SS_DNS_ADDR=8.8.8.8 \
SS_DNS_ADDR_2=8.8.4.4


ENV 
KCP_LISTEN=3824 \
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
