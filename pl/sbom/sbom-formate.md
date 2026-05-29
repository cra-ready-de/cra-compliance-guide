---
title: "Formaty SBOM: CycloneDX vs. SPDX - ktory format dla CRA?"
description: "Porownanie formatow SBOM CycloneDX i SPDX w kontekscie wymagan CRA (Regulation EU 2024/2847). Zalety i wady dla producentow przemyslowych."
lastUpdated: "2026-05-02"
lang: pl
source: cra-ready.de
---

# Formaty SBOM: CycloneDX vs. SPDX - ktory format dla CRA?

## Dlaczego format jest wazny?
    
        - CRA nie narzuca formatu, ale kompatybilnosc toolchain i interoperacyjnosc z organami beda kluczowe.
        - Dwa dominujace standardy: CycloneDX (OWASP) i SPDX (Linux Foundation).
        - Oba wspieraja JSON, XML i przetwarzanie machine-readable.
    

    ## Tabela porownawcza CycloneDX vs. SPDX
    
        
            
                
                    Kryterium
                    CycloneDX
                    SPDX
                
            
            
                
                    **Wydawca**
                    OWASP
                    Linux Foundation / ISO/IEC 5962:2021
                
                
                    **Aktualna wersja**
                    CycloneDX 1.6
                    SPDX 3.0
                
                
                    **Glowny fokus**
                    Security / vulnerability management
                    Zgodnosc licencyjna
                
                
                    **Wsparcie VEX**
                    Tak (natywnie)
                    Tak (od SPDX 3.0)
                
                
                    **Wsparcie narzedzi**
                    Bardzo szerokie (Syft, Trivy, DependencyTrack)
                    Szerokie
                
                
                    **Integracja z DependencyTrack**
                    Wspierana natywnie
                    Wspierana
                
                
                    **Przydatnosc dla CRA**
                    Bardzo dobra (focus security)
                    Dobra (standard ISO)
                
                
                    **BSI TR-03183**
                    Wymieniony jako odpowiedni format
                    Wymieniony jako odpowiedni format
                
            
        
    

    ## Rekomendacja dla uzytkownikow CRA-Ready
    
        - Dla vulnerability management i zgloszen Art.14 rekomendowany jest CycloneDX (natywne wsparcie VEX, integracja z DependencyTrack).
        - Dla supply chain z wymaganiami zgodnosci licencyjnej dobrze sprawdza sie SPDX.
        - Mozliwe jest laczenie obu, poniewaz wiele narzedzi potrafi generowac oba formaty.
        - 
            **Uwaga:** Ta rekomendacja odzwierciedla stan na May 2026.
            Komisja moze okreslic obowiazkowe formaty przez akt wykonawczy.
        
    

    ## Minimalne pola dla komponentu (oba formaty)
    
        - Nazwa komponentu
        - Version
        - Dostawca / autor
        - PURL (Package URL) - zalecany do jednoznacznej identyfikacji
        - CPE (Common Platform Enumeration) - do dopasowania CVE
        - Licencja (SPDX License Expression)
        - Hash / checksum (zalecany SHA-256)
    

    
        Powiazanie wewnetrzne:
        [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
    

    ## Oficjalne zrodla
    
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
