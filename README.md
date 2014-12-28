# git-showupstream

Shows info about defined upstreams

## Features

Accepts options like `--track` or `--verbose` to show ahead, behind info or url info respectively

## Examples

    $ git showupstream
    master -> origin/master
    $ git showupstream -t
    master -> origin/master =
    $ git showupstream -v
    master -> origin/master git@github.com:albfan/git-showupstream.git


## Install

Download and symlink to your path

```bash
$ git clone git@github.com:albfan/git-showupstream.git
$ cd git-showupstream
$ ln -s $PWD/git-showupstream ~/bin/
```
