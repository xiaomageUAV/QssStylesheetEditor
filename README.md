English | [简体中文](readme_zh-CN.md)

# preimport

[![Build Status](https://travis-ci.com/hustlei/preimport.svg?branch=master)](https://travis-ci.com/hustlei/preimport)
[![Coverage Status](https://coveralls.io/repos/github/hustlei/preimport/badge.svg?branch=master)](https://coveralls.io/github/hustlei/preimport?branch=master)
[![Platform:win|osx|linux](https://hustlei.github.io/assets/badge/platform.svg)](https://travis-ci.com/hustlei/preimport)

<br>

preimport python modules to accelerate running speed and avoid "hang" when invoke module.

# Installation

~~~shell
pip install preimport
~~~

# Usage

~~~python
from preimport import preimport

preimport('numpy', 'PyQt5')
preimport(['sys', 'os'])
~~~