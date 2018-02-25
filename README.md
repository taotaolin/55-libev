## debian55-libev-obfs-net-speeder

Shadowsocks-libev Docker 

## Start

```
docker run -d --name 55-libev -p {port:port} ramiko/55-libev-obfs-with-net-speeder -s 0.0.0.0 -p {port} -k {ramiko} -m {aes-256-cfb} --plugin obfs-server --plugin-opts {"obfs=tls"}

```

# {XXXX} is ENV