
Not tested and edited


https://www.seeedstudio.com/blog/2020/03/06/prettify-raspberry-pi-shell-with-oh-my-zsh/

https://divinenanny.nl/blog/2021-08-07-install-oh-my-zsh-on-raspberry-pi/

https://www.programmerall.com/article/82321336207/

https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb

change fonts on ubuntu server

https://www.tecmint.com/change-console-fonts-in-ubuntu-server/


vim ~/.zshrc
plugins=(git zsh-autosuggestions autojump zsh-syntax-highlighting)
plugins=(git zsh-completions zsh-autosuggestions zsh-syntax-highlighting)
autoload -U compinit && compinit
