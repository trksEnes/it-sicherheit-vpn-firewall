# Veröffentlichungshinweise

## Grundlage und Umfang

Diese redigierte Arbeitsprobe basiert auf meiner eigenen Abgabe vom 31. August 2026. Alle Netzadressen wurden dauerhaft geschwärzt oder durch fiktive Werte ersetzt. Die ursprünglichen Abgabedateien werden nicht veröffentlicht. Die technische Dokumentation kennzeichnet die späteren redaktionellen Änderungen und behält die Quellenangaben einschließlich der KI-Unterstützung bei.

## Bereinigung

- Reale IPv4-Adressen in Text, Befehlen, Tabellen und Beispielkonfigurationen konsistent ersetzt.
- IPv4-/IPv6-Adressen einschließlich lokaler und VPN-Adressen in den Terminalbildern dauerhaft aus den Pixeln entfernt.
- Mailadresse und Nachrichteninhalt im Mailbild dauerhaft geschwärzt.
- Fremde Benutzernamen, eigene Kennungen einschließlich der Testmarker sowie Remote-Hostname in den Terminalbildern geschwärzt.
- Originaler Netzplan durch eine ausdrücklich gekennzeichnete Neuzeichnung mit Beispieladressen ersetzt.
- Reale URLs aus dem Literaturverzeichnis entfernt; Autor, Titel, Abrufdatum und Hinweis auf damalige KI-Nutzung beibehalten.
- Individuelle Passwortwerte und Domains aus dem Passwortkapitel entfernt; Vorgehen und Bewertung zusammengefasst.
- Zugangspasswort, Containerpasswort, Dateiname und Benutzerkennung entfernt beziehungsweise neutralisiert.
- Auch Chiffrat, Startblock, Schlüsselwerte, Berechnungstabellen und Quersummenrechnung der Anmeldenachricht entfernt, damit das Passwort nicht daraus zurückgewonnen werden kann.
- Matrikelnummer und unterschriebene Eigenständigkeitserklärung ausgelassen.
- Neue PDF aus der bereinigten Quelle erstellt; keine Original-PDF, Anhänge, Signaturen oder originale Metadaten übernommen.

## Nicht Bestandteil dieser Fassung

Aufgabenstellung, Originalarchiv und verschachteltes Originalarchiv, Original-Markdown, Original-PDF, Originalbilder, Mail des Professors, Eigenständigkeitserklärung, öffentliche Schlüsseldatei und digitale Signatur sind nicht enthalten. Private Schlüssel, Zertifikate und Container werden ebenfalls nicht veröffentlicht.

## Konsistente Beispielwerte

| Rolle | Beispielwert |
| --- | --- |
| VPN-Endpunkt | `198.51.100.10` |
| SSH-Ziel | `198.51.100.20` |
| Lokaler VPN-Client | `192.0.2.22` |
| Nicht freigegebenes externes Ziel | `203.0.113.200` |
| Kreativbereich | `10.10.1.0/24` |
| Servernetz / DMZ | `10.10.2.0/24` |
| Verwaltung | `10.10.3.0/24` |
| WAN-Schnittstelle der Netzplanung | `203.0.113.10` |
| Webserver / Bilddatenbank | `10.10.2.142` / `10.10.2.141` |
| Neutraler Beispiel-Mailkontakt | `uebung@example.invalid` |

VPN-Versuch und Netzplanung sind getrennte Szenarien. Die Beispieladressen sind keine aktuelle, erreichbare Infrastruktur. Geschwärzte Ergebnisbilder sind Originalbelege; die technischen Ausgaben wurden nicht nachträglich durch vermeintliche neue Messergebnisse ersetzt.

## Redaktionelle Korrekturen dieser Fassung

- Interne Beispielnetze liegen in getrennten, frei gewählten privaten Bereichen. Sie überschneiden sich weder untereinander noch mit den Beispielwerten für WAN, VPN-Endpunkt, SSH-Ziel und VPN-Client.
- Der Netzplan wurde ohne kreuzende Verbindungen neu gezeichnet. Beide Server sind am gemeinsamen DMZ-Segment angeschlossen.
- Der externe ICMP-Test verwendet ein numerisches Beispielziel. Voraussetzungen für belastbare Negativtests sind erklärt; keine neue Testausführung wird behauptet.
- Ein beobachteter Paketverlust zwischen entfernten Rechnern wird nicht mehr der lokalen Firewall zugeschrieben.
- Codeblöcke und die beiden separaten Beispieldateien stimmen überein. Die ursprünglichen aktiven Befehle bzw. Direktiven bleiben bis auf Adressen und persönliche Pfade erhalten.
- Einschränkungen des ursprünglichen Firewall-Prototyps und die begrenzte Testabdeckung werden ausdrücklich genannt.
- Öffentliche Quellen-URLs bleiben vorsorglich ebenfalls entfernt; die Mail unterscheidet nicht ausdrücklich zwischen öffentlichen Quellen und Hochschuladressen. Die Quellenbenennung einschließlich KI-Nutzung bleibt erhalten.

Diese Veröffentlichung ersetzt die ursprüngliche, signierte Prüfungsabgabe nicht. Die hinzugefügten Erläuterungen und der redigierte Testfall gehören zur späteren Portfoliofassung.

## Veröffentlichungsstand

Enes Türksever hat diese bereinigte Portfoliofassung am 12. November 2026 zur Veröffentlichung freigegeben. Das Repository wird ausschließlich mit den bereinigten Dateien neu angelegt; eine frühere Git-Historie und unbereinigte Originaldateien werden nicht übernommen.
