# Helloworld Service

This is the Helloworld service

Generated with

```
micro new helloworld
```

## Usage

Generate the proto code

```
brew install protobuf
go get github.com/golang/protobuf/protoc-gen-go
go get github.com/micro/micro/v3/cmd/protoc-gen-micro
go build github.com/golang/protobuf/protoc-gen-go
go build github.com/micro/micro/v3/cmd/protoc-gen-micro
cp protoc-* ~/bin/
make proto
```

Run the service

```
micro run .
```