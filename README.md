# vim-editorconfigcore-windows

Repository to host the binaries for editorconfig core files on windows.

Clone this module, then reference the binary in your editorconfig-vim configuration. 

Since I clone this under vimfiles I add the following to my _vimrc 

    let g:EditorConfig_exec_path = $HOME.'\vimfiles\bundle\vim-editorconfigcore\lib\editorconfig.exe'

