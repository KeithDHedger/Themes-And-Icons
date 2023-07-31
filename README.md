# Themes

To checkout just the theme/iconset you want do:<br>
git clone -n https://github.com/KeithDHedger/Themes-And-Icons.git  --depth 1<br>
git checkout HEAD nouveGnomeSteel<br>

Themes ending in 'QT' have been tweaked to integrate QT5 and gtk better there is also a *-qt5ct.conf file in the main folder of the theme which you should put in ~/.config/qt5ct/colors for use with the QT5 Settings app.

To keep download/repo sizes at a managable size, only one size of icons are included in each theme, to generate extra icon sizes cd into the relevent folder and run the 'addsizes' script from the main repo eg:
For instance.
cd /tmp
git clone -n https://github.com/KeithDHedger/Themes-And-Icons.git  --depth 1
cd Themes-And-Icons/
git checkout HEAD nouveGnomeSteel
git checkout HEAD addsizes
cd nouveGnomeSteel
../addsizes scalable "16 22 24 32 48"

Then just copy the 'nouveGnomeSteel' folder to your icon folder, local is ~/.icons or global is /usr/shar/icons.

This will build the extra sizes from the scalable folder ( some icon themes use the folder 256x256 )
You will need ImageMagick installed for this, most distros install it as standard.

BUGS etc.<br>
kdhedger68713@gmail.com<br>

**Themes for LFSDesktop and Xfce4**<br>

Captain America.<br>
![Alt text](pics/CaptainAmerica.png?raw=true "Captain America")<br>
All Hallows Eve.<br>
![Alt text](pics/AllHallowsEve.png?raw=true "All Hallows Eve")<br>
Fear And Mystery.<br>
![Alt text](pics/FearAndMystery.png?raw=true "Fear And Mystery")<br>
Fear And Mystery Rage.<br>
![Alt text](pics/FearAndMysteryRage.png?raw=true "Fear And Mystery Rage")<br>
Old Brown Wood.<br>
![Alt text](pics/OldBrownWood.png?raw=true "Old Brown Wood")<br>
Old Wood And Brass.<br>
![Alt text](pics/OldWoodAndBrass.png?raw=true "Old Wood And Brass")<br>
Old Wood And Steel.<br>
![Alt text](pics/OldWoodAndSteel.png?raw=true "Old Wood And Steel")<br>
Oldy Xmas Theme.<br>
![Alt text](pics/OldyXmasTheme.png?raw=true "Oldy Xmas Theme")<br>
Wood ThemeR ustic.<br>
![Alt text](pics/WoodThemeRustic.png?raw=true "Wood Theme Rustic")<br>
Wood Theme Smooth.<br>
![Alt text](pics/WoodThemeSmooth.png?raw=true "Wood Theme Smooth")<br>
Winter Wood.<br>
![Alt text](pics/WinterWood.png?raw=true "Winter Wood")<br>
Spring Wood.<br>
![Alt text](pics/SpringWoodQT.png?raw=true "Spring Wood")<br>

**Icon sets for LFSDesktop and Xfce4.**<br>

Fear And Mystery Icons.<br>
![Fear And Mystery Icons](pics/FearAndMysteryIcons.png?raw=true "Fear And Mystery Icons")<br>
Fear And Mystery Rage Icons.<br>
![Fear And Mystery Rage Icons](pics/FearAndMysteryRageIcons.png?raw=true "Fear And Mystery Rage Icons")<br>
Halloween Icons.<br>
![Halloween Icons](pics/HalloweenIcons.png?raw=true "Halloween Icons")<br>
nouveGnomeBrass.<br>
![nouveGnomeBrass Brass](pics/nouveGnomeBrass.png?raw=true "nouveGnomeBrass Brass")<br>
nouveGnomeSteel.<br>
![nouveGnome Steel](pics/nouveGnomeSteel.png?raw=true "nouveGnome Steel")<br>
Old Brown Wood Icons.<br>
![Old Brown Wood Icons](pics/OldBrownWoodIcons.png?raw=true "Old Brown Wood Icons")<br>
Old Grey Wood Icons.<br>
![Old Grey Wood Icons](pics/OldGreyWoodIcons.png?raw=true "Old Grey Wood Icons")<br>
Old Winter Wood Icons.<br>
![Old Winter Wood Icons](pics/OldWinterWoodIcons.png?raw=true "Old Winter Wood Icons")<br>
Spring Wood Icons.<br>
![Spring Wood Icons](pics/SpringWoodIcons.png?raw=true "Spring Wood Icons")<br>
Wood Icons.<br>
![Wood Icons](pics/WoodIcons.png?raw=true "Wood Icons")<br>
Xmas Icons.<br>
![Xmas Icons](pics/XmasIcons.png?raw=true "Xmas Icons")<br>


