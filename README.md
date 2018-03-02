# tokhn
Alternative blockchain written in Java

Requires Bouncy Castle

There are three executables:
* Client
* Daemon
* Miner

Client:
The Client can generate a wallet including the keys and base58 encoded address. See Client -h for command-line usage.

Daemon:
The Daemon is a full node implementation of blockchain. See Daemon -h for command-line usage.

Miner:
The Miner connects to a Daemon and generates blocks potentially with transactions. See Miner -h for command-line usage.
