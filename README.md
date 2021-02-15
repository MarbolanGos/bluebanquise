# BlueBanquise
![BlueBanquise Logo](resources/pictures/BlueBanquise_logo_large.svg)

<p align="center">
  Web site: <a href="https://bluebanquise.com"><b>https://bluebanquise.com</b></a>
</p>

## What is BlueBanquise

**BlueBanquise** is a coherent **Ansible** roles collection, designed to deploy and manage large group of hosts (clusters of nodes).

Main target is High Performance Computing (HPC), but the BlueBanquise stack is generic and can adapt to any kind of architecture (university or enterprise infrastructures, render farm, etc.).

BlueBanquise is part of the **Algoric** Project from the [**Fabrique du Loch**](https://www.lafabriqueduloch.org/fr/accueil/) FabLab.

![BlueBanquise Logo](resources/pictures/FabriqueDuLochAlgoric_logo_large.svg)

It is a revamping of the old stack [Banquise](https://github.com/oxedions/banquise), based on Salt.

## Ressources

### Files

The stack is split over multiple repositories:

* :globe_with_meridians: **Core:** stack core is hosted on github, in this [same repository](https://github.com/bluebanquise/bluebanquise).

* :star: **Additional roles:** community roles or tools are hosted on github, in the [community repository](https://github.com/bluebanquise/community).

### Documentation

The stack documentation is available on the BlueBanquise main website, in [documentation subfolder](https://bluebanquise.com/documentation/).

Note that each role (core or community) embeds its own readme, with detailed usage description.

### Packages

The stack packages are available in the [repositories subfolder](https://bluebanquise.com/repository/).

## Supported software environment

| Operating System family | Operating System distribution | Tested versions    | Notes                               |
| ----------------------- | ----------------------------- | ------------------ | ----------------------------------- |
| RedHat                  |                               |                    |                                     |
|                         | RHEL                          | 7.x, 8.x           | Should work on all 7 and 8 versions |
|                         | CentOS                        | 7.x, 8.x           | Should work on all 7 and 8 versions |
|                         | CentOS Stream                 | NA                 | In dev, targeted for next release   |
|                         | Oracle Linux                  | NA                 | In dev, targeted for next release   |
|                         | Springdale Linux              | NA                 | In dev, targeted for next release   |
|                         | CloudLinux                    | NA                 | Waiting for distribution release    |
|                         | RockyLinux                    | NA                 | Waiting for distribution release    |
| Suse                    |                               |                    |                                     |
|                         | SLES                          | NA                 | In dev, targeted for next release   |
|                         | OpenSuse Leap                 | NA                 | In dev, targeted for next release   |
| Debian                  |                               |                    |                                     |
|                         | Ubuntu                        | NA                 | In dev, targeted for next release   |
|                         | Debian                        | NA                 | In dev, targeted for next release   |

Ansible >= 2.9.13 is mandatory for BlueBanquise to run properly.

**[OpenHPC](https://openhpc.community/downloads/)** scientific packages and OpenHPC slurm job scheduler are compatible with the stack.

## The name

You may wonder where this name comes from:

* [BlueBanquise](https://en.wikipedia.org/wiki/File:Blue_iceberg_in_the_Ilulissat_icefjord.jpg)
* [Blue Iceberg](https://en.wikipedia.org/wiki/Blue_iceberg)

## Thanks

Special thanks:

* to [CINES](https://www.cines.fr/en/) who provided Algoric team with hardware to develop this stack.
* to [@remyd1](https://github.com/remyd1) for his help on [Banquise](https://github.com/oxedions/banquise) original stack.
* to [@bouriquet](https://github.com/bouriquet) for his active help on the stack.
* to [@btravouillon](https://github.com/btravouillon) for his active help on the stack.
