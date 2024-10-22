### Editor checks:

- [X] **Documentation**: The package has sufficient documentation available online (README, pkgdown docs) to allow for an assessment of functionality and scope without installing the package. In particular,
    - [X] Is the case for the package well made?
    - [X] Is the reference index page clear (grouped by topic if necessary)?
    - [X] Are vignettes readable, sufficiently detailed and not just perfunctory?
- [X] **Fit**: The package meets criteria for [fit](https://devguide.ropensci.org/policies.html#package-categories) and [overlap](https://devguide.ropensci.org/policies.html#overlap).
- [X] **Installation instructions:** Are installation instructions clear enough for human users?
- [X] **Tests**: If the package has some interactivity / HTTP / plot production etc. are the tests using [state-of-the-art tooling](https://devguide.ropensci.org/building.html#testing)?
- [X] **Contributing information**: Is the documentation for contribution clear enough e.g. tokens for tests, playgrounds?
- [X] **License:** The package has a CRAN or OSI accepted license.  
- [X] **Project management**: Are the issue and PR trackers in a good shape, e.g. are there outstanding bugs, is it clear when feature requests are meant to be tackled?

---

#### Editor comments

Thanks for the submission @willgearty, I am keen to help on this review!

All above looks good to me. Some minor comments below, the authors could 
consider working on while we are looking for reviewers. 

- The README has a great introductory paragraph, installation instructions, 
and meta information. It could use a brief demonstration usage, see [here](https://devguide.ropensci.org/pkg_building.html#readme).
- The introductory vignette covers installation, authentication, high level 
and low level interface and best practices. It might be helpful to have a general overview of the available functions or groups of functions in {rredlist}. 
- Good to see tests for {rredlist} use {vcr} for HTTP testing. In
[CONTRIBUTING.md](https://github.com/ropensci/rredlist/blob/master/.github/CONTRIBUTING.md), 
the authors could consider including a note about how testing is different in
{rredlist} due to HTTP requests, maybe by linking to {vcr} and 
[HTTP testing in R](https://books.ropensci.org/http-testing/index.html)? This might help interested contributors to get familiar with HTTP testing. 
- One minor note from {goodpractice}:  
    
    ```
    tests/testthat/test-rl_threats.R
    Line 82 avoid sapply(), it is not type safe.
          It might return a vector, or a list, depending on the
          input data. Consider using vapply() instead.
    ```

