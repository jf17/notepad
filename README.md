# notepad
Notepad

## build :

```bash
sudo apt install libgtk-3-dev -y
clang `pkg-config --cflags gtk+-3.0` -o notepad notepad.c `pkg-config --libs gtk+-3.0`
```

## run :
```bash
./notepad
```
