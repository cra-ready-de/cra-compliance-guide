---
title: "Requisiti SBOM secondo il CRA: Software Bill of Materials secondo Annex I"
description: "Il CRA (Regulation EU 2024/2847) obbliga i fabbricanti a creare una SBOM. Cosa deve contenere? Quali formati sono adatti?"
lastUpdated: "2026-05-02"
lang: it
source: cra-ready.de
---

# Requisiti SBOM secondo il CRA: Software Bill of Materials secondo Annex I

## Che cos e una SBOM e perche il CRA la richiede?
    
        - SBOM = Software Bill of Materials: elenco leggibile da macchina di tutti i componenti software di un prodotto, incluse le dipendenze.
        - Requisito CRA: Annex I Part II No.1. I fabbricanti devono poter identificare e correggere le vulnerabilita nei componenti.
        - La SBOM e la base per gestione delle vulnerabilita, sicurezza della supply chain e documentazione tecnica (Annex VII CRA).
        - Si applica dal: 11 December 2027.
    

    ## Contenuto obbligatorio della SBOM secondo CRA Annex I
    Requisiti minimi (da Annex I Part II No.1 CRA):

    
        - Tutti i componenti top-level del prodotto
        - Dipendenze transitive (componenti dei componenti), per quanto rilevanti per l identificazione delle vulnerabilita
        - Per ogni componente: nome, versione, fornitore/autore
        - Identificatori univoci (es. CPE, PURL)
        - Informazioni di licenza (per componenti open source)
    
    
        **Nota:** Il CRA non definisce uno standard SBOM obbligatorio.
        La Commissione puo definire i formati tramite atto di esecuzione.
        Fino ad allora, CycloneDX e SPDX sono standard de-facto.
        Confronto dei formati:
        [ /help/sbom/sbom-formate](/help/sbom/sbom-formate)
    

    ## SBOM nel ciclo di vita - obbligo di aggiornamento
    
        - La SBOM deve essere aggiornata a ogni aggiornamento del prodotto (Art.13 Abs.5 CRA).
        - Per gli aggiornamenti di sicurezza, l aggiornamento della SBOM dovrebbe essere pubblicato nello stesso momento.
        - Conservazione: come parte della documentazione tecnica per 10 anni.
        - E raccomandata l automazione: generazione SBOM nella pipeline CI/CD.
    

    ## SBOM e gestione delle vulnerabilita
    
        - La SBOM consente l identificazione rapida delle versioni coinvolte quando diventano note nuove vulnerabilita (matching CVE).
        - Interazione con Art.14 CRA: i dati SBOM accelerano la prima notifica entro 24h, perche i componenti interessati sono subito identificabili.
        - VEX (Vulnerability Exploitability eXchange) e un formato complementare per dichiarazioni sull exploitability.
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Condivisione della SBOM
    
        - Alle autorita: su richiesta dell autorita di vigilanza del mercato (Art.13 Abs.12 CRA).
        - A clienti/utenti: il CRA non richiede distribuzione automatica, ma richiede trasparenza verso gli utenti (Art.13 Abs.18 CRA).
        - **Nota:** La riservatezza commerciale puo giustificare restrizioni alla divulgazione pubblica della SBOM.
    

    ## Fonti ufficiali
    
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
                https://ntia.gov/sbom (Risorse SBOM NTIA)
            ](https://ntia.gov/sbom)
        
        - 
            [
                https://cyclonedx.org (Standard CycloneDX)
            ](https://cyclonedx.org)
        
        - 
            [
                https://spdx.dev (Standard SPDX)
            ](https://spdx.dev)
