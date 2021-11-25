# vim


### Operation System

Centos7


### update VIM

```bash

# download
wget https://github.com/vim/vim/archive/v8.2.1862.tar.gz

# tar
tar -zxvf  v8.2.1862.tar.gz

# compile
cd v8.2.1862
./configure --prefix=/usr/share/vim/vim82&&make && make install


# alias
alias vim='/usr/share/vim/vim82/bin/vim'
echo "alias vim='/usr/share/vim/vim82/bin/vim' " >> ~/.bashrc

# check version

vim --version



```



### Plugin manager


Unix:

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
 ```

See https://github.com/junegunn/vim-plug for detail.

```bash
# in vim
:PlugInstall
```
