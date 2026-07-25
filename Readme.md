<p align="center"> <img src="https://circafrax.github.io/assets/banniere.png" width="500"> </p>
CircaFrax OS
<p align="center"> <img src="https://github.com/CircaFrax/CircaFrax-OS/blob/main/assets/CircaFraxOS_DVD_v1.png" width="420"> </p>
OS léger, sobre, clair pour tous.
Pas un rebrand. Un système artisanal, construit couche par couche. Base Arch pure, usage simple à la Windows.

Philosophie : le moins d'éléments extérieurs possibles. Pas de Python dans le socle.

Télécharger
En construction - Base figée
-> Releases à venir

Spécificités
CircaFrax OS n'est pas une surcouche. C'est un socle refait à la main.

Noyau : linux-lts - stabilité daily driver
Init : systemd
Graphique : Wayland + labwc 0.20.1 (léger, stable, sans fioritures)
Session : SDDM - login clair
Audio : PipeWire + WirePlumber
Réseau : NetworkManager
Bureau : foot (terminal), fuzzel (launcher), waybar (barre), swaybg / swaylock
32 paquets seulement.
Pas de superflu. Chaque paquet a sa raison.

base base-devel linux-lts linux-firmware grub efibootmgr
networkmanager pipewire wireplumber
labwc waybar foot fuzzel swaybg swaylock sddm
...
Liste complète reproductible : base/packages-list.txt

Structure du projet
/base/      -> socle reproductible
/desktop/   -> config labwc, waybar, fuzzel
/branding/  -> wallpapers, icônes, thèmes GRUB / SDDM
/skel/      -> futur /etc/skel pour l'ISO
/iso/       -> profil archiso (à venir)
État d'avancement - v1.0-dev BASE FIGÉE (22/07/2026)
Branding :

 Wallpaper bureau + lock
 Icône SUPER + Waybar taskbar
 Thème GRUB
 Thème SDDM (prêt)
 Plymouth
Système :

 Base gelée et nettoyée (-8 paquets)
 Architecture en couches
 Installation automatisée (archiso)
 ISO reproductible CircaFrax-OS-1.0-x86_64.iso
 Stabilisation boot -> desktop
Cible v1.0 : daily driver programmation, dualboot laptop.
Cible future Mwangaza : Hyprland Kiosk (Kiwix offline) pour citoyen isolé sans internet.

Installation
Actuellement : installation manuelle Arch en VM EFI + copie du skel/.

Bientôt : flash l'ISO et boot.

CircaFrax Consortium - Admin Sans Frontières

Libre d'usage. Source gardée. Comme un atelier qui prête ses outils mais garde ses plans.

