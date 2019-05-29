# piper-roddy
Share stdout as a web application, oipe stdout from cli-executables to WebSocket server with a web dashboard.

![Screenshot](https://github.com/bitterbit/piper-roddy/raw/master/imgs/screenshot.png)
## Build
``` bash
$ go build cmd/piper.go
$ go build cmd/robby.go
```
## Run
Start server, visit http://localhost:1234/
``` bash
$ ./robby -addr :1234
```

Send data
``` bash
$ echo "a" | ./piper -addr :1234
```

## Demo
![Demo](https://github.com/bitterbit/piper-roddy/raw/master/imgs/demo.gif)
