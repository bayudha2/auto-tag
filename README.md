# AUTO TAG
#### _Auto tagging git_

## Features
- create tag on current active branch/commit and push into remote repository
- delete tag and push into remote repository

And of course Auto tag itself is open source with a [public repository][auttag]
 on GitHub.

## Usage
To use `auto-tag`, you working directory have to be in active repo with `git` in it.

how to delete tagging
```sh
auto-tag -d tag_to_delete
```
example
```sh
auto-tag -d v1.0.0
```
```sh
auto-tag -d v1.0.0,v2.0.0,v3.0.0
```

how to create tagging
```sh
auto-tag -c tag_to_create
```
example
```sh
auto-tag -c v4.0.0
```
```sh
auto-tag -c v4.0.0,v5.0.0,v6.0.0
```

## License

MIT

**Free Script, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

[auttag]: <https://github.com/bayudha2/auto-tag>
