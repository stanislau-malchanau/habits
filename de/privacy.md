---
title: Datenschutzerklärung von Habit Tracker
lang: de
---

# Datenschutzerklärung von Habit Tracker: Game & Friends

*Dies ist eine Übersetzung. Weicht sie von der [englischen Fassung](../privacy) ab, ist die englische Fassung maßgeblich.*

Gültig ab: 2026-10-24

Diese Erklärung beschreibt, wie Habit Tracker: Game & Friends (auf dem Home-Bildschirm „Habits“, die „App“), entwickelt von Stanislau Malchanau („wir“, „uns“), mit Ihren Informationen umgeht. Kurz gesagt: **Wir erheben, verkaufen oder teilen Ihre personenbezogenen Daten nicht. Ihre Gewohnheiten bleiben auf Ihrem Gerät und in Ihrem eigenen iCloud-Account.**

## 1. Von der App gespeicherte Daten

Die App speichert Folgendes auf Ihrem Gerät: Ihre Gewohnheiten (Name, Symbol, Farbe, Art, Zeitplan, Ziel und Erinnerungszeiten), Ihre Markierungen für jeden Tag, Pausen und Ruhetage, Ihr Dorf (auf welchem Grundstück das Haus jeder Gewohnheit steht und wie weit es gewachsen ist) und Ihre Einstellungen. Ihre Apple Watch speichert eine Kopie derselben Daten, um Ihre Gewohnheiten anzuzeigen und zu markieren.

Wir betreiben keine Server, die diese Daten empfangen, und haben keinen Zugriff darauf. Ausnahmen sind der Zeitplan einer laufenden Live-Aktivität (Abschnitt 5) und anonyme Nutzungssignale (Abschnitt 8).

## 2. iCloud-Synchronisierung

