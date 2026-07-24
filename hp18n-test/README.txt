HP-18-N GLB-Testviewer
======================

Enthalten:
- index.html
- models/hp18n_betonschale.glb
- models/hp18n_bewehrung_druckgurt_randleiter_3stk_d8_sta3.glb

Wichtig:
Die Seite sollte nicht per Doppelklick als file:// geöffnet werden, weil Browser lokale GLB-Dateien häufig blockieren.

Einfachster Test über GitHub Pages:
1. Den kompletten Inhalt dieses Ordners in einen Unterordner des GitHub-Repositories kopieren, z. B. hp18n-test/.
2. Änderungen committen und pushen.
3. Danach öffnen:
   https://mariathal.github.io/hp-schalen-katalog/hp18n-test/

Lokaler Test mit Python:
1. Terminal/Eingabeaufforderung in diesem Ordner öffnen.
2. Befehl ausführen: python -m http.server 8000
3. Im Browser öffnen: http://localhost:8000

Bedienung:
- Linke Maustaste: drehen
- Mausrad: zoomen
- Rechte Maustaste: verschieben
- Bewehrung anklicken: ganze Testgruppe orange hervorheben
- Beton-Deckkraft über den Regler verändern
