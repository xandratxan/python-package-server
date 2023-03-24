# Package python-package-server

> GitHub Pages site that serves as a PyPi Server.

| Last version: 0.1.0          | Source code: [GitHub](https://github.com/xandratxan/python-package-server/)          | Issues: [GitHub](https://github.com/xandratxan/python-package-server/issues/) |
|------------------------------|--------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| **Last release: March 2023** | **Documentation : [GitHub Pages](https://xandratxan.github.io/package-server.html)** | **License: GNU GPL 3.0**                                                      |

> **WARNING**: This package is under active development. The current version should be considered **non-stable**.

This GitHub Pages site serves as a PyPI server for GitHub the repositories of xandratxan hosted in GitHub.
The packages available in this server can be used to specify dependencies in pyproject.toml files 
including the entry ``dependencies = ['my_package']``. They can also be installed via pip:

```bash
pip install my_package --extra-index-url https://xandratxan.github.io/python-package-server/
```

The following packages are available:

- ``physical-magnitude``

Based on a [blog post](
https://medium.freecodecamp.org/how-to-use-github-as-a-pypi-server-1c3b0d07db2) on using GitHub as a PyPi Server.

## Release History

* 0.1.0
    * First release

## Authors

Xandra Campo

[@GitHub](https://github.com/xandratxan/)
[@GitHub Pages](https://xandratxan.github.io/)

xkmpera@gmail.com