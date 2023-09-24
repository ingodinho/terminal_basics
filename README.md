# Terminal Basics

### `pwd` - Print Working Directory
Der Befehl `pwd` zeigt den aktuellen Arbeitsverzeichnis-Pfad an.
```bash
pwd
```

### `ls` - List
Mit dem Befehl `ls` können Sie den Inhalt des aktuellen Verzeichnisses auflisten.
```bash
ls # Zeigt die Ordner und Dateien im Verzeichnis an
ls -la # Zeigt alle, auch die versteckten, Dateien und Ordner im Verzeichnis strukturiert an
```

### `cd` - Change Directory
Der Befehl `cd` ermöglicht das Wechseln in ein anderes Verzeichnis. Sie können entweder den vollständigen Pfad angeben oder relative Pfade verwenden.
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
Mit `mkdir` können Sie ein neues Verzeichnis erstellen.
```bash
mkdir ordnernamen
```

## Dateien und Ordner umbenennen

### `mv` - Move/Rename
Der Befehl `mv` wird sowohl zum Verschieben von Dateien/Ordnern als auch zum Umbenennen verwendet. Geben Sie den alten Pfad/Namen und den neuen Pfad/Namen an.
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
Um ein Verzeichnis und dessen Inhalt rekursiv zu löschen, verwenden Sie `rm -r`. Achten Sie darauf, diesen Befehl mit Vorsicht zu verwenden, da der Inhalt endgültig gelöscht wird.
```bash
rm -r verzeichnisname
```

Das sind die grundlegenden Befehle, um im Terminal auf macOS zu navigieren, Dateien und Ordner zu erstellen, umzubenennen und zu löschen. Bitte seien Sie vorsichtig beim Löschen von Dateien und Verzeichnissen, da dies irreversible Auswirkungen haben kann. Üben Sie diese Befehle in einem sicheren Verzeichnis, bevor Sie sie auf wichtige Dateien anwenden.
