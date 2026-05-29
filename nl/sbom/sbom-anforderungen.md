---
title: "SBOM-vereisten volgens CRA: Software Bill of Materials volgens Annex I"
description: "De CRA (Regulation EU 2024/2847) verplicht fabrikanten om een SBOM op te stellen. Wat moet erin staan? Welke formaten zijn geschikt?"
lastUpdated: "2026-05-02"
lang: nl
source: cra-ready.de
---

# SBOM-vereisten volgens CRA: Software Bill of Materials volgens Annex I

## Wat is een SBOM en waarom vereist de CRA die?
    
        - SBOM = Software Bill of Materials: machineleesbare lijst van alle softwarecomponenten van een product, inclusief afhankelijkheden.
        - CRA-eis: Annex I Part II No.1. Fabrikanten moeten kwetsbaarheden in componenten kunnen identificeren en verhelpen.
        - De SBOM is de basis voor kwetsbaarheidsmanagement, toeleveringsketenbeveiliging en technische documentatie (Annex VII CRA).
        - Geldt vanaf: 11 December 2027.
    

    ## Verplichte SBOM-inhoud volgens CRA Annex I
    Minimumeisen (uit Annex I Part II No.1 CRA):

    
        - Alle top-levelcomponenten van het product
        - Transitieve afhankelijkheden (componenten van componenten), voor zover relevant voor identificatie van kwetsbaarheden
        - Per component: naam, versie, leverancier/auteur
        - Unieke identificatoren (bijv. CPE, PURL)
        - Licentie-informatie (voor open-sourcecomponenten)
    
    
        **Opmerking:** De CRA definieert geen verplichte SBOM-standaard.
        De Commissie kan formaten vastleggen via uitvoeringshandeling.
        Tot die tijd zijn CycloneDX en SPDX de-facto-standaarden.
        Formaatvergelijking:
        [ /help/sbom/sbom-formate](/help/sbom/sbom-formate)
    

    ## SBOM in de levenscyclus - updateverplichting
    
        - De SBOM moet bij elke productupdate worden bijgewerkt (Art.13 Abs.5 CRA).
        - Bij beveiligingsupdates moet de SBOM-update gelijktijdig met de update worden gepubliceerd.
        - Bewaring: als onderdeel van de technische documentatie gedurende 10 jaar.
        - Automatisering wordt aanbevolen: SBOM-generatie in de CI/CD-pipeline.
    

    ## SBOM en kwetsbaarheidsmanagement
    
        - De SBOM maakt snelle identificatie van getroffen versies mogelijk wanneer nieuwe kwetsbaarheden bekend worden (CVE-matching).
        - Samenhang met Art.14 CRA: SBOM-gegevens versnellen de eerste 24h-melding, omdat getroffen componenten direct identificeerbaar zijn.
        - VEX (Vulnerability Exploitability eXchange) is een aanvullend formaat voor uitspraken over exploitabiliteit.
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## SBOM-deling
    
        - Aan autoriteiten: op verzoek van de markttoezichtautoriteit (Art.13 Abs.12 CRA).
        - Aan klanten/gebruikers: de CRA vereist geen automatische verstrekking, maar wel transparantie richting gebruikers (Art.13 Abs.18 CRA).
        - **Opmerking:** Commerciele vertrouwelijkheid kan beperkingen op openbare SBOM-publicatie rechtvaardigen.
    

    ## Officiele bronnen
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Annex I Part II)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                https://ec.europa.eu/newsroom/dae/redirection/document/109664
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                https://ntia.gov/sbom (NTIA SBOM-bronnen)
            ](https://ntia.gov/sbom)
        
        - 
            [
                https://cyclonedx.org (CycloneDX-standaard)
            ](https://cyclonedx.org)
        
        - 
            [
                https://spdx.dev (SPDX-standaard)
            ](https://spdx.dev)
