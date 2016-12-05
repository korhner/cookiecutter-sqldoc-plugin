============================
Cookiecutter sqldoc Plugin
============================

[![See Build Status on Travis CI][travis_badge]][travis]
[![Documentation Status][docs_badge]][documentation]

Minimal [Cookiecutter] template for authoring [sqldoc] plugins that help
you to write better programs.

> This template requires [Cookiecutter 1.4.0 "Shortbread"][Shortbread] or
> higher

Getting Started
---------------

Simply install [Cookiecutter] and generate a new sqldoc plugin project:

```no-highlight
$ pip install cookiecutter
$ cookiecutter https://github.com/korhner/cookiecutter-sqldoc-plugin
```

Cookiecutter prompts you for information regarding your plugin:

```no-highlight
full_name [Ivan Korhner]: Ivan Korhner
email [korhner@gmail.com]: korhner@gmail.com
github_username [korhner]: korhner
plugin_name [sqldoc]: sqldoc
short_description [A simple plugin to use with sqldoc]:
version [0.1.0]:
pytest_version [0.1.0]:
Select docs_tool:
1 - mkdocs
2 - sphinx
3 - none
Choose from 1, 2, 3 [1]: 1
Select license:
1 - MIT
2 - BSD-3
3 - GNU GPL v3.0
Choose from 1, 2, 3 [1]: 2
INFO:post_gen_project:Moving files for mkdocs.
```

There you go - you just created a minimal sqldoc plugin:

```no-highlight
sqldoc-plugin/
├── LICENSE
├── README.rst
├── docs
│   └── index.md
├── mkdocs.yml
├── sqldoc_plugin.py
├── setup.py
├── tests
│   ├── conftest.py
│   └── test_plugin.py
└── tox.ini
```


Features
--------

- Installable [PyPI] package featuring a `setup.py`.
- Test suite running [Tox] and [sqldoc] that makes sure your plugin is working
  as expected
- Comprehensive `README.rst` file that contains useful information about your
  plugin
- Continuous integration configuration for [Travis CI] and [AppVeyor]
- Optional documentation with either [Sphinx] or [MkDocs]
- Choose from several licenses, such as [MIT], [BSD-3], [Apache v2.0], [GNU GPL
  v3.0], or [MPL v2.0]


Contribute
----------

We welcome you to contribute to this project. Please visit the [documentation]
to get started!

Issues
------

If you encounter any problems, please [file an issue] along with a
detailed description.

Code of Conduct
---------------

Everyone interacting in the Cookiecutter sqldoc Plugin project's codebases,
issue trackers is expected to follow the [PyPA
Code of Conduct].

License
-------

Distributed under the terms of the [MIT license], Cookiecutter sqldoc
Plugin is free and open source software



  [travis_badge]: https://travis-ci.org/korhner/cookiecutter-sqldoc-plugin.svg?branch=master
  [travis]: https://travis-ci.org/korhner/cookiecutter-sqldoc-plugin (See Build Status on Travis CI)
  [docs_badge]: https://readthedocs.org/projects/cookiecutter-sqldoc-plugin/badge/?version=latest
  [documentation]: https://cookiecutter-sqldoc-plugin.readthedocs.io/en/latest/ (Documentation)
  [Cookiecutter]: https://github.com/audreyr/cookiecutter
  [sqldoc]: https://github.com/korhner/pytest
  [PyPI]: https://pypi.python.org/pypi
  [Tox]: https://tox.readthedocs.io/en/latest/
  [MIT license]: http://opensource.org/licenses/MIT
  [file an issue]: https://github.com/korhner/cookiecutter-sqldoc-plugin/issues
  [Sphinx]: http://sphinx-doc.org/
  [MkDocs]: http://www.mkdocs.org/
  [MIT]: http://opensource.org/licenses/MIT
  [MPL v2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
  [BSD-3]: http://opensource.org/licenses/BSD-3-Clause
  [GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
  [Apache v2.0]: http://www.apache.org/licenses/LICENSE-2.0
  [Travis CI]: https://travis-ci.com/
  [AppVeyor]: http://www.appveyor.com/
  [PyPA Code of Conduct]: https://www.pypa.io/en/latest/code-of-conduct/
  [Shortbread]: https://github.com/audreyr/cookiecutter/releases/tag/1.4.0
