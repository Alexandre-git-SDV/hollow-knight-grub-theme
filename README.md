
<h1 align="center">
  <br>
  <img src="resources/pageLogo.png" alt="Happy GRUB" width="200">
  <br>
  Hollow GRUB
  <br>
</h1>

<p align="center">
  <a href="#hollow-grub">🇬🇧 English</a> •
  <a href="#-version-française">🇫🇷 Français</a>
</p>

> [!IMPORTANT]
> **This is a recovery (backup) repository.** It preserves the original project by **sergoncano** (original author), which is no longer available: <https://github.com/sergoncano/hollow-knight-grub-theme>. All credit goes to the original author and to the contributors:
>
> <table><tr>
> <td align="center"><a href="https://github.com/CH4O7IC"><img src="https://github.com/CH4O7IC.png?size=80" width="80" alt="CH4O7IC"></a><br><a href="https://github.com/CH4O7IC">@CH4O7IC</a><br><sub>Contributor</sub></td>
> <td align="center"><a href="https://github.com/osalbahr"><img src="https://github.com/osalbahr.png?size=80" width="80" alt="osalbahr"></a><br><a href="https://github.com/osalbahr">@osalbahr</a><br><sub>Contributor</sub></td>
> </tr></table>

<h4 align="center">A theme for the bootloader GRUB based off hollow knight's main menu.</h4>

<p align="center">
  <a href="#installation">Installation</a> •
  <a href="#customization">Customization</a> •
  <a href="#credits">Credits</a>
</p>

![screenshot](resources/Showcase.gif)
## Installation
Install the files:
```bash
# Clone this repository
git clone https://github.com/Alexandre-git-SDV/hollow-knight-grub-theme.git

# Go into the repository
cd hollow-knight-grub-theme

# Run the installer
sudo ./install_theme.sh
```
Now set the theme in your grub config (```/etc/default/grub```) by adding (or modifying) the following line:
```bash
GRUB_THEME="/boot/grub/themes/hollow-grub/theme.txt"
```
Finally reload the GRUB config:
```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
<br>

Alternatively, if using **Arch Linux** you can get it from the AUR:
```bash
yay -S grub-theme-hollow-knight
```
## Customization
If you want to add a new background (the day silksong comes out), just put it in the ```wallpapers/``` directory. After that, run the install script again and choose it when prompted for.
## Credits
All the art used here belongs to the game <a href="https://www.hollowknight.com/" target="_blank">Hollow Knight</a>.<br>
The installation script is a variation of <a href="https://github.com/Lxtharia/minegrub-theme" target="_blank">minegrub</a>'s. 


---

## 🇫🇷 Version française

> [!IMPORTANT]
> **Ceci est un dépôt de récupération (sauvegarde).** Il conserve le projet d'origine de **sergoncano** (auteur original), qui n'est plus disponible : <https://github.com/sergoncano/hollow-knight-grub-theme>. Tout le crédit revient à l'auteur original et aux contributeurs :
>
> <table><tr>
> <td align="center"><a href="https://github.com/CH4O7IC"><img src="https://github.com/CH4O7IC.png?size=80" width="80" alt="CH4O7IC"></a><br><a href="https://github.com/CH4O7IC">@CH4O7IC</a><br><sub>Contributeur</sub></td>
> <td align="center"><a href="https://github.com/osalbahr"><img src="https://github.com/osalbahr.png?size=80" width="80" alt="osalbahr"></a><br><a href="https://github.com/osalbahr">@osalbahr</a><br><sub>Contributeur</sub></td>
> </tr></table>

Un thème pour le chargeur de démarrage GRUB inspiré du menu principal de Hollow Knight.

### Installation
Installer les fichiers :
```bash
# Cloner ce dépôt
git clone https://github.com/Alexandre-git-SDV/hollow-knight-grub-theme.git

# Aller dans le dépôt
cd hollow-knight-grub-theme

# Lancer l'installateur
sudo ./install_theme.sh
```
Ensuite, définir le thème dans la configuration de GRUB (```/etc/default/grub```) en ajoutant (ou modifiant) la ligne suivante :
```bash
GRUB_THEME="/boot/grub/themes/hollow-grub/theme.txt"
```
Enfin, recharger la configuration de GRUB :
```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

Sinon, sous **Arch Linux**, il est disponible sur l'AUR :
```bash
yay -S grub-theme-hollow-knight
```

### Personnalisation
Pour ajouter un nouveau fond d'écran (le jour où Silksong sortira), placez-le simplement dans le dossier ```wallpapers/```. Ensuite, relancez le script d'installation et choisissez-le quand il vous le demande.

### Crédits
Toutes les illustrations utilisées appartiennent au jeu <a href="https://www.hollowknight.com/" target="_blank">Hollow Knight</a>.<br>
Le script d'installation est une variante de celui de <a href="https://github.com/Lxtharia/minegrub-theme" target="_blank">minegrub</a>.
