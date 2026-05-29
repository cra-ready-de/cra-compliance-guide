---
title: "Was ist der Cyber Resilience Act (CRA)?"
description: "Der Cyber Resilience Act (Verordnung EU 2024/2847) erklärt: Ziele, Geltungsbereich, betroffene Produkte und was Hersteller jetzt wissen müssen."
lastUpdated: "2026-05-02"
lang: de
source: cra-ready.de
---

# Was ist der Cyber Resilience Act (CRA)?

## Einleitung: Was ist der Cyber Resilience Act?
    
        Der Cyber Resilience Act (CRA) ist die **Verordnung (EU) 2024/2847** des Europäischen Parlaments und des Rates.
        Die Verordnung ist seit dem **11. Dezember 2024** in Kraft und wurde am **20. November 2024**
        im Amtsblatt der Europäischen Union veröffentlicht.
    

    
        Als horizontale Verordnung gilt der CRA direkt in allen EU-Mitgliedstaaten; eine nationale Umsetzung ist nicht erforderlich.
        Ziel ist ein einheitlicher Cybersicherheitsrahmen für Produkte mit digitalen Elementen entlang des gesamten Produktlebenszyklus.
    

    ## Warum wurde der CRA eingeführt?
    
        - Zunehmende Cyberangriffe auf vernetzte Produkte (IoT, OT und Industrieanlagen).
        - Vor dem CRA bestand ein fragmentierter Rechtsrahmen mit uneinheitlichen Anforderungen in der EU.
        - Der CRA ergänzt die NIS-2-Richtlinie: NIS-2 fokussiert auf Organisationen, der CRA fokussiert auf Produkte.
    

    ## Was ist ein "Produkt mit digitalen Elementen"?
    
        Die maßgebliche Definition findet sich in **Art.3 Nr.1 CRA**. Erfasst sind Produkte, deren bestimmungsgemäße
        Funktion ganz oder teilweise von Software oder Datenverarbeitung abhängt.
    

    Typische Beispiele sind:

    
        - Industrierouter
        - SPS/PLC
        - SCADA-Software
        - IIoT-Gateways
        - eingebettete Linux-Systeme
        - Netzwerkmanagementsysteme
    
    
        Nicht vom CRA erfasst sind u. a. Produktbereiche mit eigener sektoraler Regulierung, z. B. Medizinprodukte (MDR),
        Fahrzeuge und Luftfahrtprodukte.
    

    ## Wer ist betroffen?
    
        Betroffen sind insbesondere Hersteller (**Art.3 Nr.13**), Bevollmächtigte (**Art.3 Nr.17**),
        Importeure (**Art.3 Nr.18**) und Händler (**Art.3 Nr.19**).
        Für Open-Source Software Stewards (**Art.3 Nr.14**) gelten begrenzte Pflichten.
    

    
        Details zur Rollenabgrenzung finden Sie hier:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich)
    

    ## Was fordert der CRA konkret?
    Die Anforderungen lassen sich in drei Säulen strukturieren:

    ### a) Sicherheitsanforderungen (Anhang I Teil I)
    
        - Secure-by-design und secure-by-default
        - Minimale Angriffsfläche und keine bekannten ausnutzbaren Schwachstellen bei Markteinführung
        - Verschlüsselung, Zugangskontrolle und Integritätsschutz
    

    ### b) Schwachstellenbehandlung (Anhang I Teil II + Art.14)
    
        - 
            Support-Zeitraum: mindestens 5 Jahre ODER die erwartete Nutzungsdauer des Produkts, je nachdem welcher Zeitraum länger ist
            (Art.13 Abs.8 CRA).
        
        - 
            **WICHTIGER HINWEIS:** Der Begriff "erwartete Nutzungsdauer" (expected use time /
            voraussichtliche Nutzungsdauer) ist in Art.3 CRA nicht abschließend definiert. Die Kommission und nationale
            Aufsichtsbehörden werden diesen Begriff produktkategorie- und branchenspezifisch konkretisieren. Hersteller sollten ihre
            Einschätzung der erwarteten Nutzungsdauer in der technischen Dokumentation (Anhang VII) begründen.
        
        - Meldung aktiv ausgenutzter Schwachstellen: 24h / 72h / 14-Tage
    
    
        Details zur Meldekette:
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ### c) Transparenz und Dokumentation
    
        - 
            SBOM:
            [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
        
        - EU-Konformitätserklärung (DoC) und CE-Kennzeichnung
        - 
            CE-Kennzeichnung im Überblick:
            [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
        
        - Technische Dokumentation nach Anhang VII
    

    ## Harmonisierte Normen - Stand 2026
    
        **WICHTIGER HINWEIS FÜR HERSTELLER:**
        Die technische Konformität wird letztlich nicht nur am Verordnungstext, sondern an den harmonisierten Normen
        (Harmonised Standards) gemessen, die CEN, CENELEC und ETSI auf Basis des Normungsauftrags M/606
        (Kommissionsbeschluss C(2025)618 vom 3. Februar 2025) erarbeiten.
    

    Aktueller Stand (Mai 2026):

    
        - Horizontale Typ-A- und Typ-B-Normen (Schwachstellenbehandlung): Fertigstellungsziel August 2026
        - Vertikale Typ-C-Normen (produktkategoriespezifisch): Fertigstellungsziel Oktober 2026
        - Erste Veröffentlichung im Amtsblatt der EU: voraussichtlich Q2 2027
    
    
        Bis zur Veröffentlichung harmonisierter Normen können Hersteller auf bestehende Normen
        (z.B. IEC 62443, ETSI EN 303 645) zurückgreifen, ohne jedoch die CRA-Konformitätsvermutung zu erlangen.
        BSI TR-03183 bietet bereits jetzt eine praxisnahe Orientierung.
    

    ## Produktklassifizierung auf einen Blick
    
        
            
                
                    Kategorie
                    Kurzbeschreibung
                    Conformity Assessment Route
                
            
            
                
                    Default
                    Nicht in Annex III/IV gelistet
                    Interne Kontrolle / Selbstbewertung
                
                
                    Klasse I
                    Wichtige Produktkategorien gemäß CRA
                    Je nach harmonisierten Normen / Drittbewertung möglich
                
                
                    Klasse II
                    Höhere Kritikalität und Risiko
                    In der Regel strengere Konformitätsbewertung
                
                
                    Kritisch
                    Produkte mit besonderer sicherheitsrelevanter Wirkung
                    Zertifizierungs-/Notified-Body-orientierte Route
                
            
        
    
    
        Details zur Klassifizierung:
        [ /help/cra-grundlagen/produktklassifizierung](/help/cra-grundlagen/produktklassifizierung)
    

    
        Hinweis: Die Implementing Regulation (EU) 2025/2392 (28.11.2025) liefert offizielle technische Beschreibungen
        für alle 28 Produktkategorien.
    

    ## Sanktionen
    
        - 
            Bis zu 15 Mio. EUR oder 2,5% des weltweiten Jahresumsatzes
            (für Verstöße gegen Herstellerpflichten, Art.64 Abs.1 CRA)
        
        - 
            Bis zu 10 Mio. EUR oder 2% für andere Wirtschaftsakteure (Art.64 Abs.2 CRA)
        
        - 
            Corrigendum 2025/90555 (2. Juli 2025): Art.64 Abs.10 - Kleinstunternehmen und Kleinunternehmen sind von Bußgeldern
            für Fristversäumnisse bei der 24h-Meldepflicht ausgenommen
        
    
    
        **WICHTIGER HINWEIS:** Die genannten Beträge sind die in Art.64 CRA festgelegten HÖCHSTGRENZEN
        für die gesamte EU. Die tatsächliche Festsetzung und Vollstreckung von Bußgeldern obliegt den nationalen
        Marktüberwachungsbehörden (in Deutschland: BSI als zuständige Behörde gemäß CRA Art.35).
        Verfahren und Praxis können zwischen den Mitgliedstaaten variieren.
    

    ## Offizielle Quellen
    
        - 
            [
                Verordnung (EU) 2024/2847 im EUR-Lex (Volltext)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                EC Digital Strategy - CRA Übersicht
            ](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
        
        - 
            [
                BSI - Cyber Resilience Act
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                Kommission FAQ zum CRA (Dez. 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                Durchführungsverordnung (EU) 2025/2392 (Produktkategorien)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
