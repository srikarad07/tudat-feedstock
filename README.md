About tudat
===========

Home: http://tudat.tudelft.nl/

Package license: BSD

Feedstock license: BSD-3-Clause

Summary: A C++ platform to perform astrodynamics and space research.



Current build status
====================


<table><tr>
    <td>CircleCI</td>
    <td>
      <a href="https://circleci.com/gh/tudat-team/tudat-feedstock">
        <img alt="Linux" src="https://img.shields.io/circleci/project/github/tudat-team/tudat-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/tudat-team/tudat-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/tudat-team/tudat-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-tudat-green.svg)](https://anaconda.org/tudat-team/tudat) | [![Conda Downloads](https://img.shields.io/conda/dn/tudat-team/tudat.svg)](https://anaconda.org/tudat-team/tudat) | [![Conda Version](https://img.shields.io/conda/vn/tudat-team/tudat.svg)](https://anaconda.org/tudat-team/tudat) | [![Conda Platforms](https://img.shields.io/conda/pn/tudat-team/tudat.svg)](https://anaconda.org/tudat-team/tudat) |

Installing tudat
================

Installing `tudat` from the `tudat-team` channel can be achieved by adding `tudat-team` to your channels with:

```
conda config --add channels tudat-team
```

Once the `tudat-team` channel has been enabled, `tudat` can be installed with:

```
conda install tudat
```

It is possible to list all of the versions of `tudat` available on your platform with:

```
conda search tudat --channel tudat-team
```




Updating tudat-feedstock
========================

If you would like to improve the tudat recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tudat-team` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tudat-team` channel.
Note that all branches in the tudat-team/tudat-feedstock are
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

* [@ggarrett13](https://github.com/ggarrett13/)

