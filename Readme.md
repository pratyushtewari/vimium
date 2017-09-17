This is my version of the customized shortcut for vimium. I wanted to use the meta key for all the shortcut that I want to I unmapped all the keys and added my custom ones.

Keyboard Bindings
-----------------

Modifier keys are specified as `<c-x>`, `<m-x>`, and `<a-x>` for ctrl+x, meta+x, and alt+x
respectively. 

For Original content please see [README.md](https://github.com/philc/vimium/blob/master/README.md)



Add these to the Custom key mappings

    unmapAll
    map <m-gg> scrollToTop
    map <m-G> scrollToBottom
    map <m-h> scrollLeft
    map <m-l> scrollRight
    map <m-r> reload
    map <m-yy> copyCurrentUrl
    map <m-p> openCopiedUrlInCurrentTab
    map <m-P> openCopiedUrlInNewTab
    map <m-f> LinkHints.activateMode
    map <m-F> LinkHints.activateModeToOpenInNewTab
    map <m-o> Vomnibar.activate
    map <m-O> Vomnibar.activateInNewTab
    map <m-b> Vomnibar.activateBookmarks
    map <m-B> Vomnibar.activateBookmarksInNewTab
    map <m-T> Vomnibar.activateTabSelection
    map <m-ge> Vomnibar.activateEditUrl
    map <m-gE> Vomnibar.activateEditUrlInNewTab
    map <m-x> removeTab
    map <m-X> restoreTab
    map <m-t> createTab
    map <m-j> previousTab
    map <m-k> nextTab
    map <c-?> showHelp
    
This will override the existing setting because of `unmapAll` but this is for me only. Please use it with caution. You can see this list of key bindings at any time by typing `<c-?>`.