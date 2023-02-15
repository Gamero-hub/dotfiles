# dotfiles 
<em> # Dotfiles </em>
<h1>How To Install</h1>

First 

- First, install the primary key - it can then be used to install our keyring and mirrorlist:
  - `# pacman-key --recv-key FBA220DFC880C036 --keyserver keyserver.ubuntu.com`
  - `# pacman-key --lsign-key FBA220DFC880C036`
  - `# pacman -U 'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-keyring.pkg.tar.zst' 'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-mirrorlist.pkg.tar.zst'`
- Eddit and add `/etc/pacman.conf`:
  - `[chaotic-aur]`
  - `Include = /etc/pacman.d/chaotic-mirrorlist`

Next, Run the  look at the howtoinstall.txt
