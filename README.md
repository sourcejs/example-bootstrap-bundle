# Bootstrap Documentation example made in SourceJS

[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/sourcejs/Source)

Copy of [Bootstrap documentation](http://getbootstrap.com/components), made by using SourceJS native features: EJS includes, Markdown, catalog system, search, clarify for testing examples standalone.

Compatible with SourceJS 0.5.1+.

## Setup Instructions

Since SourceJS allows storing multiple bundles/UI libraries in one instance, checkout this repo contents as a nested folder in `sourcejs/user/specs` folder, or make a symlink there.

```
cd sourcejs/user/specs
git clone https://github.com/sourcejs/example-bootstrap-bundle
```

Re-run SourceJS app, and open http://127.0.0.1:8080/specs/bootstrap.

```
cd sourcejs
node app.js
open http://127.0.0.1:8080/specs/example-bootstrap-bundle
```
