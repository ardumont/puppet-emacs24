puppet-stumpwm
==============

A simple puppet module to ease the install of emacs24.

# use

## install via git

This is designed at the moment to be built up with git.

Add this project as a submodule

``` git
git submodule add git@github.com:ardumont/puppet-emacs24.git /path/to/puppet/modules/folder/emacs24
```

## Use

### static config

init.pp:

``` puppet
include emacs24
```

### ENC

`your-node.yaml`:

``` yaml
  emacs24:
```
