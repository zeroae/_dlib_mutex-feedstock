About _dlib_mutex
=================

Home: https://github.com/zeroae/_dlib_mutex-feedstock

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/zeroae/_dlib_mutex-feedstock/blob/master/LICENSE.txt)

Summary: The dlib mutex package.

We support different variants of darknet:
`cpu`, which is compiled with CPU/AVX only sppport
`cuda`, which is compiled with CUDA;


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/zeroae/feedstock-builds/_build/latest?definitionId=1&branchName=master">
        <img src="https://dev.azure.com/zeroae/feedstock-builds/_apis/build/status/_dlib_mutex-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_dlib_mutex-green.svg)](https://anaconda.org/zeroae/_dlib_mutex) | [![Conda Downloads](https://img.shields.io/conda/dn/zeroae/_dlib_mutex.svg)](https://anaconda.org/zeroae/_dlib_mutex) | [![Conda Version](https://img.shields.io/conda/vn/zeroae/_dlib_mutex.svg)](https://anaconda.org/zeroae/_dlib_mutex) | [![Conda Platforms](https://img.shields.io/conda/pn/zeroae/_dlib_mutex.svg)](https://anaconda.org/zeroae/_dlib_mutex) |

Installing _dlib_mutex
======================

Installing `_dlib_mutex` from the `zeroae` channel can be achieved by adding `zeroae` to your channels with:

```
conda config --add channels zeroae
```

Once the `zeroae` channel has been enabled, `_dlib_mutex` can be installed with:

```
conda install _dlib_mutex
```

It is possible to list all of the versions of `_dlib_mutex` available on your platform with:

```
conda search _dlib_mutex --channel zeroae
```




Updating _dlib_mutex-feedstock
==============================

If you would like to improve the _dlib_mutex recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`zeroae` channel, whereupon the built conda packages will be available for
everybody to install and use from the `zeroae` channel.
Note that all branches in the zeroae/_dlib_mutex-feedstock are
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

* [@sodre](https://github.com/sodre/)

