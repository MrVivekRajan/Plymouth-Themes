# Previews

<details><summary>Style-1</summary>

# Anonymous  
![Image](https://github.com/user-attachments/assets/274056c0-92f1-40b2-b850-eee5d78679bd)

# Eye
![Image](https://github.com/user-attachments/assets/4cb532f3-ef57-456b-879e-9089a9d5e3a1)

# Error
![Image](https://github.com/user-attachments/assets/8a521ae0-27ee-4913-ac7c-4666206560b9)

# DC-Marvel 
![Image](https://github.com/user-attachments/assets/02ac0d10-5818-4d80-9a85-126161ed6a22)

</details>

<details><summary>Style-2</summary>

# Bsol   
![plymouth ](https://github.com/user-attachments/assets/ea6b1579-eda4-435b-bb8f-47868fdfc21e)

# Jam (Just A Moment)
![jam](https://github.com/user-attachments/assets/21d0d9a7-770b-44e6-83ca-0ae6a88477d0)
</details>

# Installation
- Install plymouth on your distro by following guide written on your distro's wiki page or search on the internet. Do follow each and every steps properly.
  
  [Arch](https://wiki.archlinux.org/title/Plymouth)  [Debian](https://wiki.debian.org/plymouth)  [Ubuntu](https://wiki.ubuntu.com/Plymouth) [Linux-Mint](https://community.linuxmint.com/tutorial/view/646)  [Nix-OS](https://wiki.nixos.org/w/index.php?title=Plymouth&mobileaction=toggle_view_desktop)  [Gentoo](https://wiki.gentoo.org/wiki/Plymouth)  [EndeavourOS](https://forum.endeavouros.com/t/guide-how-to-install-and-use-plymouth/51363)  [Fedora](https://discussion.fedoraproject.org/t/enable-plymouth-startup/70079)  [MX-Linux](https://mxlinux.org/wiki/system/add-plymouth-to-mx-linux/)  [Manjaro](https://wiki.manjaro.org/index.php/Plymouth)  [oepnSUSE](https://en.opensuse.org/openSUSE:Plymouth)   

- Once you installed plymouth make sure that you have a themes folder inside /usr/share/plymouth/ if not then create one
```
sudo mkdir /usr/share/plymouth/themes/
```

- Clone this repository 
```
git clone https://github.com/MrVivekRajan/Plymouth-Themes.git
```

- After cloing it just copy and paste your desired Plymouth Theme to `/usr/share/plymouth/themes/`

- Now just set it as default Plymouth theme and make sure to rebuild `initrd` for that just use commands given below:-

- For Bsol-Theme 
```
sudo plymouth-set-default-theme Bsol -R 
```
- For Jam-Theme 
```
sudo plymouth-set-default-theme Jam -R 
```

# Also Available At:-
- [Pling](https://www.pling.com/p/2216301/)

- [Gnome-Look](https://www.gnome-look.org/p/2216301)

# Credits  
- [K Harishnkr](https://github.com/harishnkr) - For Blue Screen of Life Idea
- [Mauro Meloni](https://gitlab.com/maurom) - For circular loading animation

# Thanks for Visiting !! ❤️❤️
I Hope You Like my project, if yes then don't forget to give it a star as it means a lot.
<h4> <span>· </span> <a href="https://github.com/MrVivekRajan/Plymouth-Themes/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/MrVivekRajan/Plymouth-Themes/issues"> Request Feature </a> </h4>
