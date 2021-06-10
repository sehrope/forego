## forego

[Foreman](https://github.com/ddollar/foreman) in Go.

This project was forked from https://github.com/ddollar/forego.

### Installation

Pre-built binaries for Linux, OSX, and Windows are available for download: https://github.com/sehrope/forego/releases

#### Compile from Source

Clone this repo and build via:

    $ make

### Usage

    $ cat Procfile
    web: bin/web start -p $PORT
    worker: bin/worker queue=FOO

    $ forego start
    web    | listening on port 5000
    worker | listening to queue FOO

Use `forego help` to get a list of available commands, and `forego help
<command>` for more detailed help on a specific command.

### License

Apache 2.0 &copy; 2015 David Dollar

Apache 2.0 &copy; 2020 Sehrope Sarkuni
