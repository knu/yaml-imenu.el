# yaml-imenu.el

This package enhances the imenu support in `yaml-mode`.  It generates
an index containing a full list of keys that contain any child, with
key names in the dot-separated path form like `jobs.build.docker` and
`ja.activerecord.attributes.user.nickname`.  It shines best with
`which-function-mode` enabled.

## Configuration

No configuration is needed.  It automatically registers an alternative
index generator via `yaml-mode-hook`.

## Author

Copyright (c) 2018 Akinori MUSHA.

Licensed under the 2-clause BSD license.  See `LICENSE.txt` for
details.

Visit [GitHub Repository](https://github.com/knu/yaml-imenu.el) for
the latest information.
