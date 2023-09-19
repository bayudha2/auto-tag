# AUTO TAG
#### _Auto tagging git_

## Features
- remove tag and create tag on current active branch/commit and push into remote repository
- create tag on current active branch/commit and push into remote repository

And of course Auto tag itself is open source with a [public repository][auttag]
 on GitHub.

## Usage
To use `auto-tag`, you working directory have to be in active repo with `git` in it.

how to replace tagging
```sh
auto-tag -r -c tag_to_create -d tag_to_delete
```

how to create tagging
```sh
auto-tag -c tag_to_create
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [auttag]: <https://github.com/bayudha2/auto-tag>
