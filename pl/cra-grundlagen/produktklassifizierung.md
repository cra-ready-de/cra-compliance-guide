---
title: "Klasyfikacja produktow CRA: Default, Klasa I, Klasa II i Krytyczne"
description: "Jak sklasyfikowac produkt zgodnie z Regulation (EU) 2024/2847? Default, Ważne Klasa I/II lub Krytyczne, z oficjalnymi opisami z Implementing Regulation..."
lastUpdated: "2026-05-02"
lang: pl
source: cra-ready.de
---

# Klasyfikacja produktow CRA: Default, Klasa I, Klasa II i Krytyczne

## Wprowadzenie: dlaczego klasyfikacja jest kluczowa?
    
        Klasa produktu okresla procedure ocena zgodności, a tym samym naklad pracy i koszty
        zgodnosci z CRA dla kategorii "produkty z elementami cyfrowymi".
    

    
        Podstawa prawna to **CRA Annex III** (produkty wazne) oraz **CRA Annex IV**
        (produkty krytyczne).
    

    
        Dalsze doprecyzowanie zapewnia **Implementing Regulation (EU) 2025/2392** z dnia
        **28 November 2025** (opublikowane w Dzienniku Urzedowym UE dnia **1 December 2025**).
        To regulation dostarcza oficjalne opisy techniczne dla wszystkich 28 kategorii produktow z Annex III i IV,
        usuwajac wczesniejsza niepewnosc interpretacyjna.
    

    
        **WAZNE:** Decydujacym kryterium jest **GLOWNA FUNKCJA** produktu,
        a nie jego nazwa, nazwa marketingowa lub funkcje poboczne
        (EC FAQ Dec 2025, sections 3.2 and 3.4; Implementing Regulation (EU) 2025/2392, recitals 3-5).
    

    ## Model czteropoziomowy
    
        
            
                
                    Poziom
                    Podstawa prawna
                    Przyklady (istotne dla przemyslu)
                    Ocena zgodności
                
            
            
                
                    **Standard (Default)**
                    Wszystkie produkty NIEUJETE w Annex III lub IV (~90% wszystkich produktow)
                    Proste systemy wbudowane bez funkcji sieciowej, offline przemyslowe HMI, niepodlaczone jednostki sterujace
                    Samoocena (Modul A, Art.32 para.1 CRA)
                
                
                    **Wazne Klasa I**
                    CRA Annex III Klasa I + Implementing Regulation (EU) 2025/2392 Annex I Part 1
                    Menedzery hasel, systemy zarzadzania siecia, oprogramowanie monitoringu sieci, systemy operacyjne ogolnego przeznaczenia, routery i modemy domowe, przelaczniki
                    Samoocena TYLKO przy zastosowaniu norm zharmonizowanych (Art.32 para.2 CRA); w przeciwnym razie wymagana jednostka notyfikowana
                
                
                    **Wazne Klasa II**
                    CRA Annex III Klasa II + Implementing Regulation (EU) 2025/2392 Annex I Part 2
                    Hiperwizory, firewalle, systemy intrusion detection/prevention, przemyslowe systemy automatyki i sterowania (IACS) tylko przy uzyciu przez podmioty objete NIS-2, mikroprocesory odporne na manipulacje
                    Jednostka notyfikowana OBOWIAZKOWA (Art.32 para.3 CRA) LUB europejska certyfikacja cyberbezpieczenstwa (Art.32 para.4)
                
                
                    **Krytyczne**
                    CRA Annex IV + Implementing Regulation (EU) 2025/2392 Annex II
                    Moduly bezpieczenstwa sprzetowego (HSM), uklady scalone smart-card, karty inteligentne i podobne urzadzenia, urzadzenia do zaawansowanych celow bezpieczenstwa (np. certyfikowane tokeny sprzetowe)
                    Jednostka notyfikowana OBOWIAZKOWA lub europejska certyfikacja cyberbezpieczenstwa (Art.33 and 34 CRA)
                
            
        
    

    ## Test glownej funkcji
    
        **WAZNA UWAGA INTERPRETACYJNA:** Produkt klasyfikuje sie wedlug GLOWNEJ FUNKCJI,
        a nie wedlug zintegrowanych komponentow.
    

    Przyklady z EC FAQ (Dec 2025):

    
        - Smartfon z wbudowanym menedzerem hasel pozostaje w kategorii standardowej, poniewaz jego glowna funkcja nie jest zarzadzanie haslami.
        - Aplikacja z osadzona przegladarka nie jest produktem typu "browser", poniewaz jej glowna funkcja nie jest przegladanie stron.
        - Przemyslowy system automatyki jest Klasa II TYLKO, gdy operator podlega NIS-2 (Implementing Regulation (EU) 2025/2392).
    
    
        Uwaga: dokladne granice dla produktow wielofunkcyjnych moga byc zlozone w indywidualnych przypadkach.
        Komisja zapowiedziala dalsze wytyczne.
    

    ## Przeglad procedur ocena zgodności
    
        - 
            **Modul A (samoocena):** Producent przygotowuje dokumentacje techniczna i wystawia
            deklaracja zgodności UE. Wystarczajace dla Default i Klasy I przy zastosowaniu norm zharmonizowanych.
        
        - 
            **Jednostka notyfikowana:** Niezalezna strona trzecia przeprowadza ocena zgodności.
            Wymagana dla Klasy I bez norm zharmonizowanych, Klasy II i Krytyczne.
        
        - 
            **Status jednostek notyfikowanych (May 2026):** Panstwa czlonkowskie musialy opublikowac procedury oceny oraz
            wyznaczania jednostek ocena zgodności do 11 June 2026 (Art.35 CRA).
            Panstwa czlonkowskie powinny zapewnic wystarczajaca liczbe jednostek notyfikowanych do 11 December 2026 (Art.35 para.2 CRA).
        
    
    
        Szczegoly procedury:
        [ /help/konformitaet/konformitaetsbewertung](/help/konformitaet/konformitaetsbewertung)
    

    ## Rodziny produktow
    
        Producenci posiadajacy wiecej niz jeden produkt nie musza prowadzic oddzielnego projektu zgodnosci dla kazdego produktu.
        Produkty o podobnych cechach mozna laczyc w rodziny produktow.
    

    Istotne wymiary (zgodnie z wytycznymi Komisji):

    
        - Ten sam cel przeznaczenia i przewidywalny sposob uzycia
        - Podobne zasoby (klucze kryptograficzne, funkcje sieciowe)
        - Te same profile zagrozen
        - Wspoldzielone komponenty oprogramowania / nakladanie sie SBOM
    

    
        Powiazane podstawy:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (oznakowanie CE),
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Oficjalne zrodla
    
        - 
            [
                Regulation (EU) 2024/2847, Annex III and IV
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (oficjalne kategorie produktow)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
        
        - 
            [
                BSI CRA Flyer #2 - Klasyfikacja produktow
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                EC CRA FAQ (Dec 2025), sections 3.1-3.4
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
