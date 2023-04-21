The original readme is [README.md](https://github.com/cleardusk/rime-ice/blob/main/README.md).

Override the default configuration by copying the files in this directory to the Rime configuration directory.

```
# ignore .git
rsync -aP --exclude '.git' ./ ~/Library/Rime/
```

Then, reload the input method.