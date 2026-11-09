# AutoFOH

**KI-Tontechniker für das Yamaha DM3.** Ein Klick richtet alles ein: Die KI erkennt jeden Kanal,
pegelt ein, mischt, beseitigt Rückkopplungen in einer halben Sekunde, mischt Redner automatisch
und hält die Saal-Lautstärke. Kostenlos, läuft lokal auf dem Mac, ohne Cloud.

Erstellt von Norbert Bungalski. Aktuelle Version: **0.5.3**

## Herunterladen

Auf der Seite **[Releases](../../releases/latest)** das passende Paket laden:

| Dein Gerät | Datei |
|---|---|
| Mac mit M1, M2, M3 oder M4 | `AutoFOH-Mac-AppleSilicon-M1-M2-M3-M4.zip` |
| Älterer Mac (Intel) | `AutoFOH-Mac-Intel.zip` |
| Handy, Tablet, Windows-PC | **Keine Installation nötig:** AutoFOH läuft auf dem Mac, alle anderen Geräte steuern über den Browser mit (Dashboard und Musiker-Monitor, siehe unten). |

Welcher Mac? Apfel-Menü → „Über diesen Mac“: steht dort *Apple M…*, nimm die Apple-Silicon-Datei, bei *Intel* die Intel-Datei.
Voraussetzung: macOS 14 (Sonoma) oder neuer. Den KI-Chat mit Apple Intelligence gibt es ab macOS 26 auf Macs mit Apple-Chip.
Alles andere läuft auch ohne.

## Installieren (Mac)

Am einfachsten über die [Veranstaltungs-Toolbox](https://bungalskin-ui.github.io/veranstaltungs-toolbox-releases/): ein Klick auf **Installieren**.

Oder von Hand: Zip öffnen, `AutoFOH` starten. Die App ist von Apple geprüft (signiert und notarisiert) und zieht
beim ersten Start selbst in den Ordner **Programme**. Dann **„Alles automatisch einrichten“** klicken.
Ohne Pult läuft eine Simulation mit Demo-Band.

## Andere Geräte (Handy, Tablet, Windows)

Mac und Gerät ins selbe WLAN. In AutoFOH unter *Experte → Einrichtung → Dashboard* stehen Adresse und PIN.
- **Techniker:** `http://<Mac-Adresse>:8080` – NOT-AUS, Modus, Pegel, KI-Chat
- **Musiker:** `http://<Mac-Adresse>:8080/monitor` – eigener Monitor-Mix mit Musiker-PIN

## Updates

AutoFOH prüft beim Start selbst, ob es eine neue Version gibt. Dann erscheint oben der Knopf **⬆ Update**:
ein Klick lädt die neue Version, prüft sie, AutoFOH startet neu. Einstellungen, Szenen und Protokolle bleiben erhalten.
Manuell: Menü **AutoFOH → Nach Updates suchen …**

## Hilfe

Fragen oder Fehler? Schreib mir mit einer kurzen Beschreibung, was passiert ist.
