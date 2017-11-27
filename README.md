# The Developer Club's Website

This repository contains the source for the website for the Dev Club. It uses Jekyll to build the pages, so to build it, run the following command:

```
jekyll serve
```

The html files for the navbar, footer and header (contains everything in between the `<head>` tag) are located under the `_includes/` directory.

The default layout for the website is located inside `_layouts/`.

All the pages other than index.html are saved as markdown (kramdown) `.md`.

# Contributing

To contribute, fork this repository and commit changes to the fork. Then create a pull request to the `master` branch.

To update your fork with the changes in this repo, set up a remote (only needs to be run once):

```
git remote add upstream https://github.com/TheDeveloperClub/thedeveloperclub.github.io.git
```

Then to pull the commits from the main repo to your fork, run

```
git pull upstream master
```

You might have to fix some merge conflicts. If git complains about merge errors, then you might want to fix that (preferably using Atom since it is integrated with this functionality).
