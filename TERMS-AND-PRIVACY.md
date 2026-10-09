# DockShelf – Nutzungsbedingungen und Datenschutzhinweise

*Stand: 9. Oktober 2026 · gilt für DockShelf ab Version 0.3.0 · English version below*

**Kurz gesagt:** DockShelf ist ein kostenloses Hobbyprojekt. Es arbeitet vollständig auf deinem Mac: kein Konto, keine Werbung, keine Analyse, keine Server des Entwicklers. Ins Internet geht DockShelf nur, um bei GitHub nach Updates zu fragen, und das kannst du abschalten. Du nutzt die App auf eigenes Risiko; bitte sichere wichtige Daten.

## 1. Anbieter und Kontakt

DockShelf wird privat und unentgeltlich entwickelt und weitergegeben von:

Maxim Ratke\
maxxerzy@gmail.com

DockShelf ist kein Produkt von Apple Inc. und steht in keiner Verbindung zu Apple oder zu den Anbietern anderer Dock- oder Shelf-Apps. macOS, AirDrop und Apple Intelligence sind Marken von Apple Inc.

## 2. Nutzungsbedingungen

**2.1 Nutzungsrecht.** Du darfst DockShelf kostenlos auf deinen eigenen Macs installieren und nutzen. Weitergeben darfst du DockShelf nur unverändert und unentgeltlich. Verkaufen, Verändern oder Weiterverbreiten in veränderter Form ist nicht erlaubt, soweit das Gesetz nichts anderes zwingend vorsieht.

**2.2 Stand der Software.** DockShelf ist ein Vorab- und Hobbyprojekt. Die App ist nicht von Apple notarisiert und nutzt zum Teil nicht öffentliche macOS-Schnittstellen. Nach macOS-Updates kann sie deshalb ganz oder teilweise nicht mehr funktionieren. Es besteht kein Anspruch auf Fehlerbehebung, Support, Updates oder dauerhafte Verfügbarkeit.

**2.3 Deine Dateien.** DockShelf kann auf deine Anweisung hin Dateien kopieren, verschieben, umbenennen, komprimieren, umwandeln, per AirDrop oder über Teilen-Dienste senden und in den Papierkorb legen. Prüfe solche Aktionen und sichere wichtige Daten regelmäßig, zum Beispiel mit Time Machine.

**2.4 Haftung.** DockShelf wird dir geschenkt. Ich hafte deshalb nur für Vorsatz und grobe Fahrlässigkeit sowie für Mängel, die ich arglistig verschwiegen habe. Unberührt bleibt die Haftung für Schäden aus der Verletzung des Lebens, des Körpers oder der Gesundheit und nach dem Produkthaftungsgesetz.

**2.5 Updates.** Updates werden nur aus der offiziellen Veröffentlichungsquelle geladen und vor der Installation anhand einer digitalen Signatur geprüft. Mit der Installation eines Updates gelten die dann beiliegenden Bedingungen.

**2.6 Open-Source-Bestandteile.** DockShelf enthält das Update-Framework Sparkle (MIT-Lizenz). Den vollständigen Lizenztext findest du in der App unter Einstellungen › Privacy & Terms.

**2.7 Schlussbestimmungen.** Es gilt deutsches Recht. Wenn du Verbraucher bist, bleibt der Schutz durch zwingende Vorschriften des Staates, in dem du deinen gewöhnlichen Aufenthalt hast, unberührt. Sollte eine Bestimmung unwirksam sein, bleiben die übrigen wirksam.

## 3. Datenschutzhinweise

**3.1 Verantwortlicher.** Verantwortlich im Sinne der Datenschutz-Grundverordnung (DSGVO) ist die in Abschnitt 1 genannte Person, soweit überhaupt Daten an sie gelangen. Das ist beim normalen Betrieb nicht der Fall.

**3.2 Grundsatz: alles bleibt auf deinem Mac.** DockShelf hat keine Benutzerkonten, keine Analyse- oder Tracking-Werkzeuge, keine Werbung, keine Absturzberichte an mich und keinen eigenen Server. Inhalte deiner Dateien, deiner Zwischenablage oder deines Bildschirms werden nie an mich oder Dritte übertragen. Die folgende Verarbeitung findet ausschließlich lokal statt:

