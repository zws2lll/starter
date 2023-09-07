# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.
# docker

docker run -w /workspace -it -v $(pwd):/workspace alpine:edge sh -uelic '
  apk add fd gzip perl ruby unzip npm python3 py3-pip neovim-doc git lazygit neovim ripgrep alpine-sdk --update
  python3 -m venv /root/python/venv
  . /root/python/venv/bin/activate
  Pip install 
  git clone https://github.com/LazyVim/starter ~/.config/nvim
  cd /workspace
  bash
'
