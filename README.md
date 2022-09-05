# Shashank's Cheatsheet for Terminal Things

This is inspired from [technosophos](https://github.com/technosophos/vim-myhelp)

## How To Install
The cheatsheet can be used as Vim plugin. For vim-plug, add the following to your `.vimrc` or neovim's `init.vim`

`Plug 'shashanktomar/vim-myhelp'`

After that, install the plugin by running `:PlugInstall` and then you should be able to type `:h myhelp`

## Making a Change
Edit files in `/doc`. If you add new tags, make sure to run `:helpt <path-to-plugin-folder>/doc` to generate tag file
