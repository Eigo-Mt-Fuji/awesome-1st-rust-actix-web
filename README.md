# README 

## About 

- Hello world of rust actix-web.

## How to run

- start server

```
cargo run
```

- open hello web

```
curl -v http://127.0.0.1:8080/hello/eigo
```

## Note

- [20181220 - QiitaのRust Advent Calendar 2018 20日目 - actix_web は Actorモデルでどのようにwebリクエストを捌いているのか / Actor model](https://x1.inkenkun.com/archives/5890)

## Note: install python client

```
wget https://github.com/protocolbuffers/protobuf/releases/download/v3.11.2/protobuf-python-3.11.2.zip
unzip protobuf-python-3.11.2.zip
cd protobuf-3.11.2/python/
python3 setup.py install
pip3 install --upgrade pip
pip3 install aiohttp
```

