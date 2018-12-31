# UseFulCommand

#Setting a proxy for Windows using the command-line
netsh winhttp set proxy proxy-server="socks=localhost:9090" bypass-list="localhost"
netsh winhttp show proxy
netsh winhttp reset proxy
