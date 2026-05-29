---
title: "Formati SBOM: CycloneDX vs. SPDX - quale formato per il CRA?"
description: "Confronto dei formati SBOM CycloneDX e SPDX nel contesto dei requisiti CRA (Regulation EU 2024/2847). Vantaggi e svantaggi per i fabbricanti industriali."
lastUpdated: "2026-05-02"
lang: it
source: cra-ready.de
---

# Formati SBOM: CycloneDX vs. SPDX - quale formato per il CRA?

## Perche il formato e importante?
    
        - Il CRA non prescrive un formato, ma compatibilita della toolchain e interoperabilita con le autorita saranno decisive.
        - Due standard dominanti: CycloneDX (OWASP) e SPDX (Linux Foundation).
        - Entrambi supportano JSON, XML ed elaborazione machine-readable.
    

    ## Tabella di confronto CycloneDX vs. SPDX
    
        
            
                
                    Criterio
                    CycloneDX
                    SPDX
                
            
            
                
                    **Editore**
                    OWASP
                    Linux Foundation / ISO/IEC 5962:2021
                
                
                    **Versione attuale**
                    CycloneDX 1.6
                    SPDX 3.0
                
                
                    **Focus primario**
                    Security / gestione delle vulnerabilita
                    Conformita licenze
                
                
                    **Supporto VEX**
                    Si (nativo)
                    Si (da SPDX 3.0)
                
                
                    **Supporto tool**
                    Molto ampio (Syft, Trivy, DependencyTrack)
                    Ampio
                
                
                    **Integrazione DependencyTrack**
                    Supporto nativo
                    Supportato
                
                
                    **Idoneita CRA**
                    Molto buona (focus security)
                    Buona (standard ISO)
                
                
                    **BSI TR-03183**
                    Menzionato come formato idoneo
                    Menzionato come formato idoneo
                
            
        
    

    ## Raccomandazione per utenti CRA-Ready
    
        - Per vulnerability management e notifiche Art.14 e consigliato CycloneDX (supporto VEX nativo, integrazione DependencyTrack).
        - Per supply chains con requisiti di conformita licenze, SPDX e particolarmente adatto.
        - Una combinazione e possibile, perche molti tool possono produrre entrambi i formati.
        - 
            **Nota:** Questa raccomandazione riflette lo stato a May 2026.
            La Commissione puo fissare formati vincolanti con atto di esecuzione.
        
    

    ## Campi minimi per componente (entrambi i formati)
    
        - Nome del componente
        - Version
        - Fornitore / autore
        - PURL (Package URL) - consigliato per identificazione univoca
        - CPE (Common Platform Enumeration) - per matching CVE
        - Licenza (SPDX License Expression)
        - Hash / checksum (SHA-256 consigliato)
    

    
        Approfondimento interno:
        [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
    

    ## Fonti ufficiali
    
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
