# Collection of some useful bash scripts.

### Presently the list of scripts contains:
* ffmpeg-install: script for compiling and installing fresh ffmpeg (for deb-based distributions now, tested on Debian 9 and Ubuntu 16.04);
* ffmpeg-update: script for updating ffmpeg (for deb-based distributions now, tested on Debian 9 and Ubuntu 16.04);
* ffmpeg-revert: script for reverting changes made by ffmpef-install script;
* linux-post-install: script which performs Linux post-installation steps (for deb-based distributions now, tested on Debian 9 and Ubuntu 16.04);

### Where to place scripts and how to set up environment?
1. Create a folder using ```mkdir $HOME/bin```;
2. Put the scripts in ```$HOME/bin```;
3. Add the following line ```$HOME/.bashrc``` by editing with your favorite editor:
```
export PATH="$HOME/bin:$PATH"
```
When the system is looking for the command you typed, it will look in each directory
of $PATH and execute the first match it finds.

### TODO:
* make ffmpeg-install on rpm-based distributions;
* make ffmpeg-update on rpm-based distributions;
* make linux-post-install script for rpm-based distributions;
