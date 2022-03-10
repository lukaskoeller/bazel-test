## Gettings Started

Building Everything:
```
bazel build //...
```

Output goes to `bazel-bin`.

## Good to Know

* Maintainance
> This repository is maintained by volunteers in the Bazel community. Neither Google, nor the Bazel team, provides support for the code.
https://github.com/bazelbuild/rules_nodejs

**Compatibility**
* See https://github.com/sveltejs/kit/issues/2973
* See https://github.com/bazelbuild/rules_nodejs/issues/266
* See https://www.npmjs.com/search?q=%40bazel
* Workspaces compatibility https://github.com/bazelbuild/rules_nodejs/issues/266

## Reference

* vite rules from @ubiquitoustech https://github.com/ubiquitoustech/rules_vite
  * Connected prior PR https://github.com/bazelbuild/rules_nodejs/pull/3004/files
* https://github.com/mikberg/bazel-vite# bazel-test
* [`rules_nodejs` on Github](https://github.com/bazelbuild/rules_nodejs/tree/3.x)
* [`rules_nodejs` examples](https://github.com/bazelbuild/rules_nodejs/tree/stable/examples/create-react-app)
  * Tutorial with `create-react-app` https://enlear.academy/how-to-set-up-bazel-for-a-react-app-c8a6ae6131d5
* [`rules_nodejs`](https://bazelbuild.github.io/rules_nodejs/)

* [Article Start Pt0](https://levelup.gitconnected.com/build-and-run-your-first-go-application-with-bazel-ab83acb747f5)
* [Article Start Pt1](https://levelup.gitconnected.com/build-and-run-your-first-go-application-with-bazel-ab83acb747f5)
* [Article Start Pt2](https://levelup.gitconnected.com/build-and-run-your-first-node-js-application-with-bazel-898e1a92fac5)
