## DoxygenToolkit for VIM
This plugin was originally created by Mathias Lorente ([see this][1]) and this repo was forked 
from [here](https://github.com/mrtazz/DoxygenToolkit.vim) where Daniel was keeping
it to easily use it as a submodule. 

### Installation
For vundle, use the following line:

    Plugin 'aymanim/DoxygenToolkit.vim'

### Configuration
(from Mathias' page) Some configuration options can be set in your `~/.vimrc`.

    let g:DoxygenToolkit_briefTag_pre="@Synopsis  "
    let g:DoxygenToolkit_paramTag_pre="@Param "
    let g:DoxygenToolkit_returnTag="@Returns   "
    let g:DoxygenToolkit_blockHeader="-------------------------------"
    let g:DoxygenToolkit_blockFooter="---------------------------------"
    let g:DoxygenToolkit_authorName="Mathias Lorente"
    let g:DoxygenToolkit_licenseTag="My own license" <-- !!! Does not end with "\<enter>"

### Thanks
Mathias Lorente for this script and @mrtazz for putting it on github. 

[1]: http://www.vim.org/scripts/script.php?script_id=987
[2]: http://github.com/mrtazz/vimfiles
