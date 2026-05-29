---
title: "CRA-productclassificatie: Default, Klasse I, Klasse II en Kritiek"
description: "Hoe classificeert u uw product onder Regulation (EU) 2024/2847? Default, Belangrijk Klasse I/II of Kritiek, met officiele beschrijvingen uit..."
lastUpdated: "2026-05-02"
lang: nl
source: cra-ready.de
---

# CRA-productclassificatie: Default, Klasse I, Klasse II en Kritiek

## Inleiding: waarom is classificatie doorslaggevend?
    
        De productklasse bepaalt de procedure voor conformiteitsbeoordeling en daarmee de inspanning en kosten van
        CRA-conformiteit voor producten met digitale elementen.
    

    
        De rechtsgrondslag is **CRA Annex III** (belangrijke producten) en **CRA Annex IV**
        (kritieke producten).
    

    
        Nadere specificatie wordt gegeven door **Implementing Regulation (EU) 2025/2392** van
        **28 November 2025** (gepubliceerd in het Publicatieblad van de EU op **1 December 2025**).
        Deze verordening geeft officiele technische beschrijvingen voor alle 28 productcategorieen in Annex III en IV,
        en neemt daarmee de eerdere interpretatie-onzekerheid weg.
    

    
        **BELANGRIJK:** Het doorslaggevende criterium is de **KERNFUNCTIE** van het product,
        niet de naam, marketingbenaming of nevenfuncties
        (EC FAQ Dec 2025, sections 3.2 and 3.4; Implementing Regulation (EU) 2025/2392, recitals 3-5).
    

    ## Het vierstappenmodel
    
        
            
                
                    Niveau
                    Rechtsgrondslag
                    Voorbeelden (industrieel relevant)
                    Conformiteitsbeoordeling
                
            
            
                
                    **Standard (Default)**
                    Alle producten die NIET in Annex III of IV staan (~90% van alle producten)
                    Eenvoudige embedded systemen zonder netwerkfunctie, offline industriele HMI, niet-verbonden besturingseenheden
                    Zelfbeoordeling (Module A, Art.32 para.1 CRA)
                
                
                    **Belangrijk Klasse I**
                    CRA Annex III Klasse I + Implementing Regulation (EU) 2025/2392 Annex I Part 1
                    Wachtwoordmanagers, netwerkbeheersystemen, netwerkmonitoringsoftware, besturingssystemen voor algemeen gebruik, thuisrouters en modems, switches
                    Zelfbeoordeling ALLEEN bij toepassing van geharmoniseerde normen (Art.32 para.2 CRA); anders aangemelde instantie vereist
                
                
                    **Belangrijk Klasse II**
                    CRA Annex III Klasse II + Implementing Regulation (EU) 2025/2392 Annex I Part 2
                    Hypervisors, firewalls, intrusion detection/prevention-systemen, industriele automatiserings- en besturingssystemen (IACS) alleen bij gebruik door entiteiten die onder NIS-2 vallen, manipulatieresistente microprocessors
                    Aangemelde instantie VERPLICHT (Art.32 para.3 CRA) OF EU-cybersecuritycertificering (Art.32 para.4)
                
                
                    **Kritiek**
                    CRA Annex IV + Implementing Regulation (EU) 2025/2392 Annex II
                    Hardware security modules (HSM), smartcard-IC's, smartcards en vergelijkbare apparaten, apparaten voor geavanceerde beveiligingsdoeleinden (bijv. gecertificeerde hardwaretokens)
                    Aangemelde instantie VERPLICHT of EU-cybersecuritycertificering (Art.33 and 34 CRA)
                
            
        
    

    ## De kernfunctietoets
    
        **BELANGRIJKE INTERPRETATIENOTITIE:** Een product wordt geclassificeerd op basis van de KERNFUNCTIE,
        niet op basis van geintegreerde componenten.
    

    Voorbeelden uit de EC FAQ (Dec 2025):

    
        - Een smartphone met geintegreerde wachtwoordmanager blijft in de standaardcategorie, omdat de kernfunctie geen wachtwoordbeheer is.
        - Een app met ingebouwde browser is geen "browser"-product, omdat de kernfunctie niet browsen is.
        - Een industrieel automatiseringssysteem is Klasse II ALLEEN wanneer de exploitant onder NIS-2 valt (Implementing Regulation (EU) 2025/2392).
    
    
        Opmerking: de exacte afbakening bij producten met meerdere functies kan per geval complex zijn.
        De Commissie heeft aanvullende richtsnoeren aangekondigd.
    

    ## Overzicht van conformiteitsbeoordelingsprocedures
    
        - 
            **Module A (zelfbeoordeling):** De fabrikant stelt de technische documentatie op en geeft de
            EU-conformiteitsverklaring af. Voldoende voor Default en Klasse I bij toepassing van geharmoniseerde normen.
        
        - 
            **Aangemelde instantie:** Een onafhankelijke derde partij voert de conformiteitsbeoordeling uit.
            Vereist voor Klasse I zonder geharmoniseerde normen, Klasse II en Kritiek.
        
        - 
            **Status van aangemelde instanties (May 2026):** Lidstaten moesten procedures voor beoordeling en
            aanwijzing van conformiteitsbeoordelingsinstanties publiceren voor 11 June 2026 (Art.35 CRA).
            Lidstaten moeten zorgen voor voldoende aangemelde instanties voor 11 December 2026 (Art.35 para.2 CRA).
        
    
    
        Details van de procedure:
        [ /help/konformitaet/konformitaetsbewertung](/help/konformitaet/konformitaetsbewertung)
    

    ## Productfamilies
    
        Fabrikanten met meer dan een product hoeven niet voor elk product een afzonderlijk conformiteitsproject uit te voeren.
        Producten met vergelijkbare kenmerken kunnen worden gebundeld in productfamilies.
    

    Relevante dimensies (volgens richtsnoeren van de Commissie):

    
        - Zelfde beoogd doel en voorzienbaar gebruik
        - Vergelijkbare assets (cryptografische sleutels, netwerkfuncties)
        - Zelfde dreigingsprofielen
        - Gedeelde softwarecomponenten / SBOM-overlap
    

    
        Gerelateerde basisartikelen:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (CE-markering),
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Officiele bronnen
    
        - 
            [
                Regulation (EU) 2024/2847, Annex III and IV
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (officiele productcategorieen)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
        
        - 
            [
                BSI CRA Flyer #2 - Productclassificatie
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                EC CRA FAQ (Dec 2025), sections 3.1-3.4
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
