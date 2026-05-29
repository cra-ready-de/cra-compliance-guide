---
title: "CRA Meldepflichten nach Art.14: 24h, 72h und 14-Tage-Fristen"
description: "Art.14 CRA: Meldepflichten ab September 2026. Fristen 24h, 72h und 14 Tage für Schwachstellen nach Verordnung (EU) 2024/2847."
lastUpdated: "2026-05-02"
lang: de
source: cra-ready.de
---

# CRA Meldepflichten nach Art.14: 24h, 72h und 14-Tage-Fristen

## Einleitung: Ab wann gilt die Meldepflicht?
    
        Art.14 CRA gilt ab dem **11. September 2026**
        (21 Monate nach Inkrafttreten, Art.71 Abs.2 CRA).
    

    
        Das ist die **erste verbindliche CRA-Pflicht**, noch vor den allgemeinen
        Sicherheitsanforderungen (Dezember 2027).
    

    
        Betroffen sind alle Hersteller von Produkten mit digitalen Elementen,
        die auf dem EU-Markt bereitgestellt werden.
    

    
        Ausnahme: Kleinstunternehmen und Kleinunternehmen sind von Bußgeldern für Fristversäumnisse
        bei der 24h-Meldung ausgenommen (Art.64 Abs.10 CRA, Corrigendum 2025/90555 vom 2. Juli 2025).
        Die **PFLICHT** zur Meldung besteht jedoch weiterhin.
    

    ## Was muss gemeldet werden?
    Zwei Auslöser (Art.14 Abs.1 und Abs.3 CRA):

    ### Auslöser 1 - Aktiv ausgenutzte Schwachstelle
    
        - 
            Definition: Eine Schwachstelle im eigenen Produkt, für die der Hersteller Kenntnis hat,
            dass sie aktiv von Angreifern ausgenutzt wird (Art.14 Abs.1 CRA).
        
        - 
            Meldepflicht: sofort, spätestens binnen 24 Stunden nach Kenntniserlangung
            (Art.14 Abs.2 lit.a CRA).
        
    

    ### Auslöser 2 - Schwerwiegender Vorfall (Severe Incident)
    
        - 
            Definition: Ein Vorfall, der die Sicherheit des Produkts beeinträchtigt und Auswirkungen auf
            Verfügbarkeit, Vertraulichkeit oder Integrität haben kann (Art.14 Abs.3 CRA).
        
        - 
            Meldepflicht: sofort, spätestens binnen 24 Stunden nach Kenntniserlangung
            (Art.14 Abs.4 lit.a CRA).
        
    

    ## Die drei Meldefristen im Detail
    
    
            
                
                    Frist
                    Inhalt
                    Rechtsgrundlage
                
            
            
                
                    **24-Stunden-Erstmeldung**
Spätestens 24 Stunden nach Kenntniserlangung
                    Erste Meldung (Early Warning); noch keine vollständigen Informationen erforderlich; Hinweis, ob Schwachstelle oder Vorfall auf rechtswidrige oder böswillige Handlung hindeutet
                    Art.14 Abs.2 lit.a und Art.14 Abs.4 lit.a CRA
                
                
                    **72-Stunden-Folgemeldung**
Spätestens 72 Stunden nach Kenntniserlangung
                    Aktualisierte Meldung mit verfügbaren Informationen zur Schwachstelle oder zum Vorfall; erste Bewertung; gegebenenfalls Indikatoren für Kompromittierung (IoC)
                    Art.14 Abs.2 lit.b und Art.14 Abs.4 lit.b CRA
                
                
                    **Abschlussbericht (14 Tage / 1 Monat)**