- **Datei-Shelf.** Für abgelegte Dateien speichert DockShelf Name, Pfad, ein macOS-Lesezeichen, Datum, Farbmarkierung und die Zugehörigkeit zu einem Set unter `~/Library/Application Support/DockShelf`. Wenn du „Kopien speichern“ nutzt (oder bei Kurzbefehlen und iPhone-Importen), liegt dort auch eine Kopie der Datei. Die Einträge bleiben, bis du sie entfernst. Nicht mehr benötigte Kopien legt DockShelf beim nächsten Start in den Papierkorb.
- **Zweites Shelf (Bildschirmfotos und Downloads).** DockShelf zeigt die neuesten Dateien aus deinem Bildschirmfoto-Ordner und aus „Downloads“ oder aus einem Ordner, den du gewählt hast. Bei Bildern erkennt DockShelf den enthaltenen Text mit Apples Vision-Framework und bildet Stichwörter mit Apple Intelligence, beides direkt auf dem Gerät. Der Text von Dokumenten wie PDFs wird dabei nicht ausgelesen. Die Ergebnisse liegen nur im Arbeitsspeicher und verschwinden beim Beenden. Du kannst das unter Einstellungen › Second Shelf abschalten.
- **Zwischenablage-Verlauf (optional, standardmäßig aus).** Wenn du ihn einschaltest, merkt sich DockShelf bis zu 30 kopierte Einträge nur im Arbeitsspeicher und löscht sie beim Beenden. Inhalte, die Passwort-Manager als vertraulich oder vorübergehend kennzeichnen, und Kopien aus den Apps „Passwörter“ und „Schlüsselbundverwaltung“ werden übersprungen. Andere Apps kennzeichnen sensible Inhalte nicht immer; behalte das im Blick.
- **Bedienungshilfen (Accessibility).** Mit dieser Berechtigung liest DockShelf nur die Position und Größe des Docks sowie, ob das vorderste Fenster im Vollbildmodus ist und auf welchem Bildschirm es liegt. DockShelf liest keine anderen Fensterinhalte, gibt nichts ein, klickt nichts an und ändert keine Einstellungen.
- **Tastenkürzel.** Die ⌃⌥⌘-Kürzel sind beim System registriert. DockShelf erfährt dadurch nur von diesen Tastenkombinationen, nicht von anderen Tastenanschlägen.
- **Einstellungen.** Deine Einstellungen liegen in `~/Library/Preferences/com.maxim.DockShelf.plist`. Dazu gehören gewählte Ordnerpfade, angeheftete Dateien und die Kennungen von Apps, die du für „Privacy Pause“ oder Vollbild-Ausnahmen ausgewählt hast. Für „Privacy Pause“ prüft DockShelf, welche dieser Apps gerade laufen.

**3.3 Sichtbarkeit auf dem Bildschirm.** Die Shelves zeigen Dateinamen, Vorschaubilder, erkannten Text und gegebenenfalls kopierte Inhalte. Alles, was auf dem Bildschirm steht, kann in Bildschirmfotos, Aufnahmen und Bildschirmfreigaben landen. „Privacy Pause“ blendet die Shelves aus, solange ausgewählte Konferenz-Apps laufen. Eine Bildschirmfreigabe im Webbrowser erkennt sie nicht; blende die Shelves dann mit ⌃⌥⌘X aus.

**3.4 Weitergabe nur durch dich.** Daten verlassen deinen Mac nur durch Aktionen, die du selbst auslöst: AirDrop, Teilen-Dienste (z. B. Mail oder Nachrichten), Ziehen in andere Apps und Kopieren in die Zwischenablage. Die Zwischenablage kann von macOS per „Universelle Zwischenablage“ mit deinen anderen Apple-Geräten geteilt werden. Für diese Dienste gelten die Bedingungen ihrer Anbieter.

**3.5 Update-Prüfung über GitHub.** DockShelf nutzt das Open-Source-Framework Sparkle. Einmal täglich und wenn du „Check for Updates…“ wählst, ruft DockShelf eine Update-Liste von `raw.githubusercontent.com` ab. Gibt es eine neue Version, lädt DockShelf sie von `github.com` herunter, prüft ihre Signatur und installiert sie. Anbieter dieser Dienste ist GitHub, Inc., 88 Colin P. Kelly Jr. St., San Francisco, CA 94107, USA, ein Unternehmen von Microsoft.

- Dabei übermittelt dein Mac technisch notwendige Daten an GitHub: deine IP-Adresse, den Zeitpunkt, übliche Verbindungsdaten und die Kennung `DockShelf/<Version> Sparkle/<Version>`.
- Ein Systemprofil, Geräte- oder Nutzerkennungen werden nicht gesendet.
- Ich selbst erhalte keine dieser Daten; GitHub zeigt mir nur die Gesamtzahl der Downloads je Datei.
- Rechtsgrundlage ist Art. 6 Abs. 1 lit. f DSGVO. Das berechtigte Interesse liegt darin, dir Fehlerbehebungen und Sicherheitsupdates bereitzustellen.
- Die Daten werden in die USA übermittelt. GitHub verarbeitet sie in eigener Verantwortung und stützt die Übermittlung auf die in seiner Datenschutzerklärung genannten Garantien: <https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>.
- Du kannst die automatische Prüfung und die automatische Installation jederzeit unter Einstellungen › Updates abschalten. Dann verbindet sich DockShelf nur noch, wenn du selbst nach Updates suchst.
- Wenn du DockShelf von GitHub herunterlädst, gilt dafür ebenfalls die Datenschutzerklärung von GitHub.

