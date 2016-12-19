# blockgroups

Sperren von Benutzergruppen für die Verwendung von Rabatten und/oder Gutscheinserien

Platform: Oxid eShop CE

Version: 4.8.x

###Installation:

Ordner anlegen shoproot/modules/rwu

ZIP entpacken

Ordner umbenennen nach blockgroups

SQL auf Shopdatenbank ausfühen:

```sh
CREATE TABLE oxobject_block2discount like oxobject2discount;
CREATE TABLE oxobject_block2group like oxobject2group;
```

Modul aktivieren

Views aktualisieren
