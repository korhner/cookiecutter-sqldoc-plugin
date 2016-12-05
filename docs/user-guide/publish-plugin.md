# Publish a Plugin

There are several ways to publish a [sqldoc] plugin.

Essentially sqldoc plugins are not different from any other Python Package, so
you may want to create a distribution and submit it to the Python Package Index ([PyPI]).

By doing so, enables your users to easily install via ``easy-install`` or ``pip``.

## Python Package Index

Submitting to [PyPI] that includes the following steps:

- Configuring your plugin (which is already covered in this template)
- Creating a distribution for your project
- Uploading your Pytest plugin to PyPI

Please see the official [Python Packaging User Guide] for detailed information.

Sqldoc plugins should aim to meet the following requirements:

-   PyPI presence with a setup.py that contains a license, sqldoc-
    prefixed, version number, authors, short and long description.
-   a tox.ini for running tests using Tox.
-   a README describing how to use the plugin and on which platforms
    it runs.
-   a LICENSE file or equivalent containing the licensing information,
    with matching info in setup.py.

  [sqldoc]: https://github.com/korhner/sqldoc
  [PyPI]: https://pypi.python.org/pypi
  [Python Packaging User Guide]: https://python-packaging-user-guide.readthedocs.io/en/latest/distributing.html
