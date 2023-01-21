# Gra w statki

## Instalacja
### Linux
Zainstaluj `ncurses`, `coreutils`, `make`. Na Debianie/Ubuntu:
```bash
sudo apt install libncurses5-dev libncursesw5-dev coreutils make
```  
[Instrukcje instalacji ncurses dla innych dystrybucji](https://www.cyberciti.biz/faq/linux-install-ncurses-library-headers-on-debian-ubuntu-centos-fedora)

Następnie zbuduj program komendą
```bash
make
```
  
Teraz odpal plik `statki`.


### MacOS
Potrzebny jest `gcc` (aby `#include <bits/stdc++.h>` działał). Bazowo na macOS jest zainstalowany Clang, więc trzeba doinstalować `gcc` za pomocą komendy 
```
brew install gcc
```
Dodatkowo potrzebne jest zainstalowanie biblioteki ncurses. 
```
brew install ncurses
```

Następnie zbuduj program komendą
```bash
make
```
  
Teraz odpal plik `statki`.
