# Sources behind http://neic2017.nordforsk.org

## How to serve this page locally

tl;dr:
```bash
$ jekyll serve
```

Before committing changes or filing pull requests, please verify your
modifications on your computer.

How to set up jekyll right:

1. Install rbenv and bundler
2. Use rbenv and bundler to set up Jekyll and dependencies correctly.

For longer instructions, read on below.

### Install rbenv and bundler

This site uses GitHub default packages and versions, as noted in the
[/Gemfile](/Gemfile). This lets you use rbenv with ruby-build and ruby-bundler
plugins in the next step to install correct versions of all dependencies for
you.

References:

* https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
* http://dan.carley.co/blog/2012/02/07/rbenv-and-bundler/

```bash
$ sudo apt install rbenv
$ git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
$ git clone git://github.com/carsomyr/rbenv-bundler.git ~/.rbenv/plugins/bundler
$ eval "$(rbenv init -)"
$ cd ~/.rbenv/plugins/ruby-build; git pull; cd - # optional: refresh list of available ruby versions.
$ rbenv install 2.3.3
$ rbenv global 2.3.3
$ gem install bundler # do this once for each new ruby version you install.
```

### Use rbenv and bundler to set up Jekyll and dependencies correctly

```bash
$ eval "$(rbenv init -)" # Use rbenv if you don't already.
$ git clone git@github.com:neicnordic/neic2017.nordforsk.org.git # Get the sources
$ cd neic2017.nordforsk.org
$ rbenv local 2.3.3 # This site (dir) uses this version of Ruby
$ bundle install # Set up jekyll just the way GitHub has it.
$ rbenv rehash # Ensure rbenv knows to launch the right Jekyll.
$ jekyll serve # Pages now build and serve exactly like they will on GitHub. Happy hacking!
```

## How to add new pages

Add new `*.md` files, the permalink is inferred from the file path. You may also need to add a template under `_include/*.html`.


## Which files to edit in order to modify the content

Edit the `*.md` files to edit content. Edit `_include/*.html` to edit page layout and templating.


## How to add new links to the navigation bar

Edit `_data/nav.yml`.


## Why do some paths such as `_talks` have underscores?

Because some paths contain collections and collection directories seem to have
to start with an underscore.


## How to add photos and bios of speakers and chairs

Take one of existing persons under `_people/` as example, copy, rename, and adapt. Also
add the photo under `assets/img/people/`.
Make sure to not add a 5 MB photo - reduce it to a reasonable size before pushing it to the repo.
Radovan has reduced the pictures to a width of 600 px. JPG is better (smaller) than PNG.
Verify the result locally: http://127.0.0.1:4000/people/firstname-lastname/.


## Design decisions

- Jekyll to leverage GitHub pages
- GitHub to simplify contributions
- Separation of content (Markdown and YAML), templating (HTML and Liquid), and styling (CSS Bootstrap)
- Programmed for future reuse
- Schedule table is auto-generated from Markdown and YAML data


## License

Text is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
Source code is licensed under [MPL v2.0](../gh-pages/LICENSE).
