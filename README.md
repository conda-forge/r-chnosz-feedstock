About r-chnosz-feedstock
========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-chnosz-feedstock/blob/main/LICENSE.txt)


About r-chnosz
--------------

Home: https://www.chnosz.net/, https://r-forge.r-project.org/projects/chnosz/

Package license: AGPL-3.0-only

Summary: An integrated set of tools for thermodynamic calculations in aqueous geochemistry and geobiochemistry. Functions are provided for writing balanced reactions to form species from user-selected basis species and for calculating the standard molal properties of species and reactions, including the standard Gibbs energy and equilibrium constant. Calculations of the non-equilibrium chemical affinity and equilibrium chemical activity of species can be portrayed on diagrams as a function of temperature, pressure, or activity of basis species; in two dimensions, this gives a maximum affinity or predominance diagram. The diagrams have formatted chemical formulas and axis labels, and water stability limits can be added to Eh-pH, oxygen fugacity- temperature, and other diagrams with a redox variable. The package has been developed to handle common calculations in aqueous geochemistry, such as solubility due to complexation of metal ions, mineral buffers of redox or pH, and changing the basis species across a diagram ("mosaic diagrams"). CHNOSZ also implements a group additivity algorithm for the standard thermodynamic properties of proteins.

About r-chnosz
--------------

Home: https://www.chnosz.net/, https://r-forge.r-project.org/projects/chnosz/

Package license: AGPL-3.0-only

Summary: An integrated set of tools for thermodynamic calculations in aqueous geochemistry and geobiochemistry. Functions are provided for writing balanced reactions to form species from user-selected basis species and for calculating the standard molal properties of species and reactions, including the standard Gibbs energy and equilibrium constant. Calculations of the non-equilibrium chemical affinity and equilibrium chemical activity of species can be portrayed on diagrams as a function of temperature, pressure, or activity of basis species; in two dimensions, this gives a maximum affinity or predominance diagram. The diagrams have formatted chemical formulas and axis labels, and water stability limits can be added to Eh-pH, oxygen fugacity- temperature, and other diagrams with a redox variable. The package has been developed to handle common calculations in aqueous geochemistry, such as solubility due to complexation of metal ions, mineral buffers of redox or pH, and changing the basis species across a diagram ("mosaic diagrams"). CHNOSZ also implements a group additivity algorithm for the standard thermodynamic properties of proteins.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22264&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chnosz-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.2</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22264&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chnosz-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.2" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22264&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chnosz-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.2</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22264&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chnosz-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.2" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22264&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chnosz-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22264&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chnosz-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--chnosz-green.svg)](https://anaconda.org/conda-forge/r-chnosz) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-chnosz.svg)](https://anaconda.org/conda-forge/r-chnosz) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-chnosz.svg)](https://anaconda.org/conda-forge/r-chnosz) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-chnosz.svg)](https://anaconda.org/conda-forge/r-chnosz) |

Installing r-chnosz
===================

Installing `r-chnosz` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-chnosz` can be installed with `conda`:

```
conda install r-chnosz
```

or with `mamba`:

```
mamba install r-chnosz
```

It is possible to list all of the versions of `r-chnosz` available on your platform with `conda`:

```
conda search r-chnosz --channel conda-forge
```

or with `mamba`:

```
mamba search r-chnosz --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-chnosz --channel conda-forge

# List packages depending on `r-chnosz`:
mamba repoquery whoneeds r-chnosz --channel conda-forge

# List dependencies of `r-chnosz`:
mamba repoquery depends r-chnosz --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

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


Updating r-chnosz-feedstock
===========================

If you would like to improve the r-chnosz recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-chnosz-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@cmkobel](https://github.com/cmkobel/)

