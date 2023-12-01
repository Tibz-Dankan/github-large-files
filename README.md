# github-large-files

Send large files to github

## Get started

## Install `lfs` tool visiting the site `https://git-lfs.com`

## verify install of `lfs`

```.bs
git lfs install

```

## specify the files to be tracked by `lfs`

```.bs
git lfs track ".file-extention-name"

```

## Now make sure .gitattributes is tracked:

```.sh
git add .gitattributes
```

### Example

```.bs
git lfs track ".apk"

```

## Specify the git branch to deploy the large file

```.bs
git lfs push --all origin  main

```

## Then other normal git operations continue...
