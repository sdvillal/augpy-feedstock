About augpy
===========

Home: https://gitlab.com/jfolz/augpy

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/sdvillal/augpy-feedstock/blob/master/LICENSE.txt)

Summary: augpy is a lightweight library with minimal dependencies that provides a comprehensive tensor implementation for Cuda-enabled GPUs

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/augpy-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-augpy-green.svg)](https://anaconda.org/sdvillal/augpy) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/augpy.svg)](https://anaconda.org/sdvillal/augpy) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/augpy.svg)](https://anaconda.org/sdvillal/augpy) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/augpy.svg)](https://anaconda.org/sdvillal/augpy) |

Installing augpy
================

Installing `augpy` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
```

Once the `sdvillal` channel has been enabled, `augpy` can be installed with:

```
conda install augpy
```

It is possible to list all of the versions of `augpy` available on your platform with:

```
conda search augpy --channel sdvillal
```




Updating augpy-feedstock
========================

If you would like to improve the augpy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/augpy-feedstock are
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

* [@sdvillal](https://github.com/sdvillal/)

