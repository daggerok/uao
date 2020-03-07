# uao
Unzip archive and open in IDEA IDE

## install

```bash
git clone --depth=1 --no-single-branch git@github.com:daggerok/uao.git ~/.opt/uao
chmod +x ~/.opt/uao/uao # git update-index --chmod=+x ./uao
mkdir ~/.bin
ln -s `pwd`/.opt/uao/uao ~/.bin/uao
echo 'export PATH="$PATH:$HOME/.bin"' >> ~/.bas_profile # or ~/.bashrc # or ~/.zshrc
```

## usage

* make sure you have `idea` and `unzip` binaries installed on you `macOS` or `Linux` shell (click-click if you on windows:)
* generate new project on https://start.spring.io/
* open it like Josh Long :)
  ```bash
  uao ~/Downloads/demo.zip
  ```

Enjoy ;)
