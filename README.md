# git-showupstream

Shows info about defined upstreams

## Features

Accepts options like `--track` or `--verbose` to show ahead, behind info or url info respectively

## Help

See help option

```
$ git showupstream -h

git-showupstream [options] [args]

Info about defined upstreams

options:
   -v, --verbose  Show url for remote
   -t, --track    Show behind and ahead information           
   -h, --help     Show this help 

Examples:

 $ git-showupstream -v master
 $ git-showupstream -t
```

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
$ git clone https://github.com/albfan/git-showupstream.git
$ cd git-showupstream
$ ln -s $PWD/git-showupstream ~/bin/
```
