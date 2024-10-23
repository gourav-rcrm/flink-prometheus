```
go mod init flink-prometheus

go get github.com/Sirupsen/logrus
go get github.com/matsumana/flink_exporter/exporter
go get github.com/prometheus/client_golang/prometheus
go get gopkg.in/urfave/cli.v2


go run main.go --port 9160 --log-level debug --flink-job-manager-url http://localhost:8081


```
