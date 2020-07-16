# httptosocks
将SOCKS5代理转换为HTTP

编译:

    go build

使用:

    httptosocks -laddr <http-proxy (127.0.0.1:8080)> -raddr <socks-proxy (127.0.0.1:1080)>

