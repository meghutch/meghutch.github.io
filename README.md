# meghutch.github.io

------------------------------------------------------------------------

To update my personal website at meghutch.github.io:

1.  In your RStudio terminal, make sure to be on the main branch:

    `git checkout main`

2.  Make changes to .qmd files in the `meghutch-site/` directory

3.  Still on the main branch, make changes to the deployed website by running the following terminal command in RStudio:

    `quarto publish gh-pages`

The third step will automatically update branch gh-pages due to our github repo settings which name gh-pages as our default or base branch

See additional documentation [here](https://quarto.org/docs/websites/).
