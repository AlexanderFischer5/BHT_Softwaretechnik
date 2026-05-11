# Feature: Login & Registrierung

## Ziel
Das Feature ermöglicht Studierenden und Betreuenden, sich auf der Plattform ThesisMatch BHT zu registrieren und sicher anzumelden.

## Beschreibung
Nutzerinnen und Nutzer sollen ein persönliches Konto erstellen können. Bei der Registrierung wird zwischen den Rollen „Studierende“ und „Betreuende“ unterschieden. Nach erfolgreicher Anmeldung erhalten sie Zugriff auf die jeweils passenden Funktionen der Plattform.

## Funktionale Anforderungen
- Das System soll eine Registrierung mit E-Mail-Adresse und Passwort ermöglichen.
- Das System soll zwischen Studierenden und Betreuenden unterscheiden.
- Das System soll einen Login mit gültigen Zugangsdaten ermöglichen.
- Das System soll ungültige Login-Versuche mit einer Fehlermeldung ablehnen.

## Akzeptanzkriterien
- Eine Registrierung mit gültigen Daten ist erfolgreich möglich.
- Eine Anmeldung mit korrekter E-Mail-Adresse und korrektem Passwort funktioniert.
- Eine Anmeldung mit falschen Daten wird abgelehnt.
- Nach dem Login wird die passende Rolle erkannt.

## Validierung
Das Feature wird durch Funktionstests überprüft. Dabei werden erfolgreiche Registrierungen, erfolgreiche Logins sowie fehlerhafte Login-Versuche getestet.
