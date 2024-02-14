# Appendix A - Dev Notes for this Booklet Project

To upload my repo to Github, I ran:

```bash
$ gh repo create
```

To create a `gh-pages` branch in Github, I followed [this advice](https://jiafulow.github.io/blog/2020/07/09/create-gh-pages-branch-in-existing-repo/):

```bash
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Initializing gh-pages branch"
git push origin gh-pages
git checkout main # was master
```
