TODO
====

In development branch:

* End support for Python 2.4.
* Add Python 3.3 to tox file (after deprecating 2.4).
* Turn the benchmarking script at pystache/tests/benchmark.py into a command in pystache/commands, or
  make it a subcommand of one of the existing commands (i.e. using a command argument).
* Provide support for logging in at least one of the commands.
* Make sure command parsing to pystache-test doesn't break with Python 2.4 and earlier.
* Combine pystache-test with the main command.
