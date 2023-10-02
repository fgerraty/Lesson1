# **Reading Questions:** 

**Bryan (2017)**

-   What problems can `setwd()` cause in your scripts and how do RStudio projects address them?

    -   setwd() will not work on anyone else's devices due to unique file name strings. Rprojects address this by setting a top-level folder for a project that is relative (i.e. can be anywhere on anyone's device and still work).

-   When you call `rm(list=ls())`, what is removed from your environment? What\'s left over that restarting your R session would remove? What\'s the keyboard shortcut for restarting your R session?

    -   everything is removed from your environment (like objects, functions, etc.), but some things like working directory, loaded packages, or settings like "stringsAsFactors = FALSE" will remain. *Command+Shift+F10* (on a mac) restarts the R session.

**Braga et al. (2023)**

-   Imagine you\'re working with a few collaborators on an analysis. Come up with two examples of *Issues* you might open. How would using *Issues* differ from communicating over email?

    -   I would use *Issues* to communicate with coauthors and delegate specific code modifications suggested by a reviewer during the peer-review process.

    -   Coauthors could use *Issues* to communicate about suggestions for certain code chunks that they don't want to push without consultation.

-   What are three ways GitHub features can promote open science practices?

    -   Github features can promote open science practices by

        1.  enabling the archiving of data and code used for analyses

        2.  revealing analytical steps or raw data treatments not described in or suitable for a manuscript.

        3.  allow coauthors to understand all analyses and potentially identify scientific misconduct prior to manuscript submission.
