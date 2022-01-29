# Leiningen Dependency Update Action

## DEPRECATION

As of 2022-01-29, the [clojure-dependency-update-action](https://github.com/nnichols/clojure-dependency-update-action) supports most, if not all, clojure build files: including project.clj and pom.xml.
This action originally existed to serve Leiningen users directly since each dependency file type was managed by an individual action.
Because this is no longer required, the leiningen-dependency-update-action is now redundant and should be considered deprecated.

That said, upgrading to the new action is trivial.
Simply replace any references to `nnichols/leiningen-dependency-update-action@v1` with `nnichols/clojure-dependency-update-action@v4`.
The action arguments are identical and no further updates will be required.

This repository will be marked as archived and will no longer receive further updates.

## Licensing

Copyright © 2021-2022 [Nick Nichols](https://nnichols.github.io/)

Distributed under the [MIT License](https://github.com/nnichols/leiningen-dependency-update-action/blob/master/LICENSE)
