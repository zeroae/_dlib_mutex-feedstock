About _darknet_mutex
====================

Home: https://github.com/scraawl/_darknet_mutex-feedstock

Package license: BSD-3-Clause

Feedstock license: BSD 3-Clause

Summary: The darknet mutex package.

We support different variants of darknet:
`cpu`, which is darknet compiled with CPU only sppport
`gpu`, which is compiled with GPU=1;


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/zeroae/feedstock-builds/_build/latest?definitionId=1&branchName=master">
        <img src="https://dev.azure.com/zeroae/feedstock-builds/_apis/build/status/_darknet_mutex-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-_darknet_mutex-green.svg)](https://anaconda.org/zeroae/_darknet_mutex) | [![Conda Downloads](https://img.shields.io/conda/dn/zeroae/_darknet_mutex.svg)](https://anaconda.org/zeroae/_darknet_mutex) | [![Conda Version](https://img.shields.io/conda/vn/zeroae/_darknet_mutex.svg)](https://anaconda.org/zeroae/_darknet_mutex) | [![Conda Platforms](https://img.shields.io/conda/pn/zeroae/_darknet_mutex.svg)](https://anaconda.org/zeroae/_darknet_mutex) |

Installing _darknet_mutex
=========================

Installing `_darknet_mutex` from the `zeroae` channel can be achieved by adding `zeroae` to your channels with:

```
conda config --add channels zeroae
```

Once the `zeroae` channel has been enabled, `_darknet_mutex` can be installed with:

```
conda install _darknet_mutex
```

It is possible to list all of the versions of `_darknet_mutex` available on your platform with:

```
conda search _darknet_mutex --channel zeroae
```




Updating _darknet_mutex-feedstock
=================================

If you would like to improve the _darknet_mutex recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`zeroae` channel, whereupon the built conda packages will be available for
everybody to install and use from the `zeroae` channel.
Note that all branches in the zeroae/_darknet_mutex-feedstock are
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

