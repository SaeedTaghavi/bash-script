# bash-script

these are some simple bash scripts that can be used as commands if you set your `$PATH` variable.

for adding them to your `$PATH` variable you simply add the fowllowing line to your `~/.bashrc` or `~/.zshrc` 

```bash
export PATH=$PATH:/place/with/the/file
```

for example `$HOME/bin ` is a good place for there files, then you shoud add `export PATH=$PATH:$HOME/bin` to your `~/.bashrc` or `~/.zshrc`.

and also after copying the files, they should have executable permission.
`chmod +x` on a file (your script) only means, that you'll make it executable.
