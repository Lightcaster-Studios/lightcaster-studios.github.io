# Lightcaster Studios Site

Website for project documentation etc.

## Contributing

To contribute...
1. Ensure you have Ruby installed
2. Ensure you have Jekyll installed, [follow the instructions in Jekyll docs](https://jekyllrb.com/docs/)
3. Clone this repo, ensure you're on another branch
4. Delete the local `Gemfile.lock` to ensure that you have a fresh file when installing gems later (Will cause errors if skipped)
5. Run `bundle install` to install gems
6. Run `bundle exec jekyll s` and site will be hosted on `localhost:4000`

### Creating Pages

All names of `.md` files in the root directory correspond to the name of their links, e.g. For the page `/beamerman`, the file to edit the contents of the page are at `/beamerman.md` in this directory. For the page `beamerman/how-to-play`, the contents of the page are at `beamerman/how-to-play.md`.

If you want to create a new link, e.g. `/beamerman/about`, create a new `.md` file at `/beamerman/`.

### Creating Blog posts

Blog posts can be created under the `/_post` folder. Create a new `.md` file with the following naming convention `YYYY-MM-DD-title`. From there, use the layout `post` to write a blog post. A sample post file can be found inside the same folder for reference.

### Editing Layout

This site is styled using [bulma](https://bulma.io/documentation/), to change page styles, please read the docs.

### Credits

Theme is WhatATheme by [thedevslot](https://github.com/thedevslot/WhatATheme) 