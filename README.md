# tmx
My version of famous script tmux-sessionizer from ThePrimeagen

## Config File ----------
Default path for configuration file is ~/.config/tmx/tmx.conf.
There's just one field:

```
path=(/home/{your-user/...}) -> do not use $HOME or any variable
```
Default setting for path is DEFAULT_PATH=($HOME $HOME/personal/)

## Layout File
An important feature of tmx is the layout configuration file. In there, you can set name for your windows and commands to execute in first time getting in a session/path. Here an example from my books dir/session.

```
windows=(nvim-books glow-books term)
commands=(nvim glow zsh)
```

You just have to input name of the window in *windows* and the command in commands. It's important to say that windows and commands must have the same length.

