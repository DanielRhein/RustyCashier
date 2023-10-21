# RustyCashier
Handle your Cashflow with this Service

## Features
- I'd like to deposit money into an account.
- I'd like to save money in an account.
- I'd like to restrict access to account for a certain time-period.
- I'd like to determine my accounts.
- I'd like to spend money from an account for an activity.
- I'd like to spend money regulary from an account for a repetitive event.
- I'd like to change repetitive events.
- I'd like to delete repetitive events.
- I'd like to save money in an repetitive event.
- I'd like to earn interest for my money.
- Resticted access needs to give interests over time.
- I'd like to set an password
- I'd like to setup an account
- I'd like to add mandants to my account.
- I'd like to archive some data at a certain time.
- I'd like to archive some data regularly.


## What is an account
- An account is a place where money is save or remove from.
- An account accumulate money.
- An account could give interest over time.
- An account can be resticted for access. But just in case it will give interests over time.

## What is a prognosis
- It will allow to give insides what is available on your account at a certain time. 
- It will give you an information, what you can spend until a certain amount of days.

## What are repetitive events
- Standing orders will start and end at a ceartain date, but will occur on a certain date in time.

# User Stories

| Nr | Description|
|:----|:-----------|
|1|Als Anwender will ich meine Daten geschuetzt ablegen,|
| |so dass sie von keinem anderen eingesehen werden können|
| |Dennoch will ich sie als CSV bei bedarf extrahieren können |

| Nr | Description|
|:----|:-----------|
|2|Als Anwender will mein Geld auf ein Konto einzahlen|
| |und abbuchen können.|

| Nr | Description|
|:----|:-----------|
|4|Als Anwender will mein Geld regelmäßig sparen|
| |oder regelmäßige Zahlungen ausetzen können|

| Nr | Description|
|:----|:-----------|
|5|Ich will als Anwender jederzeit wissen, wieviel Geld ich|
| |im aktuellen Monat zur Verfügung habe|

| Nr | Description|
|:----|:-----------|
|6|Ich will als Anwender jederzeit wissen, wieviel Geld ich|
| |im zu einem bestimmen Zeitpunkt besitze|

| Nr | Description|
|:----|:-----------|
|6|Ich will als Anwender eine Warnung erhalten wenn ich mein Limit|
| |überschreite oder ggf. überziehe.|

| Nr | Description|
|:----|:-----------|
|7|Ich will meine Geldwünsche damit koppeln können|
| |und wissen wann ich mir einen Wunsch erfüllen kann.|

| Nr | Description|
|:----|:-----------|
|8|Ich will die Konten bestimmen können|
| |die bei der Prognose genutzt werden können, und welche nicht.|

| Nr | Description|
|:----|:-----------|
|9|Ich will einen Account anlegen können|
| |und meherere Benutzer darin verwalten können|

| Nr | Description|
|:----|:-----------|
|10|Ich will einen Account loeschen können|
| |die nicht mehr verwendet werden|

| Nr | Description|
|:----|:-----------|
|11|Ich will meine Daten verschluesseln können|
| |damit niemand anderes ohne Password diese auslesen kann.|


# Domain Storytelling

# Kontoflüsse
Ein Konto kann Geld empfangen oder übermittelt Geld auf ein anderes Konto.
Ein Konto kann eine ID, oder eindeutige Bezeichnung besitzen.  Ein Zeitpunkt zu dem Geld von einem Konto zum anderen übergeganen ist, nennt man Kontofluss.

# Regeltermine
Zu einem Zeitpunkt wird Geld von einem Konto auf ein anderes transferiert.
Der Zeitpunkt bestimmt wann und wieviel Geld auf einem Konto ist.

# Prognose
Eine prognose gibt zu einem bestimmen Zeitpunt oder Zeitraum an. Wiviel Geld zur verfügüng stehen. Sie simuliert regelmäßige Kontotransaktionen.

# Kontostand
Ist der Zustand in dem Geldwertemittel auf einem Konto zu einem Zeitpunkt sind.

1. Konto --> Konto (Geldtransfer, Kontofluss)
2. Wunsch --> Zahlungsziel
3. Kontostand ist das Ergebnis von Geldtransfers zu einem Zeitpunkt.

# MVP
## 1 Geld auf ein Konto einzahlen
- U 1 Anwender ohne Passwort anlegen.
- U 2 Konto anlegen.
- U 3 Geld ueberweisen.
- U 4 Prognose wieviel Geld kann ich im Monat ausgeben.
- E 5 Keine Verschluesselung.
- E 6 Keine weiteren Mandanten anlegen.

# MVP
## 2 Mehrere Anwender anlegen.
- U 1 Mehrere Anwender zu einem Gruppenkonto anlegen
- U 2 Anwender von Gruppenkonto loesen.
- U 3 Limit festlegen.
- E 5 Keine Verschluesselung.
- E 6 Keine weiteren Mandanten anlegen.

# MVP
## 3 Wuensche festlegen
- U 1 Wuensche koennen pro Konto bestimmt werden.
- U 2 Accounts können geloescht werden.
- U 3 Kontos können geloescht werden.

# MVP
## 4 Regeltermine festlegen
- U 1 Regeltermine fuer wiederkehrende Zahlnugen koennen festgelegt werden.
- U 2 Regeltermine fuer sicherungen koennen festgelegt werden.
- U 3 Sicherungen koennen festgelegt werden.

# MVP 
## 5 Prognosen
- U 1 Prognosen Monatlich Jaehrlich können bestimmt werden.
- U 2 Konten koennen fuer die monatliche uebersicht eingebunwerden.
- U 3 Prognosen und Wuensche koennen kombiniert werden.

# MVP 
## 6 Kontofluesse
- U 1 Eine Uebersicht zeigt wohin das Geld und wieviel Geld fließt

# MVP 
## 8 Kontofluesse
- U 1 Sicherungen speichern als CSV Datei



