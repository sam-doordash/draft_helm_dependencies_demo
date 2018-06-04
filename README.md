# draft_helm_dependencies_demo
Repository for demoing and testing Helm dependencies in a Draft project

With the current draft tasks set up, the first `draft up` fails, but the second one works.

In order for the `common` chart to be loaded correctly, the incubator charts need to be installed: https://github.com/kubernetes/charts#how-do-i-enable-the-incubator-repository
