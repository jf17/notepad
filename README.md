# notepad
Notepad

## build :

```bash
sudo apt install libgtk-3-dev -y
```
```bash
clang `pkg-config --cflags gtk+-3.0` -o jf17-text-editor main.c `pkg-config --libs gtk+-3.0`
```

## run :
```bash
./notepad
```
