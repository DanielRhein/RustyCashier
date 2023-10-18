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
2. Wunsch -->
