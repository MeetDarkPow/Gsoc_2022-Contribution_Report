## May 29,2022 - May 31, 2022

Studying:

Started reading about `potools` package. 
Studied about the functions present in this package - `translate_package()`. 

Setup of `potools` package in local workspace for released version from CRAN and understood it's workflow.

Executed: 
> `install.packages("potools")`
Successful!


## June 1, 2022 - 3 June, 2022

Studying:

Studied it's various utility functions such as - `po_extract()`, `po_create()`, `po_update()` and `po_compile()`
As these functions will let you perform the individual steps related to the `translate_package()` function.
More detailed study of the package can be viewed using the `?translate_package`.
Also looked up for the workflow which are as described in `vignette("developers")` and `vignette("translators")` of `potools` package.


## June 4, 2022

Studied more about Deployment with `GitHub Actions`:

* Triggering your deployment by using the following workflow `pull_request`, `push` and `workflow_dispatch`.
`
on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  workflow_dispatch:
`
* Environments are used to describe a general deployment target like `production`, `staging`, or `development`.
* Add a status badge is in the `README.md` file of your repository.
