[![Build and Test](https://github.com/devplaybooks/spark4/actions/workflows/CI.yml/badge.svg)](https://github.com/devplaybooks/spark4/actions/workflows/CI.yml)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square)](LICENSE-APACHE)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE-GPLv3)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE-MIT)

---

# Apache Spark 4 Dev Playbook (Work in Progress)

Leverages [asdf](https://asdf-vm.com/) for required versions of 
[Apache Spark](https://spark.apache.org/), Python 
[Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main), Java & Scala. 
See [.tool-versions](./.tool-versions) for the specific versions.

## TL;DR

```shell
asdf install
bin/doinit
```

Now, in a new shell:

```shell
bin/doactivate
bin/dojupyter
```

To clean up:

```shell
dodeactivate
nukeit
```

## Resources

- [PySpark Cheat Sheet](https://cartershanklin.github.io/pyspark-cheatsheet/)
- [Conda Forge](https://conda-forge.org/)
  - [IJava](https://github.com/JaneliaSciComp/IJava)

## Includes:

* [Actions Blank CI Starter Workglow](https://github.com/actions/starter-workflows/blob/main/ci/blank.yml)
* [bnb's](https://github.com/bnb) [Codespaces Base Starter](https://github.com/codespaces-examples/base)
* Choice of licenses:
    * [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
    * [GPL 3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * [MIT License](https://opensource.org/license/mit/)
* [Shields.io](https://shields.io/) [Badges](https://github.com/badges/shields)
