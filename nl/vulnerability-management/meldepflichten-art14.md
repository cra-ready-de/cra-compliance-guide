---
title: "CRA-meldplichten volgens Art.14: termijnen van 24h, 72h en 14 dagen"
description: "Vanaf 11 September 2026 moeten fabrikanten actief uitgebuite kwetsbaarheden binnen 24 uur aan het ENISA-platform melden. Alle termijnen en..."
lastUpdated: "2026-05-02"
lang: nl
source: cra-ready.de
---

# CRA-meldplichten volgens Art.14: termijnen van 24h, 72h en 14 dagen

## Inleiding: vanaf wanneer geldt de meldplicht?
    
        Art.14 CRA geldt vanaf **11 September 2026**
        (21 maanden na inwerkingtreding, Art.71 Abs.2 CRA).
    

    
        Dit is de **eerste bindende CRA-verplichting**, nog voor de algemene
        beveiligingseisen (December 2027).
    

    
        Dit geldt voor alle fabrikanten van producten met digitale elementen
        die op de EU-markt beschikbaar worden gesteld.
    

    
        Uitzondering: micro- en kleine ondernemingen zijn vrijgesteld van boetes bij het missen
        van de 24h-termijn (Art.64 Abs.10 CRA, Corrigendum 2025/90555 van 2 July 2025).
        De **PLICHT** om te melden blijft echter bestaan.
    

    ## Wat moet worden gemeld?
    Twee triggers (Art.14 Abs.1 en Abs.3 CRA):

    ### Trigger 1 - Actief uitgebuite kwetsbaarheid
    
        - 
            Definitie: een kwetsbaarheid in het eigen product van de fabrikant, waarvan de fabrikant weet
            dat aanvallers deze actief uitbuiten (Art.14 Abs.1 CRA).
        
        - 
            Meldplicht: onmiddellijk, uiterlijk binnen 24 uur na kennisname
            (Art.14 Abs.2 lit.a CRA).
        
    

    ### Trigger 2 - Ernstig incident (Severe Incident)
    
        - 
            Definitie: een incident dat de beveiliging van het product aantast en gevolgen kan hebben voor
            beschikbaarheid, vertrouwelijkheid of integriteit (Art.14 Abs.3 CRA).
        
        - 
            Meldplicht: onmiddellijk, uiterlijk binnen 24 uur na kennisname
            (Art.14 Abs.4 lit.a CRA).
        
    

    ## De drie meldtermijnen in detail
    
    
            
                
                    Termijn
                    Inhoud
                    Rechtsgrondslag
                
            
            
                
                    **24-uurs eerste melding**
Uiterlijk 24 uur na kennisname
                    Eerste melding (Early Warning); nog geen volledige informatie vereist; indicatie of de kwetsbaarheid of het incident wijst op een onrechtmatige of kwaadwillige handeling
                    Art.14 Abs.2 lit.a en Art.14 Abs.4 lit.a CRA
                
                
                    **72-uurs vervolgmelding**
Uiterlijk 72 uur na kennisname
                    Geactualiseerde melding met beschikbare informatie over de kwetsbaarheid of het incident; eerste conformiteitsbeoordeling; indien van toepassing indicators of compromise (IoC)
                    Art.14 Abs.2 lit.b en Art.14 Abs.4 lit.b CRA
                
                
                    **Eindrapport (14 dagen / 1 maand)**
Kwetsbaarheden: uiterlijk 14 dagen na beschikbaarheid van een beveiligingsupdate of workaround; incidenten: uiterlijk 1 maand na eerste melding
                    Volledige beschrijving; ernst; CVSS-score indien beschikbaar; getroffen versies; genomen maatregelen; status van de beveiligingsupdate
                    Art.14 Abs.2 lit.c en Art.14 Abs.4 lit.c CRA
                
            
        
    

    ## Aan wie wordt gemeld?
    
        - Melding gebeurt aan het CSIRT van de lidstaat van de hoofdvestiging van de fabrikant (Art.14 Abs.1 CRA).
        - In Duitsland: BSI (Bundesamt fuer Sicherheit in der Informationstechnik) als bevoegd CSIRT.
        - 
            Technisch kanaal: ENISA Single Reporting Platform.
            Het platform wordt door ENISA beheerd en stuurt meldingen automatisch door naar het bevoegde nationale CSIRT.
        
        - Status (May 2026): Het platform moet uiterlijk op 11 September 2026 operationeel zijn (Art.16 CRA).
    
    
        **BELANGRIJKE OPMERKING:** De exacte technische specificaties en toegang tot het ENISA-platform
        worden door de Commissie via uitvoeringshandeling vastgesteld (Art.16 Abs.4 CRA).
        Fabrikanten moeten ENISA- en BSI-aankondigingen volgen voor actuele informatie.
    

    ## Gecoordineerde openbaarmaking
    
        - Na melding aan het CSIRT stuurt ENISA de melding door naar andere getroffen CSIRTs (Art.14 Abs.7 CRA).
        - Openbare bekendmaking: ENISA publiceert informatie over gemelde kwetsbaarheden na passende termijnen.
        - 
            Vrijwillige openbaarmaking (Voluntary Disclosure, Art.14 Abs.8 CRA): fabrikanten kunnen kwetsbaarheden
            ook vrijwillig melden; dit geldt als goede praktijk en kan positief worden beoordeeld door toezichthouders.
        
        - 
            security.txt (Art.13 Abs.6 CRA): fabrikanten moeten een contactkanaal voor kwetsbaarheidsmeldingen van derden beschikbaar stellen.
            [ /help/schwachstellenmanagement/security-txt](/help/schwachstellenmanagement/security-txt)
        
    

    ## Wat moet de fabrikant intern voorbereiden?
    
        - Interne procedure voor vulnerability management documenteren (ingangskanaal, conformiteitsbeoordeling, escalatie, meldketen)
        - 24h-bereikbaarheid borgen: wie meldt? in welke taal? met welke toegangsgegevens voor het ENISA-platform?
        - CVSS-beoordelingsproces opzetten (voor het eindrapport)
        - Bewaren van meldingen: minimaal 10 jaar (Art.13 Abs.14 CRA)
        - security.txt opzetten en actueel houden (Art.13 Abs.6 CRA)
        - Afstemming met de toeleveringsketen: componentfabrikanten informeren
        - BSI TR-03183 gebruiken als leidraad voor procesinrichting
    

    ## Sancties bij overtredingen
    
        - 
            Overtreding van meldplichten volgens Art.14: tot 10 miljoen EUR of 2% van de wereldwijde jaaromzet
            (Art.64 Abs.2 CRA - behandeld als overtreding van overige verplichtingen).
        
        - 
            Uitzondering voor kleine en micro-ondernemingen: geen boetes bij het missen van de 24h-termijn
            (Art.64 Abs.10 CRA volgens Corrigendum 2025/90555). De meldplicht zelf blijft bestaan.
        
        - 
            Handhaving door nationale markttoezichtautoriteiten
            (in Duitsland: BSI volgens Art.35 CRA).
        
    

    
        Verwante basisartikelen:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (CE-markering)
    

    ## Officiele bronnen
    
        - 
            [
                Art.14 Regulation (EU) 2024/2847 (full text)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                BSI - CRA reporting obligations
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                ENISA - Cyber Resilience Act
            ](https://www.enisa.europa.eu/topics/cyber-resilience-act)
        
        - 
            [
                EC CRA FAQ (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
