---
title: "Czym jest Cyber Resilience Act (CRA)?"
description: "Wyjaśnienie Cyber Resilience Act (Regulation (EU) 2024/2847): cele, zakres stosowania, objęte produkty oraz to, co producenci muszą wiedzieć już teraz."
lastUpdated: "2026-05-02"
lang: pl
source: cra-ready.de
---

# Czym jest Cyber Resilience Act (CRA)?

## Wprowadzenie: czym jest Cyber Resilience Act?
    
        Cyber Resilience Act (CRA) to **Regulation (EU) 2024/2847** Parlamentu Europejskiego i Rady.
        Regulation obowiązuje od **11 December 2024** i została opublikowana w Dzienniku Urzędowym Unii Europejskiej
        **20 November 2024**.
    

    
        Jako rozporządzenie horyzontalne CRA stosuje się bezpośrednio we wszystkich państwach członkowskich UE; wdrożenie krajowe nie jest wymagane.
        Celem jest jednolite ramy cyberbezpieczeństwa dla produktów z elementami cyfrowymi w całym cyklu życia produktu.
    

    ## Dlaczego wprowadzono CRA?
    
        - Rosnąca liczba cyberataków na produkty połączone (IoT, OT i instalacje przemysłowe).
        - Przed CRA istniały rozproszone ramy prawne z niejednolitymi wymaganiami w UE.
        - CRA uzupełnia dyrektywę NIS-2: NIS-2 koncentruje się na organizacjach, CRA na produktach.
    

    ## Czym są "produkty z elementami cyfrowymi"?
    
        Właściwa definicja znajduje się w **Art.3 Nr.1 CRA**. Obejmuje produkty, których zamierzona
        funkcja zależy w całości lub częściowo od oprogramowania lub przetwarzania danych.
    

    Typowe przykłady:

    
        - Routery przemysłowe
        - Systemy SPS/PLC
        - Oprogramowanie SCADA
        - Bramy IIoT
        - Systemy Linux wbudowane
        - Systemy zarządzania siecią
    
    
        CRA nie obejmuje m.in. obszarów produktów z własnymi regulacjami sektorowymi,
        np. wyrobów medycznych (MDR), pojazdów i produktów lotniczych.
    

    ## Kogo to dotyczy?
    
        Dotyczy to w szczególności producentów (**Art.3 Nr.13**), upoważnionych przedstawicieli (**Art.3 Nr.17**),
        importerów (**Art.3 Nr.18**) i dystrybutorów (**Art.3 Nr.19**).
        Dla open-source software stewards (**Art.3 Nr.14**) obowiązki są ograniczone.
    

    
        Szczegóły dotyczące rozgraniczenia ról:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich)
    

    ## Czego konkretnie wymaga CRA?
    Wymagania można uporządkować w trzech filarach:

    ### a) Wymagania bezpieczeństwa (Annex I Part I)
    
        - Secure-by-design i secure-by-default
        - Minimalna powierzchnia ataku i brak znanych podatności możliwych do wykorzystania przy wprowadzaniu na rynek
        - Szyfrowanie, kontrola dostępu i ochrona integralności
    

    ### b) Obsługa podatności (Annex I Part II + Art.14)
    
        - 
            Okres wsparcia: co najmniej 5 lat LUB oczekiwany czas użytkowania produktu, w zależności od tego, który okres jest dłuższy
            (Art.13 Abs.8 CRA).
        
        - 
            **WAŻNA UWAGA:** Termin "expected use time"
            (expected use time / voraussichtliche Nutzungsdauer) nie jest ostatecznie zdefiniowany w Art.3 CRA.
            Komisja i krajowe organy nadzoru doprecyzują to pojęcie w zależności od kategorii produktu i branży.
            Producenci powinni uzasadnić swoją ocenę oczekiwanego czasu użytkowania w dokumentacji technicznej (Annex VII).
        
        - Zgłaszanie aktywnie wykorzystywanych podatności: 24h / 72h / 14 dni
    
    
        Szczegóły ścieżki zgłoszeniowej:
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ### c) Przejrzystość i dokumentacja
    
        - 
            SBOM:
            [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
        
        - deklaracja zgodności UE (DoC) i oznakowanie CE
        - 
            Oznakowanie CE w skrócie:
            [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
        
        - Dokumentacja techniczna zgodnie z Annex VII
    

    ## Normy zharmonizowane - stan 2026
    
        **WAŻNA UWAGA DLA PRODUCENTÓW:**
        Zgodność techniczna będzie ostatecznie oceniana nie tylko na podstawie tekstu Regulation,
        ale także na podstawie norm zharmonizowanych (Harmonised Standards), które opracowują CEN, CENELEC i ETSI
        na podstawie mandatu normalizacyjnego M/606 (decyzja Komisji C(2025)618 z dnia **3 February 2025**).
    

    Aktualny stan (May 2026):

    
        - Horyzontalne normy typu A i typu B (obsługa podatności): plan ukończenia August 2026
        - Wertykalne normy typu C (specyficzne dla kategorii produktów): plan ukończenia October 2026
        - Pierwsza publikacja w Dzienniku Urzędowym UE: przewidywana Q2 2027
    
    
        Do czasu publikacji norm zharmonizowanych producenci mogą stosować istniejące normy
        (np. IEC 62443, ETSI EN 303 645), bez uzyskania domniemania zgodności z CRA.
        BSI TR-03183 już teraz zapewnia praktyczne wskazówki.
    

    ## Klasyfikacja produktów w skrócie
    
        
            
                
                    Kategoria
                    Krótki opis
                    Ścieżka oceny zgodności
                
            
            
                
                    Default
                    Niewymienione w Annex III/IV
                    Kontrola wewnętrzna / samoocena
                
                
                    Klasa I
                    Ważne kategorie produktów zgodnie z CRA
                    W zależności od norm zharmonizowanych / możliwa ocena strony trzeciej
                
                
                    Klasa II
                    Wyższa krytyczność i ryzyko
                    Z reguły bardziej rygorystyczna ocena zgodności
                
                
                    Krytyczne
                    Produkty o szczególnym znaczeniu dla bezpieczeństwa
                    Ścieżka certyfikacyjna / jednostka notyfikowana
                
            
        
    
    
        Szczegóły klasyfikacji:
        [ /help/cra-grundlagen/produktklassifizierung](/help/cra-grundlagen/produktklassifizierung)
    

    
        Uwaga: Implementing Regulation (EU) 2025/2392 (**28 November 2025**) zawiera oficjalne opisy techniczne
        wszystkich 28 kategorii produktów.
    

    ## Sankcje
    
        - 
            Do 15 mln EUR lub 2,5% światowego rocznego obrotu
            (za naruszenia obowiązków producenta, Art.64 Abs.1 CRA)
        
        - 
            Do 10 mln EUR lub 2% dla pozostałych podmiotów gospodarczych (Art.64 Abs.2 CRA)
        
        - 
            Corrigendum 2025/90555 (**2 July 2025**): Art.64 Abs.10 - mikroprzedsiębiorstwa i małe przedsiębiorstwa są zwolnione z kar
            za niedotrzymanie terminów w ramach obowiązku zgłoszenia 24h
        
    
    
        **WAŻNA UWAGA:** Wskazane kwoty są MAKSYMALNYMI LIMITAMI określonymi w Art.64 CRA
        dla całej UE. Faktyczne ustalanie i egzekwowanie kar pieniężnych należy do krajowych
        organów nadzoru rynku (w Niemczech: BSI jako właściwy organ zgodnie z CRA Art.35).
        Procedury i praktyka mogą różnić się między państwami członkowskimi.
    

    ## Oficjalne źródła
    
        - 
            [
                Regulation (EU) 2024/2847 w EUR-Lex (pełny tekst)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                EC Digital Strategy - przegląd CRA
            ](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
        
        - 
            [
                BSI - Cyber Resilience Act
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                FAQ Komisji dotyczące CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (kategorie produktów)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
