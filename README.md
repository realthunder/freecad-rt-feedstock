About freecad-rt-feedstock
==========================

Feedstock license: [BSD-3-Clause](https://github.com/realthunder/freecad-rt-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/realthunder/FreeCAD

Package license: LGPL2

Summary: FreeCAD Link Branch

FreeCAD Link Branch with various enhancement


Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/realthunder/freecad-rt-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/realthunder/freecad-rt-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-freecad--rt-green.svg)](https://anaconda.org/realthunder/freecad-rt) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/freecad-rt.svg)](https://anaconda.org/realthunder/freecad-rt) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/freecad-rt.svg)](https://anaconda.org/realthunder/freecad-rt) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/freecad-rt.svg)](https://anaconda.org/realthunder/freecad-rt) |

Installing freecad-rt
=====================

Installing `freecad-rt` from the `realthunder` channel can be achieved by adding `realthunder` to your channels with:

```
conda config --add channels realthunder
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install freecad-rt
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install freecad-rt
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add freecad-rt
# for installing globally
pixi global install freecad-rt
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `freecad-rt` available on your platform:

<details>
<summary>With conda</summary>

```
conda search freecad-rt --channel realthunder
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search freecad-rt --channel realthunder
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search freecad-rt --channel realthunder
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search freecad-rt --channel realthunder

# List packages depending on `freecad-rt`:
mamba repoquery whoneeds freecad-rt --channel realthunder

# List dependencies of `freecad-rt`:
mamba repoquery depends freecad-rt --channel realthunder
```

</details>




Updating freecad-rt-feedstock
=============================

If you would like to improve the freecad-rt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`realthunder` channel, whereupon the built conda packages will be available for
everybody to install and use from the `realthunder` channel.
Note that all branches in the realthunder/freecad-rt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@realthunder](https://github.com/realthunder/)

