# gaoke-ssr


$$ From right.com.cn

K2P-A1 with modified Gocloud firmware, including Koolproxy and shadowsockets addin.

1. Flash base-firmware in breed
2. Flash modified Gocloud firmware in admin page 192.168.1.1
3. SSH at 192.168.1.1:22222 with root user
4. Download ss.ipk/Koolproxy.ipk into /tmp
5. opkg update && install koolproxy.ipk ss.ipk
