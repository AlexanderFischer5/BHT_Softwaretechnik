# Feature: Matching zwischen Studierenden und Betreuenden

## Ziel
Das Feature unterstützt Studierende dabei, passende Betreuende für ihre Abschlussarbeit zu finden.

## Beschreibung
Studierende geben ihre Themengebiete, fachlichen Interessen und ihren Studiengang an. Betreuende hinterlegen ihre Fachgebiete und bevorzugte Arbeitsweise. Das System vergleicht diese Angaben und schlägt passende Kontakte vor.

Betreuungskapazitäten können zusätzlich angezeigt werden, fließen jedoch nicht stark in die automatische Bewertung ein, da sich diese Informationen kurzfristig ändern können und regelmäßig gepflegt werden müssten.

## Funktionale Anforderungen
- Das System soll Themengebiete und fachliche Interessen erfassen.
- Das System soll den Studiengang der Studierenden berücksichtigen.
- Das System soll Fachgebiete der Betreuenden speichern.
- Das System soll bevorzugte Arbeitsweisen vergleichen.
- Das System soll passende Betreuende für Studierende vorschlagen.
- Das System soll vorhandene Informationen zu Betreuungskapazitäten als Hinweis anzeigen können.

## Akzeptanzkriterien
- Studierende können ihre Interessen und Themengebiete eintragen.
- Betreuende können ihre Fachgebiete und bevorzugte Arbeitsweise hinterlegen.
- Das System zeigt passende Vorschläge auf Basis fachlicher Übereinstimmungen an.
- Betreuungskapazitäten werden sichtbar dargestellt, aber nicht als alleiniger Ausschlussgrund verwendet.
- Die Matching-Ergebnisse sind für Studierende nachvollziehbar dargestellt.

## Validierung
Das Feature wird durch Tests mit Beispielprofilen validiert. Dabei wird geprüft, ob passende Betreuende bei gleichen oder ähnlichen Themengebieten korrekt vorgeschlagen werden. Zusätzlich wird geprüft, ob Kapazitätsinformationen korrekt als Hinweis angezeigt werden, ohne das fachliche Matching zu stark zu beeinflussen.