**3.6 Dienste von macOS.** Unabhängig von DockShelf führt macOS eigene Prüfungen und Downloads durch, zum Beispiel Gatekeeper-Prüfungen beim ersten Öffnen oder das Laden der Apple-Intelligence-Modelle. Dafür gelten die Bedingungen von Apple.

**3.7 Speicherdauer und Löschen.** Daten im Arbeitsspeicher (Zwischenablage-Verlauf, erkannte Texte, Stichwörter) verschwinden beim Beenden. Shelf-Einträge und Einstellungen bleiben, bis du sie entfernst. Beim Löschen der App bleiben diese Dateien zunächst erhalten. Für eine vollständige Entfernung beende DockShelf und lösche:

- `~/Library/Application Support/DockShelf`
- `~/Library/Preferences/com.maxim.DockShelf.plist`
- `~/Library/Caches/com.maxim.DockShelf`
- `~/Library/HTTPStorages/com.maxim.DockShelf`

Entferne DockShelf danach in den Systemeinstellungen unter „Bedienungshilfen“ und „Anmeldeobjekte“.

**3.8 Deine Rechte.** Nach der DSGVO hast du das Recht auf:

- Auskunft
- Berichtigung
- Löschung
- Einschränkung der Verarbeitung
- Datenübertragbarkeit
- Widerspruch gegen eine Verarbeitung auf Grundlage berechtigter Interessen

Da bei mir keine Daten über dich gespeichert sind, betreffen solche Anfragen in der Regel nur GitHub. Du kannst dich außerdem bei einer Datenschutz-Aufsichtsbehörde beschweren, insbesondere in dem Land, in dem du lebst.

**3.9 Änderungen.** Wenn sich DockShelf ändert, passe ich diese Hinweise an. Die jeweils aktuelle Fassung liegt jeder Version bei und ist in der App unter Einstellungen › Privacy & Terms abrufbar.

---

# DockShelf – Terms of Use and Privacy Notice

*Last updated: 9 October 2026 · applies to DockShelf 0.3.0 and later · This is a translation; if the two versions differ, the German version prevails.*

**In short:** DockShelf is a free hobby project. It runs entirely on your Mac: no account, no ads, no analytics, no developer servers. The only time DockShelf goes online is to ask GitHub for updates, and you can turn that off. You use the app at your own risk; please back up important data.

## 1. Provider and contact

DockShelf is developed and shared privately and free of charge by:

Maxim Ratke\
maxxerzy@gmail.com

DockShelf is not a product of Apple Inc. and is not affiliated with Apple or with the makers of any other Dock or shelf app. macOS, AirDrop and Apple Intelligence are trademarks of Apple Inc.

## 2. Terms of use

**2.1 License.** You may install and use DockShelf free of charge on your own Macs. You may pass it on only unmodified and free of charge. Selling, modifying, or redistributing modified versions is not permitted, except where mandatory law allows it.

**2.2 State of the software.** DockShelf is a pre-release hobby project. It is not notarized by Apple and partly uses non-public macOS interfaces, so it may stop working, fully or partly, after macOS updates. There is no entitlement to fixes, support, updates or continued availability.

**2.3 Your files.** When you tell it to, DockShelf can copy, move, rename, compress or convert files, send them via AirDrop or share services, and move them to the Trash. Check these actions, and back up important data regularly, for example with Time Machine.

**2.4 Liability.** DockShelf is a gift. I am therefore liable only for intent and gross negligence, and for defects I fraudulently concealed. This does not limit liability for injury to life, body or health, or under the German Product Liability Act.

**2.5 Updates.** Updates are loaded only from the official release source and are checked against a digital signature before they are installed. The terms included with an update apply once you install it.

**2.6 Open-source components.** DockShelf includes the Sparkle update framework (MIT license). The full license text is in the app under Settings › Privacy & Terms.

**2.7 Final provisions.** German law applies. If you are a consumer, you keep the protection of the mandatory laws of the country where you habitually live. If any provision is invalid, the rest remain valid.

## 3. Privacy notice

**3.1 Controller.** The controller under the GDPR is the person named in section 1, to the extent any data reaches them at all. In normal use, none does.

**3.2 The principle: everything stays on your Mac.** DockShelf has no accounts, no analytics or tracking tools, no ads, no crash reports sent to me, and no server of its own. The contents of your files, clipboard or screen are never sent to me or anyone else. The following processing happens only on your Mac:

