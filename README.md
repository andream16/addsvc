# How to use

Go inside addsvc:
 - Run `go get -v`. If you get errors, just fetch proper vendors. Use glide if needed.
 - Run it with `go run addsvc.go`
Go inside addcli:
 - Run `go get -v`. If you get errors, just fetch proper vendors. Use glide if needed.
 - Run it with:
   - gRPC: `go run addcli.go -grpc-addr :8082 -method concat/sum x y` > `xy or x + y`
   - http: `go run addcli.go -http-addr :8081/sum 1 2` > `1 + 2 = 3`

