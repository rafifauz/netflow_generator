# Netflow Random Generator
### Install Golang(New Version) https://golang.org/doc/install
```
wget https://golang.org/dl/go1.17.2.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
go version
cd Skripsi/nflow-generator-a/
CGO_ENABLED=0 go build
```

### cd nflow-generator
```
./main -t [IP_Logstash] -p [PORT_yang_akan_dibaca] -f
```

#### Contoh:
```
./main -t 46.137.229.166 -p 2055 -f
```
