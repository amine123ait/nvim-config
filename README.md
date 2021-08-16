# nvim-config

## dependisis 
```bash
#!/bin/bash
apt install xsel
pip3 install pynvim
apt install npm
apt install nodejs
apt install watchman 
npm i -g yarn
npm i -g neovim
```


## setup
1. install neovim ```apt install neovim```
2. store this in ~/.config ; if u dont have it just create one (```mkdir ~/.config```)
3. copy nvim to ~/.config ; ```cp -r ./nvim ~/.config/```
4. then open neovim and check if there is any errors ```nvim file``` ; ```:PlugStatus``` and ```:checkhealth```
5. Install and update all of your plugins ```:PlugInstall``` ; ```:PlugUpdate```
6. clean ```:PlugClean```
9. Finally if you want to upgrade vim-plug itself run the following ```:PlugUpgrade```




<p align="center">
<img src="https://media.giphy.com/media/l1J9FXB7QTlNICvT2/giphy.gif">
</p>