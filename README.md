# Dockerized `testrpc`

## Details

* Node.js (~6.9.0)
* testrpc (latest)


## Pull image

    docker pull harshjv/testrpc


## Usage

Start testrpc daemon;

    docker run -d -p 8545:8545 harshjv/testrpc

Or provide command-line options;

    docker run -d -p 8545:8545 harshjv/testrpc --gasPrice 0

See [`testrpc`](https://github.com/ethereumjs/testrpc) for available options.


## License

MIT