Wenn Sie bei iCloud angemeldet sind, synchronisiert die App Ihre Daten über CloudKit von Apple, in der privaten Datenbank Ihres eigenen iCloud-Accounts, damit Ihr iPhone, Ihr iPad und Ihre Apple Watch dieselben Gewohnheiten zeigen. Diese Daten werden von Apple gemäß der Datenschutzrichtlinie von Apple (https://www.apple.com/legal/privacy/) gespeichert und geschützt. Wir können sie weder sehen noch lesen noch exportieren. Sie können die Synchronisierung in iOS unter Einstellungen > [Ihr Name] > iCloud deaktivieren.

## 3. Mit Freunden geteilte Gewohnheiten

Sie können Freunde zu einer geteilten Gewohnheit einladen. Eine geteilte Gewohnheit wird über die CloudKit-Freigabe von Apple in einem geteilten Bereich Ihres iCloud-Accounts gespeichert. Die von Ihnen eingeladenen Personen, und nur sie, sehen den Namen, das Symbol, den Zeitplan und die Markierungen dieser Gewohnheit sowie den Namen, den jede teilnehmende Person in iCloud hat. Ihre anderen Gewohnheiten werden nie geteilt. Teilnehmende können eine geteilte Gewohnheit jederzeit verlassen, und wem sie gehört, kann Teilnehmende entfernen oder die Freigabe beenden; deren Kopien werden dann nicht mehr aktualisiert. Wir können weder geteilte Gewohnheiten sehen noch, wer daran teilnimmt.

## 4. Bewegungsdaten der Kopfhörer und räumlicher Klang

Mit AirPods oder anderen unterstützten Kopfhörern kann die App die Bewegungen Ihres Kopfes nutzen, damit die Klänge des Dorfes an ihrem Platz bleiben, wenn Sie sich drehen. Diese Bewegungsdaten werden in Echtzeit auf Ihrem Gerät verarbeitet, niemals gespeichert und verlassen Ihr Gerät nie.

## 5. Mitteilungen, Live-Aktivität und Widgets

Erinnerungen, die Morgenübersicht und die Erinnerung vor dem Ende eines kostenlosen Testzeitraums werden auf Ihrem Gerät erstellt. Widgets und Komplikationen der Apple Watch lesen Ihre Gewohnheiten auf Ihrem Gerät.

Die App kann für Ihre Morgenroutine eine Live-Aktivität auf dem Sperrbildschirm und in der Dynamic Island anzeigen. Damit sie zur Zeit der Routine starten und weiterlaufen kann, während die App im Ruhezustand ist, sendet die App unserem kleinen Weiterleitungsserver die Push-Tokens, die Apple ihr für Live-Aktivitäten ausgibt (eines, um die Live-Aktivität der Routine zu starten, eines für die laufende Live-Aktivität), und den Zeitplan: die Uhrzeiten, zufällige Kennungen der enthaltenen Gewohnheiten und ihre Zahlen (wie viele erledigt sind, ein Zählerstand und sein Ziel). Es werden weder der Name einer Gewohnheit noch von Ihnen eingegebener Text, Name, E-Mail-Adresse, Account- oder Gerätekennung gesendet. Zu jedem Zeitpunkt des Zeitplans bittet der Server den Push-Dienst von Apple, die Live-Aktivität zu starten oder zu aktualisieren, und er löscht, was er gespeichert hat, sobald der geplante Push gesendet ist oder die Live-Aktivität endet. Der Server läuft auf Cloudflare Workers; wie bei jedem Internetdienst sieht Cloudflare die IP-Adresse der Anfrage, während es sie zustellt, und wir speichern sie nicht. Wenn Sie in iOS unter Einstellungen die Live-Aktivitäten für die App deaktivieren, wird nichts gesendet.

## 6. Game Center

Wenn Sie bei Game Center angemeldet sind, werden Ihre Erfolge an Game Center von Apple übermittelt und gemäß der Datenschutzrichtlinie von Apple behandelt. Ihre Game Center-Identität erhalten wir nicht.

## 7. Käufe

Abonnements werden von Apple über den App Store verkauft und abgewickelt. Wir erhalten Ihre Zahlungsdaten nicht. Apple teilt der App mit, ob Ihr Abonnement aktiv ist und welchen Tarif Sie zu welchem Preis gewählt haben; was davon in unsere Nutzungsanalyse eingeht, steht in Abschnitt 8.

## 8. Nutzungsanalyse und Absturzberichte

Um zu erfahren, welche Funktionen helfen und wo die App im Weg steht, sendet die App anonyme Nutzungssignale an TelemetryDeck, einen Analysedienst der TelemetryDeck GmbH (Augsburg, Deutschland) mit Servern in der EU. Ein Signal benennt eine Aktion in der App: zum Beispiel, dass ein Schritt des ersten Starts abgeschlossen wurde, dass der Abonnement-Bildschirm angezeigt oder ein Abonnement abgeschlossen wurde, dass die App um eine Bewertung gebeten hat oder dass die iCloud-Synchronisierung fehlgeschlagen ist. Dazu kommen ein auf die Stunde gerundeter Zeitstempel und allgemeine technische Angaben: die Versionen der App und von iOS, das Gerätemodell, Sprache, Region und Zeitzone sowie Einstellungen für Anzeige und Bedienungshilfen wie Dunkelmodus oder Textgröße. Wenn ein Abonnement oder sein kostenloser Testzeitraum beginnt, nennt das Signal außerdem den Tarif, seinen in US-Dollar umgerechneten Preis, die Währung und das Land Ihres App Stores, damit wir sehen, welche Tarife gewählt werden.

Ein Signal enthält niemals die Namen Ihrer Gewohnheiten oder andere von Ihnen eingegebene Texte, Ihren Namen, Ihre E-Mail-Adresse, Ihren Apple Account, Ihre Freunde oder Ihren Standort. Ihre Installation wird nur durch eine zufällige Kennung identifiziert, die von der App vor dem Senden mit einem Salt versehen und gehasht wird, sodass die Signale weder auf Sie zurückgeführt noch über Apps hinweg verfolgt werden können. TelemetryDeck speichert keine IP-Adressen und verwendet keine Cookies. Wir werten diese Signale nur statistisch aus, um die App zu verbessern; wir verkaufen sie nicht, geben sie nicht an Werbetreibende weiter und nutzen sie nicht, um Sie zu verfolgen. Die App enthält keinen Werbe- oder Tracking-Code und verfolgt Sie nicht über andere Apps oder Websites hinweg.

Unabhängig davon kann Apple uns zusammengefasste, anonyme Nutzungsstatistiken und Absturzberichte zur Verfügung stellen, wenn Sie sich in iOS unter Einstellungen > Datenschutz & Sicherheit > Analyse & Verbesserungen dafür entscheiden, Analysedaten mit App-Entwicklern zu teilen. Anhand dieser Daten können Sie nicht identifiziert werden.

## 9. Was die App nicht verwendet

Die App fragt weder nach Ihrem Standort noch nach Ihren Kontakten, Fotos, Ihrer Kamera, Ihrem Mikrofon oder Ihren Gesundheitsdaten. Tag und Nacht im Dorf folgen der Uhr und der Zeitzone Ihres iPhone.

## 10. Kinder

Die App ist für alle Altersgruppen geeignet und erhebt wissentlich von niemandem personenbezogene Informationen, auch nicht von Kindern unter 13 Jahren (oder unter dem entsprechenden Alter in Ihrem Land).

## 11. Speicherdauer und Löschung

Die Daten bleiben gespeichert, solange Sie sie behalten. Sie können eine Gewohnheit und ihre Markierungen jederzeit in der App löschen, und alles, indem Sie die App löschen und – bei synchronisierten Daten – in iOS unter Einstellungen > [Ihr Name] > iCloud > Accountspeicher verwalten > Habits. Da wir keine Kopie besitzen, gibt es für uns darüber hinaus nichts zu löschen. Der Weiterleitungsserver speichert die Tokens und den Zeitplan einer Live-Aktivität nur, bis der geplante Push gesendet ist oder diese Live-Aktivität endet. Nutzungssignale sind anonym und lassen sich Ihnen nicht zuordnen; deshalb gibt es dazu keinen personenbezogenen Datensatz, den man abrufen oder löschen könnte.

## 12. Ihre Rechte

Je nachdem, wo Sie leben (zum Beispiel nach der GDPR in der EU, der UK GDPR, dem CCPA/CPRA in Kalifornien, dem APPI in Japan, dem PIPA in Korea oder der LGPD in Brasilien), haben Sie möglicherweise das Recht auf Auskunft über Ihre personenbezogenen Daten sowie auf deren Berichtigung, Löschung oder Übertragung und das Recht, der Verarbeitung zu widersprechen oder sie einschränken zu lassen. Da wir Ihre Daten nicht speichern, können Sie diese Rechte wie oben beschrieben direkt auf Ihrem Gerät und in iCloud ausüben. Sie können sich mit jedem Anliegen und jeder Frage auch an uns wenden und sich bei Ihrer örtlichen Datenschutzbehörde beschweren.

Wir verkaufen oder teilen keine personenbezogenen Informationen im Sinne des CCPA/CPRA.

## 13. Änderungen

Wenn sich diese Erklärung ändert, aktualisieren wir das oben angegebene Gültigkeitsdatum und informieren Sie bei wesentlichen Änderungen in der App.

## 14. Kontakt

Stanislau Malchanau, Belarus
E-Mail: 7tam.official@gmail.com
