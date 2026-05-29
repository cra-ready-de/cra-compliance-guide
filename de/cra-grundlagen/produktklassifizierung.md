---
title: "CRA Produktklassifizierung: Default, Klasse I, Klasse II und Kritisch"
description: "Produktklassifizierung nach EU 2024/2847: Default, Wichtig Klasse I/II oder Kritisch – basierend auf Durchführungsverordnung (EU) 2025/2392."
lastUpdated: "2026-05-02"
lang: de
source: cra-ready.de
---

# CRA Produktklassifizierung: Default, Klasse I, Klasse II und Kritisch

## Einleitung: Warum ist die Klassifizierung entscheidend?
    
        Die Produktklasse bestimmt das Konformitätsbewertungsverfahren und damit den Aufwand und die Kosten der
        CRA-Konformität.
    

    
        Rechtsgrundlage sind **CRA Anhang III** (wichtige Produkte) und **CRA Anhang IV**
        (kritische Produkte).
    

    
        Die Konkretisierung erfolgt durch die **Durchführungsverordnung (EU) 2025/2392** vom
        **28. November 2025** (veröffentlicht im Amtsblatt der EU am **1. Dezember 2025**).
        Diese Verordnung liefert offizielle technische Beschreibungen für alle 28 Produktkategorien in Anhang III und IV
        und beseitigt damit die bis dahin bestehende Auslegungsunsicherheit.
    

    
        **WICHTIG:** Maßgeblich ist die **KERNFUNKTION** des Produkts, nicht sein Name,
        seine Marketingbezeichnung oder Nebenfunktionen
        (EC FAQ Dez. 2025, Abschnitt 3.2 und 3.4; Durchführungsverordnung 2025/2392, Erwägungsgründe 3-5).
    

    ## Das Vier-Stufen-Modell
    
        
            
                
                    Stufe
                    Rechtsgrundlage
                    Beispiele (industrierelevant)
                    Konformitätsbewertung
                
            
            
                
                    **Standard (Default)**
                    Alle Produkte, die NICHT in Anhang III oder IV gelistet sind (~90% aller Produkte)
                    Einfache embedded Systeme ohne Netzwerkfunktion, offline Industrie-HMI, nicht-vernetzte Steuergeräte
                    Selbstbewertung (Modul A, Art.32 Abs.1 CRA)
                
                
                    **Wichtig Klasse I**
                    CRA Anhang III Klasse I + Durchführungsverordnung 2025/2392 Anhang I Teil 1
                    Passwortmanager, Netzwerkmanagementsysteme, Netzwerk-Monitoring-Software, Betriebssysteme für allgemeine Zwecke, Router und Modems für den Heimbereich, Switches
                    Selbstbewertung NUR bei Anwendung harmonisierter Normen (Art.32 Abs.2 CRA); sonst Notified Body erforderlich
                
                
                    **Wichtig Klasse II**
                    CRA Anhang III Klasse II + Durchführungsverordnung 2025/2392 Anhang I Teil 2
                    Hypervisoren, Firewalls, Intrusion Detection/Prevention Systeme, Industrielle Automatisierungs- und Steuerungssysteme (IACS) nur bei Einsatz durch Einrichtungen unter NIS-2, manipulationssichere Mikroprozessoren
                    Notified Body PFLICHT (Art.32 Abs.3 CRA) ODER EU-Cybersicherheitszertifizierung (Art.32 Abs.4)
                
                
                    **Kritisch**
                    CRA Anhang IV + Durchführungsverordnung 2025/2392 Anhang II
                    Hardware-Sicherheitsmodule (HSM), Smart-Card-ICs, Smartcards und ähnliche Geräte, Geräte für erweiterte Sicherheitszwecke (z.B. zertifizierte Hardware-Token)
                    Notified Body PFLICHT oder EU-Cybersicherheitszertifizierung (Art.33 und 34 CRA)
                
            
        
    

    ## Der Kernfunktions-Test
    
        **WICHTIGER HINWEIS zur Auslegung:** Ein Produkt wird nach seiner KERNFUNKTION klassifiziert,
        nicht nach integrierten Komponenten.
    

    Beispiele aus EC FAQ (Dez. 2025):

    
        - Ein Smartphone mit integriertem Passwortmanager bleibt Standard-Kategorie, da die Kernfunktion nicht Passwortverwaltung ist.
        - Eine App mit eingebettetem Browser ist kein "Browser"-Produkt, da die Kernfunktion nicht Browsing ist.
        - Ein industrielles Automatisierungssystem ist Klasse II NUR, wenn der Betreiber unter NIS-2 fällt (Durchführungsverordnung 2025/2392).
    
    
        Hinweis: Die genaue Abgrenzung bei Produkten mit mehreren Funktionen kann im Einzelfall komplex sein.
        Die Kommission hat angekündigt, weitere Leitlinien zu veröffentlichen.
    

    ## Konformitätsbewertungsverfahren im Überblick
    
        - 
            **Modul A (Selbstbewertung):** Hersteller erstellt die technische Dokumentation und stellt die
            EU-Konformitätserklärung aus. Ausreichend für Default und Klasse I bei Anwendung harmonisierter Normen.
        
        - 
            **Notified Body:** Unabhängige dritte Stelle bewertet die Konformität.
            Erforderlich für Klasse I ohne harmonisierte Normen, Klasse II und Kritisch.
        
        - 
            **Stand Notified Bodies (Mai 2026):** Mitgliedstaaten mussten bis 11. Juni 2026 Verfahren zur
            Bewertung und Benennung von Konformitätsbewertungsstellen veröffentlichen (Art.35 CRA).
            Mitgliedstaaten sollen bis 11. Dezember 2026 ausreichend Notified Bodies sicherstellen (Art.35 Abs.2 CRA).
        
    
    
        Details zum Verfahren:
        [ /help/konformitaet/konformitaetsbewertung](/help/konformitaet/konformitaetsbewertung)
    

    ## Produktfamilien
    
        Hersteller mit mehr als einem Produkt müssen nicht für jedes Produkt ein separates Konformitätsprojekt durchführen.
        Produkte mit ähnlichen Eigenschaften können zu Produktfamilien zusammengefasst werden.
    

    Relevante Dimensionen (aus Kommissionsleitlinien):

    
        - Gleicher Verwendungszweck und vorhersehbarer Einsatz
        - Ähnliche Assets (kryptografische Schlüssel, Netzwerkfunktionen)
        - Gleiche Bedrohungsprofile
        - Gemeinsame Software-Komponenten / SBOM-Überschneidungen
    

    
        Verwandte Grundlagen:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung),
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Offizielle Quellen
    
        - 
            [
                Verordnung (EU) 2024/2847, Anhang III und IV
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Durchführungsverordnung (EU) 2025/2392 (offizielle Produktkategorien)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
        
        - 
            [
                BSI CRA Flyer #2 - Produktklassifizierung
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                EC FAQ zum CRA (Dez. 2025), Abschnitte 3.1-3.4
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
