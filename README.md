# Sublime Text 3 Packages

This repository is a collection of settings, packages, and plugins tailored for
my personal enjoyment. After all, what fun is web development if you hate your
primary tool?

## Installation (OS X)

1. Backup your old Sublime packages in case you have second thoughts:

    ```shell
    cp -r $HOME/Libary/Application\ Support/Sublime\ Text\ 3/Packages \
          $HOME/Libary/Application\ Support/Sublime\ Text\ 3/Packages.backup
    ```

2. Clone the repo, checkout the `sublime-3` branch, and initialize the
   submodules:

    ```shell
    git clone git://github.com/gevans/sublime-packages.git \
              $HOME/Libary/Application\ Support/Sublime\ Text\ 3/Packages \
              --branch sublime-3 --recursive
    ```

3. Install a better monospace font
   ([Envy Code R](http://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released)).

4. Restart Sublime.