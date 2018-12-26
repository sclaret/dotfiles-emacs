# Enable melpa

```
~/.emacs.d/init.el

(require 'package)
(add-to-list 'package-archives
             '("melpa-stable" . "http://stable.melpa.org/packages/") t)
```


# Install packages

```
M-x list packages
magit
```


# Initialize packages

```
~/.emacs.d/init.el

(global-set-key (kbd "C-x g") 'magit-status)
```

# Help

Key Sequence | Command
--- | ---
C-h C-h | help
M-x | run command
C-g | quit



# Reference

- [Guide](http://www.jesshamrick.com/2012/09/10/absolute-beginners-guide-to-emacs/)