# Alex's neovim config
A config for neovim for development on C++ with nvim.

# Keybinds
- `F3` Toggle file tree
- `F2` Source file explorer
- `F10` Next *tab* editor
- `F9` Previous *tab* editor


nnoremap <silent> <F3> <cmd>NvimTreeToggle<CR>
nnoremap <silent> <F2> <cmd>Telescope find_files<CR>
nnoremap <silent> <F10> <cmd>BufferLineCycleNext<CR>
nnoremap <silent> <F9> <cmd>BufferLineCyclePrev<CR>