Instructions on how to save and restore dconf settings

ref: https://askubuntu.com/questions/984205/how-to-save-gnome-settings-in-a-file

save to a ini file:

```
dconf dump / > dconf-settings.ini
```

load from the ini file:
```
dconf load / < dconf-settings.ini
```

