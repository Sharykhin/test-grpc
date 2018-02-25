# test-grpc

Generate grpc interface:
```bash
protoc -I grpc/ grpc/customer.proto --go_out=plugins=grpc:grpc
```