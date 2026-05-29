---
title: "Exigences SBOM selon le CRA : Software Bill of Materials selon l Annexe I"
description: "Le CRA (Regulation EU 2024/2847) oblige les fabricants a etablir une SBOM. Que doit-elle contenir ? Quels formats sont adaptes ?"
lastUpdated: "2026-05-02"
lang: fr
source: cra-ready.de
---

# Exigences SBOM selon le CRA : Software Bill of Materials selon l Annexe I

## Qu est-ce qu une SBOM et pourquoi le CRA l exige-t-il ?
    
        - SBOM = Software Bill of Materials : liste lisible par machine de tous les composants logiciels d un produit, y compris les dependances.
        - Exigence CRA : Annexe I Partie II No.1. Les fabricants doivent pouvoir identifier et corriger les vulnerabilites dans les composants.
        - La SBOM est la base de la gestion des vulnerabilites, de la securite de la chaine d approvisionnement et de la documentation technique (Annexe VII CRA).
        - Applicable a partir du : 11 December 2027.
    

    ## Contenu obligatoire de la SBOM selon l Annexe I CRA
    Exigences minimales (selon Annexe I Partie II No.1 CRA) :

    
        - Tous les composants de premier niveau du produit
        - Dependances transitives (composants des composants), lorsque pertinentes pour l identification des vulnerabilites
        - Pour chaque composant : nom, version, fournisseur/auteur
        - Identifiants uniques (par ex. CPE, PURL)
        - Informations de licence (pour les composants open source)
    
    
        **Remarque :** Le CRA ne definit pas de standard SBOM obligatoire.
        La Commission peut definir des formats par acte d execution.
        Jusque-la, CycloneDX et SPDX sont des standards de-facto.
        Comparaison des formats :
        [ /help/sbom/sbom-formate](/help/sbom/sbom-formate)
    

    ## SBOM dans le cycle de vie - obligation de mise a jour
    
        - La SBOM doit etre mise a jour a chaque mise a jour du produit (Art.13 Abs.5 CRA).
        - Pour les mises a jour de securite, la mise a jour SBOM devrait etre publiee en meme temps.
        - Conservation : en tant que partie de la documentation technique pendant 10 ans.
        - L automatisation est recommandee : generation de la SBOM dans la pipeline CI/CD.
    

    ## SBOM et gestion des vulnerabilites
    
        - La SBOM permet l identification rapide des versions affectees lorsque de nouvelles vulnerabilites sont connues (mise en correspondance CVE).
        - Interaction avec Art.14 CRA : les donnees SBOM accelerent la notification initiale sous 24h, car les composants affectes sont immediatement identifiables.
        - VEX (Vulnerability Exploitability eXchange) est un format complementaire pour les declarations d exploitabilite.
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Transmission de la SBOM
    
        - Aux autorites : sur demande de l autorite de surveillance du marche (Art.13 Abs.12 CRA).
        - Aux clients/utilisateurs : le CRA n exige pas de diffusion automatique, mais impose une obligation de transparence envers les utilisateurs (Art.13 Abs.18 CRA).
        - **Remarque :** La confidentialite commerciale peut justifier des restrictions de diffusion publique de la SBOM.
    

    ## Sources officielles
    
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
                https://ntia.gov/sbom (Ressources SBOM NTIA)
            ](https://ntia.gov/sbom)
        
        - 
            [
                https://cyclonedx.org (Standard CycloneDX)
            ](https://cyclonedx.org)
        
        - 
            [
                https://spdx.dev (Standard SPDX)
            ](https://spdx.dev)
