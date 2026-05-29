---
title: "Formats SBOM: CycloneDX vs. SPDX - quel format pour le CRA ?"
description: "Comparaison des formats SBOM CycloneDX et SPDX dans le contexte des exigences CRA (Regulation EU 2024/2847). Avantages et limites pour les fabricants..."
lastUpdated: "2026-05-02"
lang: fr
source: cra-ready.de
---

# Formats SBOM: CycloneDX vs. SPDX - quel format pour le CRA ?

## Pourquoi le format est-il important ?
    
        - Le CRA ne prescrit pas de format, mais la compatibilite des toolchains et l interoperabilite avec les autorites seront decisives.
        - Deux standards dominants : CycloneDX (OWASP) et SPDX (Linux Foundation).
        - Les deux prennent en charge JSON, XML et le traitement lisible par machine.
    

    ## Tableau comparatif CycloneDX vs. SPDX
    
        
            
                
                    Critere
                    CycloneDX
                    SPDX
                
            
            
                
                    **Editeur**
                    OWASP
                    Linux Foundation / ISO/IEC 5962:2021
                
                
                    **Version actuelle**
                    CycloneDX 1.6
                    SPDX 3.0
                
                
                    **Focus principal**
                    Securite / gestion des vulnerabilites
                    Conformite des licences
                
                
                    **Support VEX**
                    Oui (natif)
                    Oui (a partir de SPDX 3.0)
                
                
                    **Support outillage**
                    Tres large (Syft, Trivy, DependencyTrack)
                    Large
                
                
                    **Integration DependencyTrack**
                    Support natif
                    Supporte
                
                
                    **Adequation CRA**
                    Tres bonne (focus securite)
                    Bonne (standard ISO)
                
                
                    **BSI TR-03183**
                    Mentionne comme format approprie
                    Mentionne comme format approprie
                
            
        
    

    ## Recommandation pour les utilisateurs CRA-Ready
    
        - Pour la gestion des vulnerabilites et les notifications Art.14, CycloneDX est recommande (support VEX natif, integration DependencyTrack).
        - Pour les supply chains avec exigences de conformite des licences, SPDX est tres adapte.
        - Une combinaison est possible, car de nombreux outils peuvent produire les deux formats.
        - 
            **Remarque :** Cette recommandation reflete l etat en May 2026.
            La Commission peut fixer des formats obligatoires par acte d execution.
        
    

    ## Champs minimaux par composant (deux formats)
    
        - Nom du composant
        - Version
        - Fournisseur / auteur
        - PURL (Package URL) - recommande pour une identification unique
        - CPE (Common Platform Enumeration) - pour le rapprochement CVE
        - Licence (SPDX License Expression)
        - Hash / checksum (SHA-256 recommande)
    

    
        Approfondissement interne :
        [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
    

    ## Sources officielles
    
        - 
            [
                https://cyclonedx.org/specification/overview/
            ](https://cyclonedx.org/specification/overview/)
        
        - 
            [
                https://spdx.dev/specifications/
            ](https://spdx.dev/specifications/)
        
        - 
            [
                https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/CyberSecurity/products/technical-guidelines/TR-03183/BSI-TR-03183-2.pdf
            ](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/CyberSecurity/products/technical-guidelines/TR-03183/BSI-TR-03183-2.pdf)
        
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Annexe I Partie II)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
