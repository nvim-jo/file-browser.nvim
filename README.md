# file-browser.nvim

`file-browser.nvim` is a file browser extension for telescope.nvim. It supports synchronized creation, deletion, renaming, and moving of files and folders powered by [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) and [plenary.nvim](https://github.com/nvim-lua/plenary.nvim). This plugin is forked from [telescope-file-browser.nvim](https://github.com/nvim-telescope/telescope-file-browser.nvim), please use the original one.


## Optional Dependencies

- `file-browser` optionally leverages [fd](https://github.com/sharkdp/fd) if installed for faster, more async browsing
- [`nvim-web-devicons`](https://github.com/nvim-tree/nvim-web-devicons) for file icons
- `git` to show the status of files directly in the file browser.