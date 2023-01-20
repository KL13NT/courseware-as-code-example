---
title: Upgrading CaC version
description: How to update the version of the action used with your course
---

CaC is software. And like all software, it receives updates occasionally with
added features and bugs fixed. To update the version of CaC used in your
pipeline go to the `.github/workflows/build.yml` file, scroll down until you
find the `uses: kl13nt/courseware-as-code-action@v0.0.14` line of code and
change the version to the latest you can find on the [releases] page.

For example, to upgrade from version 0.0.14 to 0.0.15 make the following
changes:

```diff
...
      - name: Build using CaC Action 🏗️
-       uses: kl13nt/courseware-as-code-action@v0.0.14
+       uses: kl13nt/courseware-as-code-action@v0.0.15
        with:
          debug: true
...
```

[releases]: https://github.com/KL13NT/courseware-as-code-action/releases
