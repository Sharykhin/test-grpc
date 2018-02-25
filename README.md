# test-grpc

Generate grpc interface:
```bash
protoc -I grpc/ grpc/customer.proto --go_out=plugins=grpc:grpc
```

Usage:
```bash
cd server && go run main.go
cd client && go run main.go
```

Origin source:
https://medium.com/@shijuvar/building-high-performance-apis-in-go-using-grpc-and-protocol-buffers-2eda5b80771b
