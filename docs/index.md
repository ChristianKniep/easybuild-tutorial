!!! warning
    *(Apr 19th 2020)*<br/>
    **This is very much a work in progress!**<br/>
    Many pages are still empty, that will hopefully change soon...

# Welcome to the official EasyBuild tutorial!

<p align="center"><img src="https://boegel.github.io/easybuild-tutorial/img/easybuild_logo_alpha.png" alt="EasyBuild logo" width="300px"/></p>


---

## Scope

This is an introductory tutorial to [EasyBuild](https://easybuilders.github.io/easybuild),
a command line tool for installing (scientific) software on High Performance Computing (HPC) systems.

It aims to explain the core concepts of EasyBuild,
get you started with using it, make you familiar with some of the features it provides,
and show how it is used by large HPC sites to maintain their central software stacks.

Through hands-on exercises and demos, you will learn how EasyBuild can help you
to get scientific software installed in an efficient way.


## Intended audience

This tutorial is primarily intended for people new to EasyBuild, but even if you're already familiar
with the project it could be interesting to step through it.

Our main target audience includes:

* HPC system administrators
* HPC user support team members
* scientific researchers using HPC systems


## Prerequisites

We expect you to be (a little bit) familiar with:

* using a Linux command line interface
* the (absolute) basics of compiling software from source

Required software:

* OS: GNU/Linux (any distribution)
* Python 2.7 or 3.5+
* an environment modules tool (see the ``module`` command)

    * we recommend [Lmod](https://lmod.readthedocs.io), a modern environment modules tool implemented in Lua
    * for more information on the environment modules tools supported by EasyBuild, see [here](https://easybuild.readthedocs.io/en/latest/Installation.html#required-modules-tool)


## Tutorial contents

1. [Introduction to EasyBuild](01_introduction.md)
*  [Installation](02_installation.md) ``(*)``
*  [Configuration](03_configuration.md) ``(*)``
*  [Basic usage](04_basic_usage.md) ``(*)``
*  [Installing software with EasyBuild](05_installing_software.md) ``(*)``
*  [Troubleshooting](06_troubleshooting.md) ``(*)``
*  [Beyond the basics](07_beyond_the_basics.md) ``(*)``
*  [Hierarchical module naming schemes](08_hmns.md) ``(*)``
*  [Adding support for additional software](09_adding_support_software.md) ``(*)``
*  [EasyBuild at Jülich Supercomputing Centre](10_jsc.md)
*  [EasyBuild at Compute Canada](11_computecanada.md)
*  [The EasyBuild Community](12_community.md)
*  [Contributing to EasyBuild](13_contributing.md) ``(*)``
*  [Comparison with other tools](14_comparison_other_tools.md)
*  [Getting help](15_getting_help.md)

*(sections indicated with* ``(*)`` *involve hands-on exercises)*

## Additional resources

* website: [https://easybuilders.github.io/easybuild](https://easybuilders.github.io/easybuild)
* documentation: [https://easybuild.readthedocs.io](https://easybuild.readthedocs.io)
* GitHub: [https://github.com/easybuilders](https://github.com/easybuilders)
* Slack: [https://easybuild.slack.com](https://easybuild.slack.com) (self-request an invite [here](https://easybuild-slack.herokuapp.com))
* mailing list: [https://lists.ugent.be/wws/subscribe/easybuild](https://lists.ugent.be/wws/subscribe/easybuild)
