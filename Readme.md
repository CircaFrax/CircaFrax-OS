<p align="center"> <img src="https://circafrax.github.io/assets/banniere.png" width="500"> </p> <h1 align="center">CircaFrax OS</h1> <p align="center"> <b>OS léger, sobre, clair pour tous.</b><br> Pas un rebrand. Un système artisanal, construit couche par couche. </p> <p align="center"> <img src="https://img.shields.io/badge/Version-1.0--dev%20BASE%20FIG%C3%89E-beige?style=flat-square" /> <img src="https://img.shields.io/badge/Base-Arch%20pur%20%7C%20linux--lts-777?style=flat-square" /> <img src="https://img.shields.io/badge/Paquets-32%20seulement-lightgrey?style=flat-square" /> <img src="https://img.shields.io/badge/Philo-Pas%20de%20Python%20dans%20le%20socle-black?style=flat-square" /> </p> <p align="center"> <img src="https://github.com/CircaFrax/CircaFrax-OS/blob/main/assets/CircaFraxOS_DVD_v1.png" width="420"> </p>
> Philosophie
Le moins d'éléments extérieurs possibles.
Base Arch pure, usage simple à la Windows. Chaque paquet a sa raison d'être.

Cible v1.0 : daily driver programmation, dualboot laptop.
Cible Mwangaza : Hyprland Kiosk offline (Kiwix) pour citoyen isolé sans internet.

📦 Socle Minimal
Couche	Détail
- Noyau	linux-lts + linux-firmware / mesa
- Init / Boot	systemd + grub + efibootmgr
- Graphique	Wayland + labwc 0.20.1 + xorg-xwayland
- Session	sddm
- Audio	pipewire + wireplumber + pipewire-pulse + pavucontrol
- Réseau	networkmanager
- Bureau	waybar (barre) / fuzzel (launcher) / foot (terminal) / swaybg + swaylock
- Base	base / base-devel / bash / sudo / git / nano / vim
- 32 paquets au total. Audit du 22/07/2026.
- Liste reproductible : base/packages-list.txt

Supprimés pour alléger : kitty, bemenu, jgmenu, wofi, hyprland (déplacé vers Mwangaza)


🗂️ Architecture
bash
/base/       -> socle reproductible
/desktop/    -> config labwc, waybar, fuzzel
/branding/   -> wallpapers, icon SUPER, themes GRUB / SDDM
/skel/       -> futur /etc/skel pour l'ISO
/iso/        -> profil archiso (à venir)


🚧 État d'avancement
Branding
>Wallpaper bureau + lock screen
- Icône SUPER + Waybar taskbar sans chevauchement
- Thème GRUB
- Thème SDDM
- Plymouth - à faire
>Système
- BASE FIGÉE CLEAN - nettoyage 8 paquets
- Architecture en couches séparées
- Installation automatisée (archiso)
- ISO reproductible CircaFrax-OS-1.0-x86_64.iso
- Stabilisation boot -> desktop
- 
🖼️ Aperçu
Screenshots à venir - VM clean

<p align="center"> <i>Prochainement captures ici : bureau vide, fuzzel ouvert, waybar</i><br> <code>assets/screenshot-desktop.png</code> </p>
📥 Télécharger
En construction active. Pas d'ISO publique pour l'instant.

-> Releases - à venir

Installation actuelle dev : VM EFI, install manuelle Arch + copie skel/.

<p align="center"> <b>CircaFrax Consortium - Admin Sans Frontières</b><br> <i>Libre d'usage. Source gardée. Comme un atelier qui prête ses outils mais garde ses plans.</i> </p>
