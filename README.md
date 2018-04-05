# Newton-Blockchain-Explorer
Block explorer for Newton CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon newtond. It should be accessible from the Internet. Run newtond with open port as follows:
```bash
./newtond --enable-cors=* --enable-blockexplorer --rpc-bind-ip 0.0.0.0 --rpc-bind-port 21236
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
