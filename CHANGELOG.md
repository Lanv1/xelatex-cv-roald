# Changes in version 3
## Changes which affect regular users
- Added a new `documentclass` option `colorharmony`, which defines a new color using color harmony models. The new color is called `second` and can use this color in the document with `\color{second}`. This color is also used for the new `link{}` command, see below.
- Added a new `documentclass` option `titlecolor`, which allows you to set a separate color (compared to the header) of the titles.
- Defined a new command `\FAspace` which replaces the old length `\FAspace` (and therefore breaks compatibility with the v2 class file). Now you can use `\FAspace` directly in the document, instead of using `\hspace{\FAspace}`.
- Defined a new command `\link{someurl.com}`, which places a fontawesome logo in the document with the link. The color is detemined using the color harmony models.

# Changes in version 2
## Changes which affect regular users
- You can change the color of the header and titles using the `changecolor` option. Example: `\documentclass[changecolor={111, 156, 45}]{cv-roald}`.
- You can add a picture to the top right of the page using the command `\photo{filename}`.
- It is no longer needed to start a new table row with `\\[\vspacepar]`, now `\\` is sufficient. The row spacing is now defined globally in the class file.

## Small changes in the background
- Removed a lot of variables from the class file.
- Improved the formatting of the `.cls` and `.tex` files.