About cryptography
==================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

Home: https://github.com/pyca/cryptography

Package license: Apache 2.0 or BSD 3-Clause, PSF 2

Feedstock license: BSD 3-Clause

Summary: Provides cryptographic recipes and primitives to Python developers

Cryptography is a package which provides cryptographic recipes and
primitives to Python developers. Our goal is for it to be your
"cryptographic standard library". It supports Python 2.6-2.7, Python 3.3+,
and PyPy 2.6+. Cryptography includes both high level recipes, and low level
interfaces to common cryptographic algorithms such as symmetric ciphers,
message digests and key derivation functions.


Current build status
====================

[![Linux,OSX](https://img.shields.io/circleci/project/github/conda-forge/cryptography-feedstock/master.svg?label=Linux,OSX)](https://circleci.com/gh/conda-forge/cryptography-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/conda-forge/cryptography-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/conda-forge/cryptography-feedstock/branch/master)
[![linux-aarch64](https://img.shields.io/shippable/5c3295fad1578b0700304a0b/aarch64.svg?label=linux-aarch64)](https://app.shippable.com/github/Archiconda/cryptography-feedstock)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cryptography-green.svg)](https://anaconda.org/conda-forge/cryptography) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/cryptography.svg)](https://anaconda.org/conda-forge/cryptography) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/cryptography.svg)](https://anaconda.org/conda-forge/cryptography) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/cryptography.svg)](https://anaconda.org/conda-forge/cryptography) |

Installing cryptography
=======================

Installing `cryptography` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `cryptography` can be installed with:

```
conda install cryptography
```

It is possible to list all of the versions of `cryptography` available on your platform with:

```
conda search cryptography --channel conda-forge
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating cryptography-feedstock
===============================

If you would like to improve the cryptography recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/cryptography-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@jakirkham](https://github.com/jakirkham/)
* [@jschueller](https://github.com/jschueller/)
* [@ocefpaf](https://github.com/ocefpaf/)

