# PRG.PRG web page

* People are listed in `_data/members.yml`
* Everything else is directly in `index.html`

## Debugging locally

The normal `jekyll serve --watch` does not work on Windows (using WSL), so you need magic incantation (in `start-wsl.sh`):

```
bundle exec jekyll serve --force_polling --livereload
```
