# Requests mirror server
Mirroring your requests

### Install

fetching with git:
```sh
git clone https://github.com/DsXack/requests-mirror-server.git
```

or fetching with `go get`
```sh
go get github.com/DsXack/requests-mirror-server
```

### Running

running without params:
```sh
requests-mirror-server
Start listen 8000 port for requests
```

running with params:
```sh
PORT=7000 requests-mirror-server
Start listen 7000 port for requests
```

### Make requests:
```sh
curl http://localhost:7000/test_path

GET /test_path HTTP/1.1
Host: localhost:7000
Accept: */*
User-Agent: curl/7.43.0
```
