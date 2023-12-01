# github-large-files

Send large files to github

## Get started

## Install `lfs` tool using command below

```.bs
git lfs install

```

## specify the files to be tracked by `lfs`

```.bs
git lfs track ".file-extention-name"

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
