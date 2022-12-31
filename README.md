# `re-actors/checkout-python-sdist@release/v1`

A GitHub Action to unpack a source distribution package (tarball / `.tar.gz`) into the current workspace


## Options

This action only has two inputs — `source-tarball-name` (default:
`*.tar.gz`) and `workflow-artifact-name` (default:
`python-package-distributions`). It downloads the latter and works with
the sdist matching the former glob to make its contents available in the
current working directory.


## Any users?

At the moment, it is used by the [@CherryPy] upstream, more to come.


## License

The contents of this project is released under the
[BSD 3-clause license].


[BSD 3-clause license]: LICENSE
[@CherryPy]: https://github.com/cherrypy
