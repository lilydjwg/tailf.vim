tailf.vim is a simple Vim 8 plugin to do things like "tail -f" in Vim asynchronously.

Why tailf.vim?

1. Asynchronous output. No need to move the cursor to see the update.
2. Highlighted and searchable like any other ordinary buffers in Vim.

How to use?

1. `:Tailf filename` to do a `tail -f fileneme` in current window
2. `:TailfCmd command` to run and view the output in current window. For example, to view systemd's journal: `:TailfCmd journalctl -fn`

Status:

This plugin is in its alpha stage. You may meet bugs sooner or later. Patches and pull requests are welcome!
