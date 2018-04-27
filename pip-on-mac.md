### Problem

How can I install `pip` on Mac if I haven't got one?

### Current state

I got `pip3`, `python3` and `python` (`2`).

### Steps tried

`brew search pip` led me to `brew install python`, which only upgraded python from 3.x, and also it suggested <https://pip.readthedocs.io/en/stable/installing/>, which, apart from Linux package managers, advocates for the `get-pip.py` script, and it has two issues stopping me from installing it:

1. a warning: 
`Be cautious if you are using a Python install that is managed by your operating system or another package manager. get-pip.py does not coordinate with those tools, and may leave your system in an inconsistent state.`

2. an obfuscated blob inside it, which I don't know if it is benign or malign

### Solution

`brew install python@2` installed `pip` for me!