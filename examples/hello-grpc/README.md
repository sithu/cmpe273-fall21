# How to compile IDL

```sh
python3 -m grpc_tools.protoc -Iprotos --python_out=. --grpc_python_out=. protos/helloworld.proto
```

## Run Server

```sh
python3 greeter_server.py
```

## Run Client

```sh
python3 greeter_client.py
```