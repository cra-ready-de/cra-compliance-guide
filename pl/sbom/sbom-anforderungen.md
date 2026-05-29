---
title: "Wymagania SBOM wedlug CRA: Software Bill of Materials zgodnie z Annex I"
description: "CRA (Regulation EU 2024/2847) zobowiazuje producentow do stworzenia SBOM. Co musi zawierac? Jakie formaty sa odpowiednie?"
lastUpdated: "2026-05-02"
lang: pl
source: cra-ready.de
---

# Wymagania SBOM wedlug CRA: Software Bill of Materials zgodnie z Annex I

## Czym jest SBOM i dlaczego CRA tego wymaga?
    
        - SBOM = Software Bill of Materials: maszynowo czytelna lista wszystkich komponentow oprogramowania w produkcie, lacznie z zaleznosciami.
        - Wymog CRA: Annex I Part II No.1. Producenci musza umiec identyfikowac i usuwac podatnosci w komponentach.
        - SBOM jest podstawa dla vulnerability management, bezpieczenstwa lancucha dostaw i dokumentacji technicznej (Annex VII CRA).
        - Obowiazuje od: 11 December 2027.
    

    ## Obowiazkowa zawartosc SBOM wedlug CRA Annex I
    Minimalne wymagania (z Annex I Part II No.1 CRA):

    
        - Wszystkie komponenty top-level produktu
        - Zaleznosci tranzytywne (komponenty komponentow), o ile sa istotne dla identyfikacji podatnosci
        - Dla kazdego komponentu: nazwa, wersja, dostawca/autor
        - Jednoznaczne identyfikatory (np. CPE, PURL)
        - Informacje o licencjach (dla komponentow open source)
    
    
        **Uwaga:** CRA nie definiuje obowiazkowego standardu SBOM.
        Komisja moze okreslic formaty przez akt wykonawczy.
        Do tego czasu CycloneDX i SPDX sa standardami de-facto.
        Porownanie formatow:
        [ /help/sbom/sbom-formate](/help/sbom/sbom-formate)
    

    ## SBOM w cyklu zycia - obowiazek aktualizacji
    
        - SBOM musi byc aktualizowany przy kazdej aktualizacji produktu (Art.13 Abs.5 CRA).
        - Przy aktualizacjach bezpieczenstwa aktualizacja SBOM powinna byc publikowana jednoczesnie.
        - Przechowywanie: jako czesc dokumentacji technicznej przez 10 lat.
        - Zalecana jest automatyzacja: generowanie SBOM w pipeline CI/CD.
    

    ## SBOM i zarzadzanie podatnosciami
    
        - SBOM umozliwia szybka identyfikacje dotknietych wersji, gdy pojawiaja sie nowe podatnosci (dopasowanie CVE).
        - Powiazanie z Art.14 CRA: dane SBOM przyspieszaja pierwsze zgloszenie w 24h, bo dotkniete komponenty sa od razu identyfikowalne.
        - VEX (Vulnerability Exploitability eXchange) to uzupelniajacy format dla oswiadczen o exploitability.
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Udostepnianie SBOM
    
        - Organom: na zadanie organu nadzoru rynku (Art.13 Abs.12 CRA).
        - Klientom/uzytkownikom: CRA nie wymaga automatycznej dystrybucji, ale wymaga przejrzystosci wobec uzytkownikow (Art.13 Abs.18 CRA).
        - **Uwaga:** Poufnosc handlowa moze uzasadniac ograniczenia publicznego ujawniania SBOM.
    

    ## Oficjalne zrodla
    
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
                https://ntia.gov/sbom (Zasoby SBOM NTIA)
            ](https://ntia.gov/sbom)
        
        - 
            [
                https://cyclonedx.org (Standard CycloneDX)
            ](https://cyclonedx.org)
        
        - 
            [
                https://spdx.dev (Standard SPDX)
            ](https://spdx.dev)
