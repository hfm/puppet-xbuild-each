## module structure

```
modules/xbuild/
`-- manifests
    |-- init.pp
    |-- install.pp
    |-- node
    |   `-- install.pp
    |-- perl
    |   `-- install.pp
    |-- php
    |   `-- install.pp
    |-- python
    |   `-- install.pp
    `-- ruby
        `-- install.pp
```

## how to use

```puppet
include ::xbuild
::xbuild::ruby::install { '2.1.0': }
```
