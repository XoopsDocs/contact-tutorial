# 3.0 Moduleinstellungen

### Optionen für Captcha
#### Google reCaptcha verwenden?
Wähle Ja, um Google reCaptcha im Eingabeformular zu verwenden.

#### Ihr reCaptcha-Sicherheitsschlüssel
Bitte hier ihren reCaptcha-Sicherheitsschlüssel angeben

Wenn Sie reCaptcha verwenden möchten, müssen Sie Ihre Webseite zuvor bei Google reCaptcha registrieren. Um den erforderlichen Webseitenschlüssel zu erhalten, gehen Sie dazu wie folgt vor:

- Wenn Sie nicht bei Google registriert sind, müssen Sie sich zuerst bei registrieren
- Aufruf der Webseite https://www.google.com/recaptcha/admin
- Einfach die gewünschte Webseite (Bezeichnung und Url) angeben:
![3_recaptcha_01_de.jpg](../assets/3_recaptcha_01_de.jpg)

- Nach dem Klick auf "Registrieren" erscheint eine neue Seite mit dem erforderlichen Webseitenschlüssel:
![3_recaptcha_02_de.jpg](../assets/3_recaptcha_02_de.jpg)

- Den Webseitenschlüssel kopieren und in der Moduleinstellung eintragen
- fertig

Mehr über Google reCaptcha unter https://www.google.com/recaptcha


### Formularoptionen
Hier können sie festlegen, welche Felder im Kontaktformular angezeigt werden sollen.


### Optionen für die Verwendung von Abteilungen
#### Auswahl für Abteilungen anzeigen
Hier können sie festlegen, ob sie diese Option grundsätzlich verwenden wollen. Die nachfolgenden Optionen müssen dann befüllt werden.

#### Abteilungen/Empfänger
Diese Option erlaubt die Angabe/Kombination von verschiedenen Abteilungen/Empfängern.
Je nach Benutzerauswahl erhält die entsprechende Abteilung die jeweilige Kontaktinformation an die dafür definierte E-Mail-Adresse.

Definiere jede Abteilung/E-Mail wie folgt:

abteilung1,email1|abteilung2,email2|abteilung3,email3 etc. - jede Abteilung muss von der E-Mail mit einem Beistrich ',' getrennt sein,
und jede Kombination Abteilung/E-Mail muss durch einen Strich '|' getrennt sein.

Wenn eine Nachricht an 2 EMails weitergeleitet werden soll, dann wiederholen sie die Abteilung, z.B. abteilung1,email1|abteilung1,email2

Wenn keine Abteilung/kein Empfänger angegeben wird, wird die Mailnachricht an die Standard-E-Mail-Adresse versendet.

#### Abteilung als Präfix verwenden?
Wenn ja, dann wird der Name der Abteilung als Präfix im E-Mail-Betreff verwendet.


#### Zusatz Präfix Email-Betreff
Definieren sie den Text, der als Präfix Abteilung im E-Mail-Betreff verwendet wird.


### Information
#### Überschrift des Kontaktformulars
Hier können sie festlegen, welcher Text im Kopfbereich des Kontaktformulars angezeigt werden soll. Dabei ist auch HTML-Code zulässig.


#### Standard-Kontaktdaten
Hier können die Kontaktdaten angegeben werden, die zusätzlich zum Formular angezeigt werden sollen (z.B. Name, Adresse , Telefonnummer,...


#### Google Maps einbetten
Hier können sie Google Maps als iframe einbetten

Gehen Sie dazu wie folgt vor:
- Den entsprechenden Ort in Google Maps suchen
- Auf "Einstellungen" oder "Teilen" klicken:
![3_maps_01_de.jpg](../assets/3_maps_01_de.jpg)

- Nach dem Klick auf "Karte teilen oder einbetten" den Tab "Karte einbetten" wählen:
![3_maps_02_de.jpg](../assets/3_maps_02_de.jpg)

- Den iframe-Code kopieren und in der Moduleinstellung eintragen
- Falls erforderlich, die Einstellung der Weite des iframes auf 100 % ändern.
- fertig


### Sonstige Optionen
#### Standardempfänger
Definieren sie, an welche E-Mail-Adresse jede Kontaktanfrage per Mail gesendet wird.


#### Bestätigungsmail senden?
Wenn sie ja wählen, wird an die im Kontaktformular angegebene E-Mail-Adresse eine kurze Bestätigungsmail mit den wichtigsten Informationen gesendet#


### Administration
#### Anfragen pro Seite
Definieren sie die Anzahl der Einträge für die Liste der Anfragen (Administrationsbereich)