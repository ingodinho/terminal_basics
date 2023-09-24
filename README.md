# Terminal Basics

Hier möchten wir euch kurz die wichtigsten Terminal-Befehle bezüglich der Interaktion mit dem Filesystem vorstellen, die wir im Bootcamp nutzen werden.

### `pwd` - Print Working Directory
Der Befehl `pwd` zeigt den aktuellen Arbeitsverzeichnis-Pfad an.
```bash
pwd
```

### `ls` - List
Mit dem Befehl `ls` könnt ihr den Inhalt des aktuellen Verzeichnisses auflisten.
```bash
ls # Zeigt die Ordner und Dateien im Verzeichnis an
ls -la # Zeigt alle, auch die versteckten, Dateien und Ordner im Verzeichnis strukturiert an
```

### `cd` - Change Directory
Der Befehl `cd` ermöglicht das Wechseln in ein anderes Verzeichnis. Ihr könnt entweder den vollständigen Pfad angeben oder relative Pfade verwenden.
```bash
cd Verzeichnisname          # In ein Verzeichnis wechseln
cd ..                      # Ins übergeordnete Verzeichnis wechseln
cd ~                       # Ins Benutzerverzeichnis wechseln
```

## Dateien und Ordner erstellen

### `touch` - Dateien erstellen
Der Befehl `touch` erstellt eine leere Datei mit dem angegebenen Namen.
```bash
touch dateiname.txt
```

### `mkdir` - Ordner erstellen
Mit `mkdir` können ihr ein neues Verzeichnis erstellen.
```bash
mkdir ordnernamen
```

## Dateien und Ordner umbenennen

### `mv` - Move/Rename
Der Befehl `mv` wird sowohl zum Verschieben von Dateien/Ordnern als auch zum Umbenennen verwendet. Gebt den alten Pfad/Namen und den neuen Pfad/Namen an.
```bash
mv altername neuername     # Umbenennen
mv datei.txt Verzeichnis   # Verschieben in ein anderes Verzeichnis
```

## Dateien und Ordner löschen

### `rm` - Remove
Der Befehl `rm` löscht Dateien. Vorsicht: Dateien werden dauerhaft gelöscht und können nicht wiederhergestellt werden.
```bash
rm datei.txt
```

### `rmdir` - Remove Directory
Der Befehl `rmdir` löscht ein leeres Verzeichnis.
```bash
rmdir verzeichnisname
```

### `rm -r` - Recursive Remove
Um ein Verzeichnis und dessen Inhalt rekursiv zu löschen, verwendet `rm -r`. Achtet darauf, diesen Befehl mit Vorsicht zu verwenden, da der Inhalt endgültig gelöscht wird.
```bash
rm -r verzeichnisname
```