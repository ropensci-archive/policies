## rOpenSci Policies

### Package submission

@karthik idea: We could have a web form or such that people submit along with a repo URL for us to consider. There they can check off what we consider best practices, or write a note for why they decided not to (e.g. Prefer to write long-from docs without roxygen).

* Who will decide on which packages get accepted?
* Do we gaurantee a decision within a certain amount of time? e.g., 5 days?
* Other outstanding questions?

### Package fit

This may evolve through time as the scope of rOpenSci changes, but we will consider fit. An example may be helpful. A package submitted to rOpenSci that performs only statistical analysis, albeit important, is not a great fit. Packages that might be a good fit, but are focused around government data will likely get directed towards [rOpenGov](http://ropengov.github.io/), and if focused around public health get directed to [rOpenHealth](https://github.com/ropenhealth). 

### The role of rOpenSci owners

That rOpenSci owners will not intervene much but remain helpful (e..g hey we're seeing a lot of build failures of late on Appveyor, need any help?). But occasionally we retain the right to merge a critical PR if the author is slow to respond or away.

### Package removal 

@karthik We also need to include one guideline on how to remove a package from the suite. I can't imagine why this situation would arise but good to put in our docs.

@jennybc If someone decided to "take their toys and go home", would be good to have pre-agreement on what rOpenSci would do with the project/repo/package. Keep hosting/maintaining it in the state it was at the breach on GitHub or CRAN?

### Code of Conduct

@jennybc Is there a Code of Conduct that applies to, e.g. a developer's behaviour on GitHub? I'm thinking of Linus-like or R-help jerkiness w/r/t issues or pull requests. If someone was being a public asshole, you don't want that happening in an rOpenSci-affiliated repository. I think that should actually apply to any public forum in which the person is speaking as a maintainer of the rOpenSci-affiliated project, e.g. Twitter, Stackoverflow.

### Quality commitment

@jennybc Some commitment to keeping it "build passing" or never letting it be broken for longer than x days? Or if that happens, then the repo status automatically gets set to something that informs and warns users?
