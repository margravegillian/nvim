lazy vim mine
windows setup 
# required
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

# optional but recommended
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
stdr lazy vim
git clone https://github.com/LazyVim/starter $env:LOCALAPPDATA\nvim
mine
git clone https://github.com/margravegillian/nvim.git $env:LOCALAPPDATA\nvim