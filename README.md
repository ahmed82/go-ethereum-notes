# go-ethereum

https://geth.ethereum.org/downloads/

https://geth.ethereum.org/docs/install-and-build/installing-geth

```
docker pull ethereum/client-go
docker run -it -p 30303:30303 ethereum/client-go
```

## install make & gcc
```
sudo apt-get install build-essential
```

## c compiler gcc not found
```
download MinGW on http://www.mingw.org/
install on basic package Gcc-g++ (see this image)
add on environment Patch of windows variables.
restart and continue with "go get ..."
```
