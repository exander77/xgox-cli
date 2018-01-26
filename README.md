xgox-cli
===========

The missing command line interface for xgoxd using RPC.

```
sudo npm install -g xgox-cli
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
