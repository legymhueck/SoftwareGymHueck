# Software für die Computer am Gymnasium Hückelhoven

## GitHub Repo

- `git clone https://github.com/legymhueck/SoftwareGymHueck`
- Als Link: https://github.com/legymhueck/SoftwareGymHueck

---

## Winget

- Alle Programme, bei denen "Winget Installation" steht, lassen sich mit der in diesem GitHub Repo verfügbaren .json-Datei installatieren. Die Installation erfolgt über `winget import`, gefolgt vom Namen der .json-Datei.
- Ein Update aller Programme ist möglich mit `winget upgrade --all`.
- Eine Liste der aktuell installierten Software lässt sich exportieren mit `winget export -o`, gefolgt vom Namen der .json-Datei.
- Nähere Infos finden sich in diesem [Microsoft-Artikel](https://docs.microsoft.com/de-de/windows/package-manager/winget/).

---

## 7Zip

- NetMan Startmenü: **Zubehör**
- [Download-Link](https://www.7-zip.org)
- Winget Installation: `winget install 7zip.7zip`

---

## Adobe Acrobat Standard DC (Reader)

- NetMan Startmenü: **Office**
- [Download-Link](https://www.adobe.com/de/acrobat/pdf-reader.html)
- Winget Installation: `winget install Adobe.Acrobat.Reader.64-bit`

---

## Audacity

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.audacityteam.org/download/)
- Winget Installation: `winget install Audacity.Audacity`

---

## BiBox

- NetMan Startmenü: **Office**
- [Download-Link](https://www.bibox.schule/download/)

---

## BlueJ

- NetMan Startmenü: **Informatik**
- [Download-Link](https://www.bluej.org/)
- Winget Installation: `winget install BlueJTeam.BlueJ`

---

## DB Browser for SQLite

- NetMan Startmenü: **Informatik**
- [Download-Link](https://sqlitebrowser.org/dl/)
- Winget: `winget install DBBrowserForSQLite.DBBrowserForSQLite`

---

## Double Commander

- NetMan Startmenü: **Zubehör**
- [Download-Link](https://sourceforge.net/p/doublecmd/wiki/Download/)
- Winget Installation: `winget install alexx2000.DoubleCommander`
- Zusatzinfo: `xml`-Datei, die sich in diesem GitHub Repo findet, bitte ins Programmverzeichnis kopieren.

---

## Draw.io

- NetMan Startmenü: **Medien**
- [Download-Link](https://github.com/jgraph/drawio-desktop/releases/)
- Winget Installation: `winget install JGraph.Draw`

---

## Filius

- NetMan Startmenü: **Informatik**
- [Download-Link](https://lernsoftware-filius.de/Herunterladen)

---

## Firefox

- NetMan Startmenü: **Internet**
- [Download-Link](https://www.mozilla.org/de/firefox/all/#product-desktop-release)
- Winget Installation: `winget install Mozilla.Firefox`

---

## Foxit PDF Reader

- NetMan Startmenü: **Office**
- [Download-Link](https://www.foxit.com/downloads/#Foxit-Reader/)
- Winget Installation: `winget install Foxit.FoxitReader`

---

## Freeplane

- NetMan Startmenü: **Office**
- [Download-Link](https://docs.freeplane.org/#/getting-started/getting-started)
- Winget Installation: `winget install Freeplane.Freeplane`

---

## GeoGebra Classic 6

- NetMan Startmenü: **Mathe**
- [Download-Link](https://www.geogebra.org/download)
- Winget Installation: `winget install GeoGebra.Classic`

---

## Gimp

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.gimp.org/)
- Winget Installation: `winget install GIMP.GIMP`

---

## Git

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://git-scm.com/)
- Winget Installation: `winget install Git.Git`

---

## Google Chrome

- NetMan Startmenü: **Internet**
- [Download-Link](https://www.google.com/intl/de_de/chrome/)
- Winget Installation: `winget install Google.Chrome`

---

## Grafstat

- NetMan Startmenü: **Sowi**
- [Download-Link](https://www.grafstat.de/bezugsquellen.htm)
- Zusatzinformation: Ein Download-Link wird per Mail zugeschickt.

---

## Greenfoot

- NetMan Startmenü: **Informatik**
- [Download-Link](https://www.greenfoot.org/download)
- Winget Installation: `winget install GreenfootTeam.Greenfoot`

---

## Handbrake

- NetMan Startmenü: **Medien**
- [Download-Link](https://handbrake.fr/)
- Winget Installation:
  - `winget install Microsoft.DotNet.Runtime.6`
  - `winget install Microsoft.DotNet.DesktopRuntime.6`
  - `winget install Microsoft.DotNet.AspNetCore.6`
  - `winget install HandBrake.HandBrake`

---

## IntelliJ Community Edition

- NetMan Startmenü: **Informatik**
- [Download-Link](https://www.jetbrains.com/idea/download/#section=windows)
- Winget Installation: `winget install JetBrains.IntelliJIDEA.Community`
- Zusatzinfo: Die "idea.properties" im bin-Verzeichnis muss so angepasst werden, dass alle Einträgen (`config`, `systems`, `plugins` und `log`) auskommentiert werden und überall das Verzeichnis auf "U:\Eigene Dateien" gesetzt wird!

---

## IrfanView

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.irfanview.de/download-irfanview-64-bit-deutsche-version)
- Winget Installation: `winget install IrfanSkiljan.IrfanView`
- [Plugins](https://www.irfanview.de/download-irfanview-plugins-64-bit-deutsche-version)

---

## Java-Editor

- NetMan Startmenü: **Informatik**
- [Download-Link](https://javaeditor.org/doku.php?id=en:download)

---

## JDK8 LTS - FULL JDK

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://bell-sw.com/pages/downloads/#/java-8-lts)
- Winget Installation: `winget install BellSoft.LibericaJDK.8.Full`
- Zusatzinformations:
  - Bei *Package* die **Full JDK** wählen.
  - Nur die 64 Bit Version installieren.

---

## JDK17 LTS - FULL JDK

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://bell-sw.com/pages/downloads/#/java-17-lts)
- Winget Installation: `winget install BellSoft.LibericaJDK.17.Full`
- Zusatzinformations:
  - Bei *Package* die **Full JDK** wählen.
  - Nur die 64 Bit Version installieren.

---

## Kdenlive

- NetMan Startmenü: **Medien**
- [Download-Link](https://kdenlive.org/en/download/)
- Winget Installation: `winget install KDE.Kdenlive`

---

## KeepassXC

- NetMan Startmenü: **Zubehör**
- [Download-Link](https://keepassxc.org/download#windows)
- Winget Installation: `winget install KeePassXCTeam.KeePassXC`

---

## Krita

- NetMan Startmenü: **Medien**
- [Download-Link](https://krita.org/en/)
- Winget Installation: `winget install KDE.Krita`

---

## LibreOffice

- NetMan Start-Startmenü: **Office**
- [Download-Link](https://de.libreoffice.org/download/download/)
- Winget Installation: `winget install TheDocumentFoundation.LibreOffice`

---

## LibreOffice Hilfe Deutsch

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://de.libreoffice.org/download/download/)

---

## LibreOffice Erweiterung Rechtschreib- und Grammatikprüfung

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://extensions.libreoffice.org/en/extensions/show/languagetool)
- Zusatzinfo: Installation der heruntergeladenen .oxt-Datei in LibreOffice Writer mit *Extras -> Extension Manager -> Hinzufügen*

---

## LogikSim

- NetMan Startmenü: **Informatik**
- [Download-Link](https://logiksim.dbclan.de/download.html)

---

## Logisim

- NetMan Startmenü: **Informatik**
- [Download-Link](https://sourceforge.net/projects/circuit/files/2.7.x/2.7.1/)

---

## Logisim-Evolution

- NetMan Startmenü: **Informatik**
- [Download-Link](https://github.com/logisim-evolution/logisim-evolution/releases/tag/v3.7.2)
- Winget-Installation: `winget install logisim-evolution.logisim-evolution`

---

## MarkText

- NetMan Startmenü: **Office**
- [Download-Link](https://github.com/marktext/marktext/releases/)
- Winget Installation: `winget install MarkText.MarkText`

---

## MicroBlocks

- NetMan Startmenü: **Informatik**
- [Download-Link](https://microblocks.fun/download)

---

## MIND+ Desktop

- NetMan Startmenü: **Informatik**
- [Download-Link](https://mindplus.cc/download-en.html)
- Winget Installation: `winget install DFRobot.Mind+`
- Zusatzinfos:
  - .sb3-Dateien dürfen nicht bei Doppelklick mit dieser App verknüpft werden, sondern mit Scratch.
  - Die App startet mit chinesischer Lokalisierung. Bitte ändern und testen.

---

## MuseScore

- NetMan Startmenü: **Medien**
- [Download-Link](https://musescore.org/en)
- Winget Installation: `winget install Musescore.Musescore`

---

## Notepad++

- NetMan Startmenü: **Office**
- [Download-Link](https://notepad-plus-plus.org/downloads/)
- Winget Installation: `winget install Notepad++.Notepad++`

---

## OBS

- NetMan Startmenü: **Medien**
- [Download-Link](https://obsproject.com/de)
- Winget Installation: `winget install OBSProject.OBSStudio`

---

## Obsidian

- NetMan Startmenü: **Office**
- [Download-Link](https://obsidian.md/)
- Winget Installation: `winget install Obsidian.Obsidian`

---

## OpenShot

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.openshot.org/download/)
- Winget Installation: `winget install OpenShot.OpenShot`

---

## OpenStego

- NetMan Startmenü: **Informatik**
- [Download-Link](https://github.com/syvaidya/openstego/releases)
- Winget Installation: `winget install syvaidya.openstego`

---

## Pandoc

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://pandoc.org/installing.html)
- Winget Installation: `winget install JohnMacFarlane.Pandoc`

---

## Paint.NET

- NetMan Startmenü: **Medien**
- [Download-Link](https://github.com/paintdotnet/release/releases)

---

## PDFTK Builder

- NetMan Startmenü: **Office**
- [Download-Link](https://pdftk-builder.de.uptodown.com/windows)
- Winget Installation: `winget install AngusJohnson.PDFTKBuilder`

---

## Prowise Presenter Windows Desktop App

- NetMan Startmenü: **Office**
- [Download-Link](https://presenter10.prowise.com/downloads)
- Winget Installation: `winget install Prowise.ProwisePresenter`

---

## Prowise Reflect

- NetMan Startmenü: **Zubehör**
- [Download-Link](https://www.prowise.com/en/download-prowise-reflect/)
- Winget Installation `winget install ProwiseB.V.ProwiseReflect`

---

## PyCharm

- NetMan Startmenü: **Informatik**
- [Download-Link](https://www.jetbrains.com/de-de/pycharm/download/#section=windows)
- Winget Installation: `winget install JetBrains.PyCharm.Community`

---

## Python

- NetMan Startmenü: **kein Eintrag**
- [Download-Link](https://www.python.org/downloads/)
- Winget Installation: `winget install Python.Python.3.10`

---

## SceneBuilder

- NetMan Startmenü: **Informatik**
- [Download-Link](https://gluonhq.com/products/scene-builder/#download)
- Winget installation: `winget install Gluon.SceneBuilder.18`

---

## Scratch offline

- NetMan Startmenü: **Informatik**
- [Download-Link](https://scratch.mit.edu/download)
- Winget Installation: `winget install MITMediaLab.Scratch.3`

---

## Shotcut

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.shotcut.org/download/)
- Winget Installation: `winget install Meltytech.Shotcut`

---

## Sketchometry

- NetMan Startmenü: **Medien**
- [Download-Link](https://sketchometry.org/en/download/index.html)
- Zusatzinformations: Zwei mögliche Installationen:
  - Nur die URL verlinken: [https://start.sketchometry.org](https://start.sketchometry.org)
  - Die USB-Stick Version nehmen (unten auf der Webseite).

---

## Smart Notebook

- NetMan Startmenü: **Office**
- [Download-Link](https://www.smarttech.com/en/products/education-software/smart-learning-suite/download)
- Zusatzinformation: Nur installieren auf Boards und Lehrer-PCs

---

## SQLiteStudio

- NetMan Startmenü: **Informatik**
- [Download-Link](https://github.com/pawelsalawa/sqlitestudio/releases)
- [Webseite](https://sqlitestudio.pl)

---

## Struktogrammeditor

- NetMan Startmenü: **Informatik**
- [Download-Link](https://github.com/kekru/struktogrammeditor) (siehe unten auf GitHub-Seite: "Download via Jitpack")
- Zusatzinformations:
  - Nach Download der letzten Version die heruntergeladene Datei umbenennen in `struktogrammeditor.jar`.
  - Bei vorhandener Java-Installation wird die jar-Datei so gestartet: `java -jar struktogrammeditor.jar`
  - [Webseite](https://whiledo.de/index.php?p=struktogrammeditor)

---

## Struktogrammer

- NetMan Startmenü: **Informatik**
- [Download-Link](https://sourceforge.net/projects/struktogrammer/files/)
- Zusatzinfo: Anleitung für die Windows-Installation auf der Link-Seite weiter unten.

---

## SumatraPDF

- NetMan Startmenü: **Office**
- [Download-Link](https://www.sumatrapdfreader.org/download-free-pdf-viewer.html)
- Winget Installation: `winget install SumatraPDF.SumatraPDF`

---

## TexasInstruments.TI-Nspire.CXStudent

- NetMan Startmenü: **Mathe**
- [Download-Link](https://education.ti.com/de/software/details/en/36be84f974e940c78502aa47492887ab/ti-nspirecxcas_pc_full)
- Winget Installation: `winget install TexasInstruments.TI-Nspire.CXStudent`

---

## TigerJython4Kids

- NetMan Startmenü: **Informatik**
- [Download-Link](https://www.tigerjython4kids.ch/index.php?inhalt_links=home/navigation.inc.php&inhalt_mitte=home/einrichten.inc.php)

---

## VeraCrypt

- NetMan Startmenü: **Zubehör**
- [Download-Link](https://www.veracrypt.fr/en/Downloads.html)
- Winget Installation: `winget install IDRIX.VeraCrypt`
- Zusatzinfo: Die App startet zwar bei Schüleraccounts, aber der Laufwerksbuchstabe des gemounteten Volumes kann nicht angeklickt werden.

---

## VianaNET

- NetMan Startmenü: **Physik**
- [Download-Link](https://github.com/avosskuehler/viana/releases)
- [Webseite](http://www.viananet.de/downloads)
- Winget Installation: `winget install avosskuehler.viana`

---

## Visual Studio Code

- NetMan Startmenü: **Informatik**
- [Download-Link](https://code.visualstudio.com/docs/?dv=win)
- Winget Installation: `winget install Microsoft.VisualStudioCode`

---

## VLC

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.videolan.org/vlc/)
- Winget Installation: `winget install VideoLAN.VLC`

---

## Waveform Free

- NetMan Startmenü: **Musik**
- [Download-Link](https://www.tracktion.com/products/waveform-free)
- Zusatzinformations: Download nur möglich über Registrierung.

---

## XnView Classic

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.xnview.com/de/xnview/#downloads)
- Winget Installation: `winget install XnSoft.XnView.Classic`

---

## XNView MP

- NetMan Startmenü: **Medien**
- [Download-Link](https://www.xnview.com/de/xnviewmp/)
- Winget Installation: `winget install XnSoft.XnViewMP`

---

## yEd

- NetMan Startmenü: **Informatik**
- [Download-Link](https://www.yworks.com/products/yed/download#download)
- Choco Installation: `choco install yed`
- Scoop Installation: `scoop install yed`
- Zusatzinfos:
  - Die NRW Symbole, die unter diesem [Download-Link](https://www.schulentwicklung.nrw.de/lehrplaene/upload/klp_SII/if/MaterialZABI/yED-NRW-Palette.zip) zu finden sind, müssen nach der Installation importiert werden. Dies erfolgt über: *Bearbeiten* -> *Palette verwalten* -> *Abschnitt importieren*.
  - Danach wird in `AppData\Roaming` ein Verzeichnis namens `yWorks\yED` angelegt, welches ins Image kopiert werden muss.
