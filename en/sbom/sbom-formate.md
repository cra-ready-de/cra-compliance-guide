---
title: "SBOM Formats: CycloneDX vs. SPDX – Which Format for the CRA?"
description: "Comparison of SBOM formats CycloneDX and SPDX in the context of CRA requirements (Regulation EU 2024/2847). Pros and cons for industrial manufacturers."
lastUpdated: "2026-05-02"
lang: en
source: cra-ready.de
---

# SBOM Formats: CycloneDX vs. SPDX – Which Format for the CRA?

## Why is the format important?
    
        - The CRA does not prescribe a format, but toolchain compatibility and interoperability with authorities will be critical.
        - Two dominant standards are CycloneDX (OWASP) and SPDX (Linux Foundation).
        - Both support JSON, XML and machine-readable processing.
    

    ## Comparison table: CycloneDX vs. SPDX
    
        
            
                
                    Criterion
                    CycloneDX
                    SPDX
                
            
            
                
                    **Publisher**
                    OWASP
                    Linux Foundation / ISO/IEC 5962:2021
                
                
                    **Current version**
                    CycloneDX 1.6
                    SPDX 3.0
                
                
                    **Primary focus**
                    Security / vulnerability management
                    License compliance
                
                
                    **VEX support**
                    Yes (native)
                    Yes (from SPDX 3.0)
                
                
                    **Tool support**
                    Very broad (Syft, Trivy, DependencyTrack)
                    Broad
                
                
                    **DependencyTrack integration**
                    Natively supported
                    Supported
                
                
                    **CRA suitability**
                    Very good (security focus)
                    Good (ISO standard)
                
                
                    **BSI TR-03183**
                    Mentioned as suitable format
                    Mentioned as suitable format
                
            
        
    

    ## Recommendation for CRA-Ready users
    
        - For vulnerability management and Art.14 reports, CycloneDX is recommended (native VEX support, DependencyTrack integration).
        - For supply chains with license-compliance requirements, SPDX is a strong option.
        - A combination is possible because many tools can output both formats.
        - 
            **Note:** This recommendation reflects the current status (May 2026).
            The Commission may set mandatory formats by implementing act.
        
    

    ## Minimum fields per component (both formats)
    
        - Component name
        - Version
        - Supplier / author
        - PURL (Package URL) - recommended for unique identification
        - CPE (Common Platform Enumeration) - for CVE matching
        - License (SPDX License Expression)
        - Hash / checksum (SHA-256 recommended)
    

    
        Internal deep link:
        [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
    

    ## Official Sources
    
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
