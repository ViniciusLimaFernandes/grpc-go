# gRPC-GO
A simple application using gRPC to learn more about the tool.

  Links:
  
  [Protocol buffers](https://developers.google.com/protocol-buffers)
  
  [gRPC](https://grpc.io)

## Prerequisites
```$ sudo apt-get install autoconf automake libtool curl make g++ unzip```

  ### Installation
  1. From [this page](https://github.com/protocolbuffers/protobuf/releases/tag/v3.6.1), download the ```protobuf-all-[VERSION].tar.gz```.
  2. Extract the contents and change in the directory
  3. ```./configure```
  4. ```make```
  5. ```make check```
  6. ```sudo make install```
  7. ```sudo ldconfig ```.
  
  
  ## Build / Generate
  To generate the proto file use the following command: 
  ```$ protoc -I=${source folder name} --go_out=plugins=grpc:${output folder} ${proto file path} ```

