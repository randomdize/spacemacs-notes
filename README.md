# spacemacs-notes

# setup
line number `dotspacemacs-line-numbers 'relative`  
powerline color in `user-config` `(setq powerline-image-apple-rgb t)`  

# useful keybinding
## spacemacs
edit config `SPC f e d`  
project search `SPC p p`  
open file in project `SPC p f`  
cancel command `C-g`  
command list `C-x` or `SPC SPC`  
restart emacs `SPC q R`  

## magit
clone repo `SPC SPC magit-clone`  
magit menu `SPC g m`  
open a magit status window `SPC g s`  
stage current file `SPC g S`  
git status `SPC g s`  

### In status
unstage `u`  
stage `s`  
commit `c` 

## multi-term
open term `SPC SPC multi-term`  
exit `ESC`  

## buffer
new buffer `SPC b N`  
next buffer `SPC b n`  
previus buffer `SPC b p`  
buffer list `SPC b h`  

## HELM
find file `C-x C-f`  

# Error 
`find ~/.emacs.d/elpa/ -name "*etc" -delete`  
