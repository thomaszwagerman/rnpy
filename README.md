# Combining R and Python for Scientific Computing

This book is currently in the "brain dump" development stage. I am collecting notes on using R and Python together as I go. This might eventually form a comprehensive book, it might not. There is currently no active effort to develop it as such.

## Deployment
After making changes, run `quarto render` before committing.  

```sh
quarto render
git add _book/*
git commit -m "publish some changes"
git push
```

This book is rendered to Github Pages from the `gh-pages` branch. This is
handled automatically by `.github/publish.yml`