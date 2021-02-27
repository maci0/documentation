# RISC-V Documentation at RV-MACHINES

## Introduction

This is the repository for the documentation available at [RISC-V Machines @ RTFD](http://risc-v-machines.rtfd.io/), a project that aims to serve documentation regarding the `RISC-V` architecture applied to containers and especially `Kubernetes`.

The documentation is hosted with love at *Read The Docs*.

For details about RISC-V itself, see the [RISC-V Website](https://riscv.org) and the [RISC-V Getting Started Guide](https://risc-v-getting-started-guide.readthedocs.io/en/latest/index.html).

## Compiling the Guide

The Guide is built using [MkDocs](https://www.mkdocs.org/).

`MkDocs` can be installed with `pip`, the Python package manager:

```bash
pip install mkdocs
```
> for detailed instructions, see [MkDocs User Guide](https://www.mkdocs.org/user-guide/writing-your-docs/>)

To compile the HTML version of the Guide, use::

```bash
mkdocs serve
```

> It will start a light http server that will allow you viewing the rendered docs.
