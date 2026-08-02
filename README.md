# G Hunt Play

This public repository hosts the compiled browser build for G Hunt.

The editable Godot project, GDScript source, scenes, raw development files, and source Git history remain in the private `Dancodes2/g-hunt` repository.

Compiled Web builds are uploaded as GitHub Release assets named `g-hunt-web.zip`. The GitHub Pages workflow downloads that asset, validates the artifact root, uploads it with `actions/upload-pages-artifact`, and publishes it with `actions/deploy-pages`.

Do not commit `index.pck`, `index.wasm`, Godot source files, or raw source project folders to this repository.
