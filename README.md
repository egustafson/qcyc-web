# Quarter Creek Yacht Club - Web Site

Statically generated using [Hugo](https://gohugo.io) and the [xmin](https://github.com/yihui/hugo-xmin) theme.

----
## Cloning this repo

+ `git clone --recursive -b hugo-source github.com:egustafson/qcyc-web`
+ ~~`git clone --recursive -b hugo-source github.com:egustafson/qcyc-web`~~

## Publishing

TBD -- not implemented yet.

1. Commit everything in the repo.   (script check for this)
2. `pub2gh.sh`
3. `cd public; git push origin master`  (echoed from pub2gh.sh)

## Clean after Publishing

1. `rm -rf public`
2. `git worktree prune`
