xgox-cli
===========

The missing command line interface for xgoxd using RPC. It is written in NodeJS, so you need to have NPM and NodeJS installed.

```
sudo npm install -g xgox-cli
```

```
npm install
./bin/xgox-cli getbalance
```

# Usage

```
xgox-cli [args] method arguments
```

## Arguments:

* `--host` or `-h`: Define xgoxd host
* `--port` or `-p`: Define xgoxd port
* `--rpcuser`: Define rpc username
* `--rpcpassword`: Define rpc password

If `rpcuser` and `rpcpassword` are not defined, the client will try to get them from `~/.xgox/xgox.conf`.

# License

MIT
