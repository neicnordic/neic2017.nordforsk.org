# Sources behind http://neic2017.nordforsk.org

## How to serve this page locally

Before committing changes or filing pull requests, please verify your
modifications on your computer:
```
$ jekyll serve
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


## Design decisions

- Jekyll to leverage GitHub pages
- GitHub to simplify contributions
- Separation of content (Markdown and YAML), templating (HTML and Liquid), and styling (CSS Bootstrap)
- Programmed for future reuse
- Schedule table is auto-generated from Markdown and YAML data
