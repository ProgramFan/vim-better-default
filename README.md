# vim-better-default

There are some general settings for convenience in almost everyone's `.vimrc` file. Let's shorten your `.vimrc` and make the default vim better.

## [中文简介](https://liuchengxu.github.io/2016/10/31/my-first-vim-plugin.html)

## Features

- **Out-of-the-box**: address a ton of deficiencies of the default vim configurations that nearly everyone can agree upon.

- **Mnemonic key bindings**: commands have mnemonic prefixes like `<Leader> b` for the buffer commands or `<Leader> w` for the window commands. `SPC` key is recommended as the leader key.

If new to Vim, you can install [vim-better-default](https://github.com/liuchengxu/vim-better-default) as a starting point, rather than copying some random vimrc you found.

If you have been a vimer for quit a while, please see [default.vim](https://github.com/liuchengxu/vim-better-default/blob/master/plugin/default.vim) directly. At the beginning [vim-better-default](https://github.com/liuchengxu/vim-better-default) is intended for simplifying the tedious `.vimrc` file , so you may also use it to shorten your `.vimrc`.

## Installation

This plugin can be installed with a varity of plugin managers, such as:

- [Vundle](https://github.com/VundleVim/Vundle.vim)
    - `Plugin 'liuchengxu/vim-better-default`
- [Plug](https://github.com/junegunn/vim-plug)
    - `Plug 'liuchengxu/vim-better-default`

## Options

- `vim_better_default_minimum`

- `vim_better_default_key_mapping`

    - `vim_better_default_basic_key_mapping`

    - `vim_better_default_buffer_key_mapping`

    - `vim_better_default_file_key_mapping`

    - `vim_better_default_fold_key_mapping`

    - `vim_better_default_window_key_mapping`



If you set the `vim_better_default_minumum` option, then vim seemingly looks like no difference with the default vim, it only adds some essential funtionalities.

```
let g:vim_better_default_minimum = 1
```

If you want to exclude key mappings in [vim-beter-default](https://github.com/liuchengxu/vim-better-default), just set the value as 0.

```
let g:vim_better_default_key_mapping = 0
```

For more details, please refer to the [default.vim](https://github.com/liuchengxu/vim-better-default/blob/master/plugin/default.vim). Don't worry. It is extremely simple and just part of your own `.vimrc` file alike.

You can also fork [vim-beter-default](https://github.com/liuchengxu/vim-better-default) and modify `plugin/default.vim` for more customization.

## Contributions

If you have any ideas or suggestions to improve [vim-better-default](https://github.com/liuchengxu/vim-better-default), please fork it and send a pull request. Your feedback is highly appreciated. 

[vim-better-default](https://github.com/liuchengxu/vim-better-default) needs *you* !

## Inspired by

- [spacemacs](https://github.com/syl20bnr/spacemacs)
- [better-defaults](https://github.com/technomancy/better-defaults)
- [vim-sensible](https://github.com/tpope/vim-sensible)
- [space-vim](https://github.com/liuchengxu/space-vim)
