# Datenschutzerklärung – Bot Detector

**Stand:** 2. November 2026

## 1. Verantwortlicher

Verantwortlich für die Datenverarbeitung durch den Discord-Bot **„Bot Detector“** ist:

**[Ozzna]**  
**[ossna]**

## 2. Welche Daten werden verarbeitet?

Der Bot verarbeitet in Discord-Servern, in denen er aktiv ist, folgende Daten:

- Discord-Benutzer-ID
- Server-ID und Kanal-ID
- Zeitpunkt einer Nachricht
- Nachrichtentext, jedoch nur normalisiert und auf maximal 1.000 Zeichen gekürzt
- Ergebnisse der automatisierten Heuristik-Analyse, etwa Risikowert und erkannte Muster
- Bei Alarmen: Nutzer-Erwähnung, Kanal, Risikowert, erkannte Hinweise und ein Link zur Nachricht

Es werden keine Passwörter, Tokens, private Direktnachrichten oder vollständige dauerhafte Chatverläufe gespeichert.

## 3. Zweck der Verarbeitung

Die Daten werden ausschließlich verarbeitet, um mögliche Spam-, Scam- oder Bot-ähnliche Verhaltensmuster in konfigurierten Serverkanälen zu erkennen.

Dazu zählen:

- Wiederholte oder stark ähnliche Nachrichten
- Auffällig schnelle Nachrichtenfolgen
- Vorhandensein von Links und bestimmten Begriffen
- Erzeugung von Warnungen in einem konfigurierten Log-Kanal

Die Analyse ist heuristisch. Ein hoher Risikowert ist kein Beweis dafür, dass ein Nutzer ein Bot ist oder gegen Regeln verstößt.

## 4. Rechtsgrundlage

Die Verarbeitung erfolgt auf Grundlage von Art. 6 Abs. 1 lit. f DSGVO, dem berechtigten Interesse am Schutz von Discord-Servern vor Spam, Scam-Versuchen und automatisiertem Missbrauch.

Serveradministratoren können die Überwachung auf bestimmte Kanäle beschränken, Nutzer oder Rollen ausnehmen und den Verlauf einzelner Nutzer löschen.

## 5. Speicherdauer

Der Bot speichert Daten nur temporär im Arbeitsspeicher. Es erfolgt keine Speicherung auf einer Festplatte, in einer Datenbank oder bei einem externen Anbieter.

- Der Nachrichtenverlauf ist auf die zuletzt erfassten Nachrichten pro Nutzer begrenzt.
- Beim Neustart des Bots werden Analyseverläufe und temporäre Einstellungen gelöscht.
- Administratoren können den Verlauf eines Nutzers mit `/detector_reset` löschen.

## 6. Weitergabe von Daten

Es erfolgt keine Weitergabe personenbezogener Daten an Dritte, insbesondere nicht zu Werbe- oder Tracking-Zwecken.

Alarmmeldungen werden ausschließlich im jeweils konfigurierten Log-Kanal des Discord-Servers veröffentlicht. Discord erhält Daten im Rahmen der technischen Nutzung seiner Plattform gemäß der Datenschutzerklärung von Discord.

## 7. Deine Rechte

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit und Widerspruch.

Da der Bot keine dauerhaften Daten speichert, kann eine Löschung in der Regel durch einen Neustart des Bots oder durch `/detector_reset` durch die Serververwaltung erfolgen.

Für Anfragen wende dich an die im Abschnitt „Verantwortlicher“ genannte Kontaktadresse.

## 8. Änderungen

Diese Datenschutzerklärung kann bei Änderungen der Bot-Funktionen angepasst werden.
