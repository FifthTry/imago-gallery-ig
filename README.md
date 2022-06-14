# FTD - Slideshow

Package name: Slideshow
URL: fifthtry.github.io/slideshow

This component can be used as a slideshow component on your page to showcase your achievements etc.

Usage:

[Click here to see demo](https://fifthtry.github.io/slideshow/)

How to use this package?
- add below lines into `FPM.ftd` file:

```ftd
-- fpm.dependency: fifthtry.github.io/slideshow
-- fpm.auto-import: fifthtry.github.io/slideshow
```


How to define list of slideshow items e.g.

```ftd

\-- record tc:
caption title:
body body:
integer index:
boolean is-last:

\-- tc list list-tc:

\-- list-tc: Commit to the process
index: 1
is-last: false

FifthTry has a review based workflow for documentation, just like Github Pull Request. Instead of directly editing documents, FifthTry users can create change requests to implement changes to documentation

\-- list-tc: Own the changes
index: 2
is-last: false


FifthTry has a review based workflow for documentation, just like Github Pull Request. Instead of directly editing documents, FifthTry users can create change requests to implement changes to documentation

\-- list-tc: Deploy when everything’s ready
index: 3
is-last: true


FifthTry has a review based workflow for documentation, just like Github Pull Request. Instead of directly editing documents, FifthTry users can create change requests to implement changes to documentation.


Basic usage example
reference: $assets.files.assets.slideshow-demo.png
reference-width: fill

\-- slideshow: Continous Translation
list-title-copy: $list-tc

FifthTry has a review based workflow for documentation, just like Github Pull Request. Instead of directly editing documents, FifthTry users can create change requests to implement changes to documentation.

\-- slideshow: Continous Translation
list-title-copy: $list-tc

FifthTry has a review based workflow for documentation, just like Github Pull Request. Instead of directly editing documents, FifthTry users can create change requests to implement changes to documentation.
```

