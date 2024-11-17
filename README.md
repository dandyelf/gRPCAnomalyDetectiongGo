# gRPCAnomalyDetectiongGo
Anomaly detection from a normal distribution with gRPC and log on postgres db.

![variant1](images/normald.png)

Cli start with flags: -port -k -s -pgconf\
  "port", 8888, "Server port" \
  "k", 2.0, "Anomaly coefficient" \
  "s", false, "Table setup" \
  "pgconf", "postgres://postgres:123@localhost:5432/postgres?sslmode=disable", "Postgres address" \

Server start with: -port \
"port", 8888, "The server port" \
