## About
My vimrc file.
It sets up some customizations to make [Vim] behave nicely,
but without overwhelming shortcuts and bindings.
All the plugins are managed by [Vundle], a vim bundle manager.

## The nice thing
At opening vim, the vimrc file check if [Vundle] is present on the machine.
If not, it automagically installs it and all the declared plugins, so
that the settings are immediately ready and up-to-date on any new machine.<br>
Nice isn't it?

## Remarks
This works perfectly on Linux and _should_ work on OS X, although it has never been tested.<br>
However, on Windows, the clone of Vundle itself works, but the:

```VimL
    :BunbleInstall
```

command might be entered manually.

[Vim]:http://vim.org
[Vundle]:http://github.com/gmarik/vundle
