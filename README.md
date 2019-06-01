# Low Memory Bitcoin Node

Prototypal Bitcoin Node Configuration for a Low Memory Environment

## Getting Started

Located in this repository is a configuration file for running
[Bitcoin](https://bitcoin.org/en/download) in a low memory environment. The
configuration file is a list of setting=value pairs, one per line, with optional
comments starting with the '#' character.

By default when running Bitcoin, Bitcoin will look for this a file in the
bitcoin data directory, but both the data directory and the configuration file
path may be changed using the -datadir and -conf command-line arguments.

The configuration file is not automatically created; you can create it using
your favorite plain-text editor, or use the `bitcoin.conf` file located in this
repository.

### Prerequisites

In order to take advantage of this repository, first make sure you are [Running
Bitcoin](https://en.bitcoin.it/wiki/Running_Bitcoin).

## Versioning

`1.0.0`

## Maintainer

Will Binns (GitHub/Telegram/Twitter: @wbnns | Web: https://willbinns.org/)

## License

See the [LICENSE.md](LICENSE.md) file for more details.

## Reference Material

+ https://bitcoin.stackexchange.com/questions/50580/how-to-run-bitcoind-in-a-low-memory-environment
+ https://en.bitcoin.it/wiki/Running_Bitcoin
