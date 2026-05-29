---
title: "SBOM-Formate: CycloneDX vs. SPDX – Welches Format für den CRA?"
description: "Vergleich der SBOM-Formate CycloneDX und SPDX im Kontext der CRA-Anforderungen (Verordnung EU 2024/2847). Vor- und Nachteile für Industriehersteller."
lastUpdated: "2026-05-02"
lang: de
source: cra-ready.de
---

# SBOM-Formate: CycloneDX vs. SPDX – Welches Format für den CRA?

## Warum ist das Format wichtig?
    
        - Der CRA schreibt kein Format vor, aber Toolchain-Kompatibilität und Interoperabilität mit Behörden werden entscheidend.
        - Zwei dominante Standards: CycloneDX (OWASP) und SPDX (Linux Foundation).
        - Beide unterstützen JSON, XML und maschinenlesbare Verarbeitung.
    

    ## Vergleichstabelle CycloneDX vs. SPDX
    
        
            
                
                    Kriterium
                    CycloneDX
                    SPDX
                
            
            
                
                    **Herausgeber**
                    OWASP
                    Linux Foundation / ISO/IEC 5962:2021
                
                
                    **Aktuelle Version**
                    CycloneDX 1.6
                    SPDX 3.0
                
                
                    **Primärer Fokus**
                    Security / Schwachstellenmanagement
                    Lizenz-Compliance
                
                
                    **VEX-Unterstützung**
                    Ja (nativ)
                    Ja (ab SPDX 3.0)
                
                
                    **Tool-Unterstützung**
                    Sehr breit (Syft, Trivy, DependencyTrack)
                    Breit
                
                
                    **DependencyTrack-Integration**
                    Nativ unterstützt
                    Unterstützt
                
                
                    **CRA-Eignung**
                    Sehr gut (Security-Fokus)
                    Gut (ISO-Standard)
                
                
                    **BSI TR-03183**
                    Erwähnt als geeignetes Format
                    Erwähnt als geeignetes Format
                
            
        
    

    ## Empfehlung für CRA-Ready Nutzer
    
        - Für Schwachstellenmanagement und Art.14-Meldungen wird CycloneDX empfohlen (nativer VEX-Support, DependencyTrack-Integration).
        - Für Lieferketten mit Lizenz-Compliance-Anforderungen eignet sich SPDX besonders gut.
        - Eine Kombination ist möglich, weil viele Tools beide Formate ausgeben können.
        - 
            **Hinweis:** Diese Empfehlung basiert auf dem Stand Mai 2026.
            Die Kommission kann per Durchführungsrechtsakt Formate verbindlich festlegen.
        
    

    ## Mindestfelder pro Komponente (beide Formate)
    
        - Name der Komponente
        - Version
        - Lieferant / Urheber (Supplier)
        - PURL (Package URL) - empfohlen für eindeutige Identifikation
        - CPE (Common Platform Enumeration) - für CVE-Abgleich
        - Lizenz (SPDX License Expression)
        - Hash / Prüfsumme (SHA-256 empfohlen)
    

    
        Interne Vertiefung:
        [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
    

    ## Offizielle Quellen
    
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
