# EndeavourOS-Setup-from-scratch

EndeavourOS is an arch based linux distro that is considered the most beginner friendly distros for anyone interested in using arch. Here I'll be setting up endeavourOS from scratch so if your new to using this OS you can follow along.

<h>Step 1: Setup the Mirrorlist</h>

<img width="1221" height="383" alt="Screenshot_20261017_113414" src="https://github.com/user-attachments/assets/41552bbc-64bb-4886-be2b-9156c83d3b5f" />

The first thing your gonna wanna do is setup the mirrorlist so you can actually install programs or software into your machine. Open your terminal and type this command: sudo curl -o /etc/pacman.d/mirrorlist "https://archlinux.org/mirrorlist/?country=ZA&protocol=https&use_mirror_status=on"

The "country=ZA" in the command can be changed to whatever server closest to your country. I choose ZA because it is the closest server to my location.

<img width="1219" height="407" alt="Screenshot_20261017_113849" src="https://github.com/user-attachments/assets/5406af8d-765f-46b7-9da0-9b4760a15ea0" />

After that type sudo pacman -Syu. This will update your system and reveal if the first command was successful or not. In my case it did not work so we'll try a slightly different to setup mirrorlist. Type: cat /etc/pacman.d/mirrorlist

<img width="1220" height="697" alt="image" src="https://github.com/user-attachments/assets/5a91054e-dd3c-45da-9861-7234a5ad891d" />

As you can see this command went through meaning that setting up the mirrorlist was successful
