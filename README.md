# yaml-imenu.el

This package enhances the imenu support in `yaml-mode`.  It generates
an index containing a full list of keys that contain any child, with
key names in the dot-separated path form like `jobs.build.docker` and
`ja.activerecord.attributes.user.nickname`.  It shines best with
`which-function-mode` enabled.

## Configuration

No configuration is needed.  It automatically registers an alternative
index generator via `yaml-mode-hook`.

## Usage

A precise YAML node path list this package provides is especially
useful when dealing with a large YAML file.

With `which-func-mode` enabled, you can always see at a glance where
you are.  In this example, the "YAML path" is shown in the header line
instead of the mode line by customizing `header-line-format`.

![With which-func-mode](./images/which-func.png "With which-func-mode")

Using `helm-imenu`, it is extremely easy to navigate to anywhere you
want to go.

![With helm-imenu](./images/helm-imenu.png "With helm-imenu")

## Author

Copyright (c) 2018 Akinori MUSHA.

Licensed under the 2-clause BSD license.  See `LICENSE.txt` for
details.

Visit [GitHub Repository](https://github.com/knu/yaml-imenu.el) for
the latest information.
