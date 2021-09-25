# Dutch version of the Patterns of Life website

This repository contains the Dutch pages for the
[Patterns of Life](https://www.patternsoflife.nl/) website, and some
shared assets for the site as a whole.

## Repositories

The entire website is generated out of three repositories:

- [patternsoflife/patternsoflife.github.io](https://github.com/patternsoflife/patternsoflife.github.io) (this repository): dutch pages and large shared assets
- [patternsoflife/en](https://github.com/patternsoflife/en): english pages
- [patternsoflife/pages-theme](https://github.com/patternsoflife/pages-theme): theme files and small shared assets

## Testing pull requests locally

To test a PR on your local system, you need to have the following software installed:

- Ruby
- Bundler

Then, you need to make sure the correct Ruby gems are installed in your test repository. Open a terminal and `cd` to your local repository's working directory. Run the following command:

```
bundle install
```

Now, whenever you want to test the branch you are working on, run the following command:

```
bundle exec jekyll serve
```

You should now be able to browse to http://localhost:4000/ to view the test version of the site. Please note the following:

- English translate links will go to the online version. You are only testing the Dutch repository locally.
- The same applies to the theme: your local version will use the online version of the theme at Github.
