# Audi

## Audi Q3 8U

## MMI 3GP+R (Multi Media Interface)
- Restart (Affengriff) - **TONE** + **OK** + **obere rechte Funktionstaste**

### Engineering Menu (Red Menu) (Hidden Menu)
Es muss vorher via Script freigeschaltet werden

Funktion | Ausführung
-- | --
öffnen | **CAR** + **BACK**
beenden | **CAR**

### Developer Menu (Green Menu)

Funktion | Ausführung
-- | --
öffnen | **CAR** + **MENU**
beenden | **CAR**

### Screenshot auf die SD Karte erstellen

Funktion | Ausführung
-- | --
Screenshot | **TEL** + **MEDIA**

### MMI FSC Keys sichern (Red Menu)
Sichern der Keys auf der Unit mit:

SYSTEM > Activation Keys > Export Keys > SD1
Einspielen der gesicherten Keys dann mit: SYSTEM > Activation Keys > Import Keys > SD1

### Make sure that MMI is fully booted
(press all buttons once RADIO CAR NAV MEDIA TEL). 
Wait until all options are working (no options in gray) even when all options are working
wait a minute more.

## Firmware Upgrade
- Ein Firmwareupgrade kann direkt auf die höhste Version ohne Zwischenschritte erfolgen.
- nach dem Firmwareupdate kann man wieder Enable_Green_Menu einsppielen
- ein MicroSD > SD-Karen Adapter ist problemlos möglich
- 64GB Karten können funktionieren (es gibt keine Probleme, entweder wird es erkannt oder nicht)
- 64GB unter Windows mit FAT32 mit ##guiformat64.exe ist problemlos möglich

## Karten Update
- das Update dauert wirklich ca. 1.5h ! Deshalb nur mit angeschlossenen Ladegerät durchführen
- es wird dabei 2-3 gebootet, die Karte kann drin bleiben
- bei Boose Sound System - benutzerdefiniertes Update durchführen (zuvor im REG Menu ohne reboot es freischalten)

AKtivierung
- MAC Adresse auslesen
- in XCodeCalculator.html einfügen 
- und die Datei entsprechne umbenennen in Vlasoff maps activation 2016-2017-2018.rar

HEX V2
- Hinweis: Ab Version 08.023.04 läuft der Loader nicht mehr in einer virtuellen / virtualisierungsfähigen Umgebung und es kann auch kein Downgrade der Firmware mehr erfolgen!

