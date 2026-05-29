---
title: "SBOM-formaten: CycloneDX vs. SPDX - welk format voor de CRA?"
description: "Vergelijking van de SBOM-formaten CycloneDX en SPDX in de context van CRA-eisen (Regulation EU 2024/2847). Voor- en nadelen voor industriele fabrikanten."
lastUpdated: "2026-05-02"
lang: nl
source: cra-ready.de
---

# SBOM-formaten: CycloneDX vs. SPDX - welk format voor de CRA?

## Waarom is het format belangrijk?
    
        - De CRA schrijft geen format voor, maar toolchain-compatibiliteit en interoperabiliteit met autoriteiten worden cruciaal.
        - Twee dominante standaarden: CycloneDX (OWASP) en SPDX (Linux Foundation).
        - Beide ondersteunen JSON, XML en machineleesbare verwerking.
    

    ## Vergelijkingstabel CycloneDX vs. SPDX
    
        
            
                
                    Criterium
                    CycloneDX
                    SPDX
                
            
            
                
                    **Uitgever**
                    OWASP
                    Linux Foundation / ISO/IEC 5962:2021
                
                
                    **Huidige versie**
                    CycloneDX 1.6
                    SPDX 3.0
                
                
                    **Primaire focus**
                    Security / kwetsbaarheidsmanagement
                    Licentiecompliance
                
                
                    **VEX-ondersteuning**
                    Ja (native)
                    Ja (vanaf SPDX 3.0)
                
                
                    **Tool-ondersteuning**
                    Zeer breed (Syft, Trivy, DependencyTrack)
                    Breed
                
                
                    **DependencyTrack-integratie**
                    Native ondersteund
                    Ondersteund
                
                
                    **CRA-geschiktheid**
                    Zeer goed (security-focus)
                    Goed (ISO-standaard)
                
                
                    **BSI TR-03183**
                    Vermeld als geschikt format
                    Vermeld als geschikt format
                
            
        
    

    ## Aanbeveling voor CRA-Ready gebruikers
    
        - Voor kwetsbaarheidsmanagement en Art.14-meldingen wordt CycloneDX aanbevolen (native VEX-support, DependencyTrack-integratie).
        - Voor supply chains met licentiecompliance-eisen is SPDX bijzonder geschikt.
        - Een combinatie is mogelijk, omdat veel tools beide formaten kunnen exporteren.
        - 
            **Opmerking:** Deze aanbeveling is gebaseerd op de stand van May 2026.
            De Commissie kan formaten bindend vastleggen via uitvoeringshandeling.
        
    

    ## Minimumvelden per component (beide formaten)
    
        - Naam van de component
        - Version
        - Leverancier / auteur
        - PURL (Package URL) - aanbevolen voor eenduidige identificatie
        - CPE (Common Platform Enumeration) - voor CVE-matching
        - Licentie (SPDX License Expression)
        - Hash / checksum (SHA-256 aanbevolen)
    

    
        Interne verdieping:
        [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
    

    ## Officiele bronnen
    
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
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Anhang I Teil II)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