- **File shelf.** For files you put on the shelf, DockShelf stores the name, path, a macOS bookmark, date, color tag and set membership in `~/Library/Application Support/DockShelf`. With "Store copies" on (and always for Shortcuts input and iPhone imports), a copy of the file is kept there too. Entries stay until you remove them. Copies that are no longer needed are moved to the Trash at the next launch.
- **Second shelf (screenshots and downloads).** DockShelf shows the newest files in your screenshot folder and in Downloads, or in a folder you chose. For images, it recognizes the text they contain with Apple's Vision framework and derives keywords with Apple Intelligence, both on the device. The text of documents such as PDFs is not read. The results are kept in memory only and are gone when you quit. You can turn this off under Settings › Second Shelf.
- **Clipboard history (optional, off by default).** If you turn it on, DockShelf keeps up to 30 copied items in memory only and clears them when you quit. It skips content that password managers mark as concealed or transient, and copies from the Passwords and Keychain Access apps. Other apps don't always mark sensitive content, so keep that in mind.
- **Accessibility.** With this permission, DockShelf reads only the Dock's position and size, and whether the frontmost window is in full screen and on which display. It does not read other window content, type, click, or change any setting.
- **Keyboard shortcuts.** The ⌃⌥⌘ shortcuts are registered with the system, so DockShelf learns only about those key combinations, never about other keystrokes.
- **Settings.** Your settings are stored in `~/Library/Preferences/com.maxim.DockShelf.plist`. They include folder paths you chose, pinned files, and the identifiers of apps you picked for Privacy Pause or full-screen exceptions. For Privacy Pause, DockShelf checks which of those apps are running.

**3.3 Visibility on screen.** The shelves show file names, thumbnails, recognized text and, if enabled, copied content. Anything on screen can end up in screenshots, recordings and screen shares. Privacy Pause hides the shelves while selected conferencing apps are running. It cannot detect screen sharing in a web browser; hide the shelves with ⌃⌥⌘X in that case.

**3.4 Sharing happens only when you do it.** Data leaves your Mac only through actions you start yourself: AirDrop, share services (e.g. Mail or Messages), dragging into other apps, and copying to the clipboard. macOS may sync the clipboard to your other Apple devices via Universal Clipboard. Those services are governed by their providers' terms.

**3.5 Update checks via GitHub.** DockShelf uses the open-source framework Sparkle. Once a day, and whenever you choose "Check for Updates…", DockShelf fetches an update list from `raw.githubusercontent.com`. If there is a new version, it downloads it from `github.com`, verifies its signature and installs it. These services are provided by GitHub, Inc., 88 Colin P. Kelly Jr. St., San Francisco, CA 94107, USA, a Microsoft company.

- Your Mac sends GitHub the technically necessary data: your IP address, the time, standard connection data, and the identifier `DockShelf/<version> Sparkle/<version>`.
- No system profile and no device or user identifiers are sent.
- I receive none of this data; GitHub only shows me total download counts per file.
- The legal basis is Art. 6(1)(f) GDPR. The legitimate interest is providing you with bug fixes and security updates.
- The data is transferred to the USA. GitHub processes it as its own controller and relies on the safeguards described in its privacy statement: <https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>.
- You can turn off automatic checks and automatic installation at any time under Settings › Updates. DockShelf then connects only when you check for updates yourself.
- When you download DockShelf from GitHub, GitHub's privacy statement applies as well.

**3.6 macOS services.** Independently of DockShelf, macOS runs its own checks and downloads, for example Gatekeeper checks on first launch or downloading Apple Intelligence models. Apple's terms apply to those.

**3.7 Retention and deletion.** In-memory data (clipboard history, recognized text, keywords) is gone when you quit. Shelf entries and settings remain until you remove them, and deleting the app leaves these files in place at first. For a complete removal, quit DockShelf and delete:

- `~/Library/Application Support/DockShelf`
- `~/Library/Preferences/com.maxim.DockShelf.plist`
- `~/Library/Caches/com.maxim.DockShelf`
- `~/Library/HTTPStorages/com.maxim.DockShelf`

Then remove DockShelf under Accessibility and Login Items in System Settings.

**3.8 Your rights.** Under the GDPR you have the right to:

- access
- rectification
- erasure
- restriction of processing
- data portability
- object to processing based on legitimate interests

Since I hold no data about you, such requests will usually concern GitHub. You may also lodge a complaint with a data protection supervisory authority, in particular in the country where you live.

**3.9 Changes.** When DockShelf changes, I will update this notice. The current version ships with every release and is available in the app under Settings › Privacy & Terms.
