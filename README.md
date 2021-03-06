# GitHub Projects Story Points

A Chrome Extension to add [SCRUM](https://en.wikipedia.org/wiki/Scrum_(software_development))
[story points](https://en.wikipedia.org/wiki/Planning_poker) pretty display to
[GitHub Projects](https://help.github.com/articles/about-projects/).

![Example screenshot](./screenshot.png)

You notes/PR/issues should have a title like `My issue title (2)` and the "(2)"
will be converted in a nice tag. Also all projects lists will have the total count
of story points in them next to the count of cards.

Examples:
* `Issue title (2)` -> `0 spent of 2`
* `Issue title (3/8)` -> `3 spent of 8`
* `Issue title (0.5/8.0)` -> `0.5 spent of 8`

## To Install

1. Download all the files in the directory.
1. Launch Chrome
1. Open chrome://extensions/
1. Make sure "Developer mode" is CHECKED
1. Click "Load unpacked extension..."
1. Select the directory you downloaded all the files to.

**GitHub Projects Story Points** should now appear in your Extensions lists

1. Reload the extension page or click the "Reload" link under **GitHub Projects Story Points**
1. Open your Projects or Issues pages in your Repo on GitHub.com
1. You should now see any items with `(#)`` as a suffix in the title added up as (# points)`
