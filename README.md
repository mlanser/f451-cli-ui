# f451 Labs CLI UI module v0.0.2

## Overview

The *f451 Labs CLI UI* module contains functions, variables, and constants that c an be used to create common UI elements for *f451 Labs* projects.

## Install

This module is not (yet) available on PyPi. however, you can still use `pip` to install the module directly from Github (see below).

### Dependencies

This module is dependent on the following libraries:

- [rich](https://pypi.org/project/pyfiglet/)
- [sparklines](https://pypi.org/project/sparklines/)
- [termcolor](https://pypi.org/project/termcolor/) to color Sparkline graphs
- [f451-common](https://github.com/mlanser/f451-common.git) to create fancy logo color Sparkline graphs

### Installing from Github using `pip`

You can use `pip install` to install this module directly from Github as follows:

```bash
$ pip install 'f451-cli-ui @ git+https://github.com/mlanser/f451-cli-ui.git'
```

## How to use

Using the module is straightforward. Simply `import` the components of the module as needed in your code.

```Python
# Import specific components from the f451 Labs CLI UI module
from f451_cli_ui.cli_ui import some_function, some_variable, some_constant

myVar = some_function()

# Import all components from the f451 Labs CLI UI module
import f451_cli_ui.cli_ui as f451CLIUI

myVar = f451CLIUI.some_function()
```

## Core functions

- **some_function()** — Blah blah.
- **other_function()** — Blah blah.
