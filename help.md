# Game Lunch-optione to use:
## Disables the minmal file limits (helps to play Shadow of the Tomb Raider)
```
PROTON_NO_ESYNC=1 %command%
```

## Debug messages of Steam Proton: debug-log apprears in ~/steam\_gameid.log
```
PROTON_LOG=1 %command%
```

# Fix network-connection problems with games like Dragon-Quest(maybe obsolet now):
```
sudo ln -s /usr/lib/libgnutls.so /usr/lib/libgnutls.so26
```

# Fix flickering of the epicgames launcher (add this in lutris) as Argument
```
com.epicgames.launcher://apps/blank?silent=true
```
