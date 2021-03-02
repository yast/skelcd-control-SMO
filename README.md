# skelcd-control-SMO

[![Workflow Status](https://github.com/yast/skelcd-control-SMO/workflows/CI/badge.svg?branch=master)](
https://github.com/yast/skelcd-control-SMO/actions?query=branch%3Amaster)

Installation control file for SUSE Micro OS

See also the [documentation for the `control.xml` file][1].

---

:warning: For the time being, **`master` branch is not in use**, since SUSE
Micro OS is based in SLE-15-SP2 code stream. Thus, all changes should be done
against the [`SLE-15-SP2`
branch](https://github.com/yast/skelcd-control-SMO/tree/SLE-15-SP2), which is
configured to use the `SUSE:SLE-15-SP2:Update:Products:MicroOS` project when
sending a submit request via `rake osc:sr`.

---

[1]: https://github.com/yast/yast-installation/blob/master/doc/control-file.md