Schwachstellen: spätestens 14 Tage nach Verfügbarkeit eines Sicherheitsupdates oder Workarounds; Vorfälle: spätestens 1 Monat nach Erstmeldung
                    Vollständige Beschreibung; Schweregrad; CVSS-Score falls verfügbar; betroffene Versionen; ergriffene Maßnahmen; Status des Sicherheitsupdates
                    Art.14 Abs.2 lit.c und Art.14 Abs.4 lit.c CRA
                
            
        
    

    ## An wen wird gemeldet?
    
        - Meldung erfolgt an das CSIRT des Mitgliedstaats der Hauptniederlassung des Herstellers (Art.14 Abs.1 CRA).
        - In Deutschland: BSI (Bundesamt für Sicherheit in der Informationstechnik) als zuständiges CSIRT.
        - 
            Technischer Kanal: ENISA Single Reporting Platform.
            Die Plattform wird von ENISA betrieben und leitet Meldungen automatisch an das zuständige nationale CSIRT weiter.
        
        - Status (Mai 2026): Die Plattform muss bis 11. September 2026 betriebsbereit sein (Art.16 CRA).
    
    
        **WICHTIGER HINWEIS:** Die genauen technischen Spezifikationen und der Zugang zur ENISA-Plattform
        werden von der Kommission per Durchführungsrechtsakt festgelegt (Art.16 Abs.4 CRA).
        Hersteller sollten die ENISA-Website und BSI-Ankündigungen für aktuelle Informationen verfolgen.
    

    ## Koordinierte Offenlegung
    
        - Nach der Meldung an das CSIRT leitet ENISA die Meldung an andere betroffene CSIRTs weiter (Art.14 Abs.7 CRA).
        - Öffentliche Bekanntmachung: ENISA veröffentlicht Informationen zu gemeldeten Schwachstellen nach Ablauf angemessener Fristen.
        - 
            Freiwillige Offenlegung (Voluntary Disclosure, Art.14 Abs.8 CRA): Hersteller können Schwachstellen auch
            freiwillig melden; dies gilt als gute Praxis und kann bei der Bewertung durch Aufsichtsbehörden positiv
            berücksichtigt werden.
        
        - 
            security.txt (Art.13 Abs.6 CRA): Hersteller müssen einen Kontaktweg für Schwachstellenmeldungen Dritter bereitstellen.
            [ /help/schwachstellenmanagement/security-txt](/help/schwachstellenmanagement/security-txt)
        
    

    ## Was muss der Hersteller intern vorbereiten?
    
        - Internes Vulnerability-Management-Verfahren dokumentieren (Eingangskanal, Bewertung, Eskalation, Meldekette)
        - 24h-Bereitschaft sicherstellen: Wer meldet? In welcher Sprache? Mit welchen Zugangsdaten zur ENISA-Plattform?
        - CVSS-Bewertungsverfahren etablieren (für Abschlussbericht)
        - Aufbewahrung der Meldungen: mindestens 10 Jahre (Art.13 Abs.14 CRA)
        - security.txt einrichten und aktuell halten (Art.13 Abs.6 CRA)
        - Koordination mit Lieferkette: Komponenten-Hersteller informieren
        - BSI TR-03183 als Orientierung für Prozessgestaltung nutzen
    

    ## Sanktionen bei Verstößen
    
        - 
            Verstoß gegen Meldepflichten nach Art.14: bis zu 10 Mio. EUR oder 2% des weltweiten Jahresumsatzes
            (Art.64 Abs.2 CRA - Verstoß gegen andere Pflichten).
        
        - 
            Ausnahme für Kleinunternehmen und Kleinstunternehmen: keine Bußgelder für Versäumnis der 24h-Frist
            (Art.64 Abs.10 CRA i.d.F. Corrigendum 2025/90555). Die Meldepflicht selbst bleibt bestehen.
        
        - 
            Vollstreckung durch nationale Marktüberwachungsbehörden
            (in Deutschland: BSI gemäß Art.35 CRA).
        
    

    
        Verwandte Grundlagen:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
    

    ## Offizielle Quellen
    
        - 
            [
                Art.14 Verordnung (EU) 2024/2847 (Volltext)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                BSI - CRA Meldepflichten
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                ENISA - Cyber Resilience Act
            ](https://www.enisa.europa.eu/topics/cyber-resilience-act)
        
        - 
            [
                EC FAQ zum CRA (Dez. 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
