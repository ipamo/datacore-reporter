Datacore-reporter
=================

Extract data easily from your Datacore controllers.


## Installation

Datacore-reporter package is published [on PyPI](https://pypi.org/project/datacore-reporter/):

```sh
pip install datacore-reporter
```


## Configuration

Create file `C:\Users\$USER\AppData\Local\datacore-reporter\datacore-reporter.conf` (`/home/$USER/.config/datacore-reporter/datacore-reporter.conf` on Linux). Example:

```ini
[datacore-reporter]
host = myhost.example.org
controller = mycontroller.example.org
user = reporter
password = ...
no_ssl = True
```

## Usage

See also [full documentation](https://ipamo.net/datacore-reporter) (including [API reference](https://ipamo.net/datacore-reporter/latest/api-reference.html)).

Datacore-reporter may be used as a library in your Python code:

```py
from datacore_reporter.client import DatacoreClient
...
```

Datacore-reporter may also be invoked as a command-line application (the `datacore-reporter` executable is installed with the package).

Complete help about command-line usage may be displayed by typing:

```sh
datacore-reporter --help
```


## Legal

This project is licensed under the terms of the [MIT license](https://raw.githubusercontent.com/ipamo/datacore-reporter/main/LICENSE.txt).

This project is not affiliated in any way with the Datacore company.
