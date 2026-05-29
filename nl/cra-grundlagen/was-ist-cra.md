---
title: "Wat is de Cyber Resilience Act (CRA)?"
description: "Uitleg van de Cyber Resilience Act (Regulation (EU) 2024/2847): doelstellingen, toepassingsgebied, betrokken producten en wat fabrikanten nu moeten weten."
lastUpdated: "2026-05-02"
lang: nl
source: cra-ready.de
---

# Wat is de Cyber Resilience Act (CRA)?

## Inleiding: Wat is de Cyber Resilience Act?
    
        De Cyber Resilience Act (CRA) is **Regulation (EU) 2024/2847** van het Europees Parlement en de Raad.
        De Regulation is van kracht sinds **11 December 2024** en werd op **20 November 2024**
        gepubliceerd in het Publicatieblad van de Europese Unie.
    

    
        Als horizontale verordening geldt de CRA rechtstreeks in alle EU-lidstaten; nationale omzetting is niet vereist.
        Het doel is een uniform cyberbeveiligingskader voor producten met digitale elementen gedurende de volledige productlevenscyclus.
    

    ## Waarom is de CRA ingevoerd?
    
        - Toenemende cyberaanvallen op verbonden producten (IoT, OT en industriële installaties).
        - Vóór de CRA bestond een gefragmenteerd juridisch kader met niet-uniforme eisen in de EU.
        - De CRA vult de NIS-2-richtlijn aan: NIS-2 richt zich op organisaties, de CRA op producten.
    

    ## Wat is een "product met digitale elementen"?
    
        De relevante definitie staat in **Art.3 Nr.1 CRA**. Het gaat om producten waarvan de beoogde
        functie geheel of gedeeltelijk afhankelijk is van software of gegevensverwerking.
    

    Typische voorbeelden zijn:

    
        - Industriële routers
        - SPS/PLC-systemen
        - SCADA-software
        - IIoT-gateways
        - Embedded Linux-systemen
        - Netwerkbeheersystemen
    
    
        Niet onder de CRA vallen onder meer productdomeinen met eigen sectorspecifieke regelgeving,
        zoals medische hulpmiddelen (MDR), voertuigen en luchtvaartproducten.
    

    ## Wie wordt geraakt?
    
        Met name fabrikanten (**Art.3 Nr.13**), gemachtigden (**Art.3 Nr.17**),
        importeurs (**Art.3 Nr.18**) en distributeurs (**Art.3 Nr.19**) worden geraakt.
        Voor open-source software stewards (**Art.3 Nr.14**) gelden beperkte verplichtingen.
    

    
        Details over de rolafbakening vindt u hier:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich)
    

    ## Wat eist de CRA concreet?
    De eisen kunnen in drie pijlers worden gestructureerd:

    ### a) Beveiligingseisen (Annex I Part I)
    
        - Secure-by-design en secure-by-default
        - Minimaal aanvalsoppervlak en geen bekende uitbuitbare kwetsbaarheden bij marktintroductie
        - Versleuteling, toegangscontrole en integriteitsbescherming
    

    ### b) Kwetsbaarhedenbeheer (Annex I Part II + Art.14)
    
        - 
            Supportperiode: minimaal 5 jaar OF de verwachte gebruiksduur van het product, afhankelijk van welke periode langer is
            (Art.13 Abs.8 CRA).
        
        - 
            **BELANGRIJKE OPMERKING:** De term "expected use time"
            (expected use time / voraussichtliche Nutzungsdauer) is in Art.3 CRA niet uitputtend gedefinieerd.
            De Commissie en nationale toezichthoudende autoriteiten zullen dit begrip per productcategorie en sector nader concretiseren.
            Fabrikanten moeten hun inschatting van de verwachte gebruiksduur onderbouwen in de technische documentatie (Annex VII).
        
        - Melding van actief uitgebuite kwetsbaarheden: 24h / 72h / 14 dagen
    
    
        Details over de meldketen:
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ### c) Transparantie en documentatie
    
        - 
            SBOM:
            [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
        
        - EU-conformiteitsverklaring (DoC) en CE-markering
        - 
            Overzicht CE-markering:
            [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
        
        - Technische documentatie volgens Annex VII
    

    ## Geharmoniseerde normen - stand 2026
    
        **BELANGRIJKE OPMERKING VOOR FABRIKANTEN:**
        Technische conformiteit wordt uiteindelijk niet alleen gemeten aan de tekst van de Regulation,
        maar ook aan de geharmoniseerde normen (Harmonised Standards) die CEN, CENELEC en ETSI opstellen
        op basis van normalisatieopdracht M/606 (Commissiebesluit C(2025)618 van **3 February 2025**).
    

    Huidige stand (May 2026):

    
        - Horizontale type-A- en type-B-normen (kwetsbaarhedenbeheer): opleverdoel August 2026
        - Verticale type-C-normen (productspecifiek): opleverdoel October 2026
        - Eerste publicatie in het Publicatieblad van de EU: naar verwachting Q2 2027
    
    
        Tot de publicatie van geharmoniseerde normen kunnen fabrikanten terugvallen op bestaande normen
        (bijv. IEC 62443, ETSI EN 303 645), zonder de CRA-vermoedens van conformiteit te verkrijgen.
        BSI TR-03183 biedt nu al praktische oriëntatie.
    

    ## Productclassificatie in één oogopslag
    
        
            
                
                    Categorie
                    Korte beschrijving
                    Route voor conformiteitsbeoordeling
                
            
            
                
                    Default
                    Niet opgenomen in Annex III/IV
                    Interne controle / zelfbeoordeling
                
                
                    Klasse I
                    Belangrijke productcategorieën volgens de CRA
                    Afhankelijk van geharmoniseerde normen / beoordeling door derden mogelijk
                
                
                    Klasse II
                    Hogere kriticiteit en hoger risico
                    Doorgaans strengere conformiteitsbeoordeling
                
                
                    Kritiek
                    Producten met bijzondere veiligheidsrelevantie
                    Certificeringsroute / route met aangemelde instantie
                
            
        
    
    
        Details over classificatie:
        [ /help/cra-grundlagen/produktklassifizierung](/help/cra-grundlagen/produktklassifizierung)
    

    
        Opmerking: Implementing Regulation (EU) 2025/2392 (**28 November 2025**) bevat officiële technische beschrijvingen
        voor alle 28 productcategorieën.
    

    ## Sancties
    
        - 
            Tot 15 miljoen EUR of 2,5% van de wereldwijde jaaromzet
            (voor overtredingen van fabrikantenverplichtingen, Art.64 Abs.1 CRA)
        
        - 
            Tot 10 miljoen EUR of 2% voor andere marktdeelnemers (Art.64 Abs.2 CRA)
        
        - 
            Corrigendum 2025/90555 (**2 July 2025**): Art.64 Abs.10 - micro- en kleine ondernemingen zijn vrijgesteld van boetes
            bij termijnoverschrijding van de 24h-meldplicht
        
    
    
        **BELANGRIJKE OPMERKING:** De genoemde bedragen zijn de in Art.64 CRA vastgelegde MAXIMALE GRENZEN
        voor de gehele EU. De daadwerkelijke vaststelling en handhaving van boetes is aan nationale
        markttoezichtautoriteiten (in Duitsland: BSI als bevoegde autoriteit volgens CRA Art.35).
        Procedures en praktijk kunnen tussen lidstaten verschillen.
    

    ## Officiële bronnen
    
        - 
            [
                Regulation (EU) 2024/2847 in EUR-Lex (volledige tekst)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                EC Digital Strategy - CRA-overzicht
            ](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
        
        - 
            [
                BSI - Cyber Resilience Act
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                FAQ van de Commissie over de CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (productcategorieën)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
