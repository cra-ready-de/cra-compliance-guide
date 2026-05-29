---
title: "Obowiazki zglaszania CRA wedlug Art.14: terminy 24h, 72h i 14 dni"
description: "Od 11 September 2026 producenci musza zglaszac aktywnie wykorzystywane podatnosci do platformy ENISA w ciagu 24 godzin. Wszystkie terminy i obowiazki..."
lastUpdated: "2026-05-02"
lang: pl
source: cra-ready.de
---

# Obowiazki zglaszania CRA wedlug Art.14: terminy 24h, 72h i 14 dni

## Wprowadzenie: od kiedy obowiazuje obowiazek zgloszenia?
    
        Art.14 CRA obowiazuje od **11 September 2026**
        (21 miesiecy po wejsciu w zycie, Art.71 Abs.2 CRA).
    

    
        To jest **pierwszy wiazacy obowiazek CRA**, jeszcze przed ogolnymi
        wymaganiami bezpieczenstwa (December 2027).
    

    
        Dotyczy wszystkich producentow w obszarze produkty z elementami cyfrowymi
        udostepnianych na rynku UE.
    

    
        Wyjatek: mikroprzedsiebiorstwa i male przedsiebiorstwa sa zwolnione z kar pienieznych za niedotrzymanie
        terminu 24h (Art.64 Abs.10 CRA, Corrigendum 2025/90555 z 2 July 2025).
        **OBOWIAZEK** zgloszenia pozostaje jednak w mocy.
    

    ## Co nalezy zglaszac?
    Dwa wyzwalacze (Art.14 Abs.1 i Abs.3 CRA):

    ### Wyzwalacz 1 - Aktywnie wykorzystywana podatnosc
    
        - 
            Definicja: podatnosc we wlasnym produkcie producenta, o ktorej producent ma wiedze,
            ze jest aktywnie wykorzystywana przez atakujacych (Art.14 Abs.1 CRA).
        
        - 
            Obowiazek zgloszenia: niezwlocznie, nie pozniej niz w ciagu 24 godzin od uzyskania wiedzy
            (Art.14 Abs.2 lit.a CRA).
        
    

    ### Wyzwalacz 2 - Powazny incydent (Severe Incident)
    
        - 
            Definicja: incydent, ktory narusza bezpieczenstwo produktu i moze miec wplyw na
            dostepnosc, poufnosc lub integralnosc (Art.14 Abs.3 CRA).
        
        - 
            Obowiazek zgloszenia: niezwlocznie, nie pozniej niz w ciagu 24 godzin od uzyskania wiedzy
            (Art.14 Abs.4 lit.a CRA).
        
    

    ## Trzy terminy zgloszen w szczegolach
    
    
            
                
                    Termin
                    Zawartosc
                    Podstawa prawna
                
            
            
                
                    **Wstepne zgloszenie 24-godzinne**
Nie pozniej niz 24 godziny od uzyskania wiedzy
                    Pierwsze zgloszenie (Early Warning); pelne informacje nie sa jeszcze wymagane; wskazanie, czy podatnosc lub incydent wskazuje na dzialanie bezprawne lub zlosliwe
                    Art.14 Abs.2 lit.a i Art.14 Abs.4 lit.a CRA
                
                
                    **Zgloszenie uzupelniajace 72-godzinne**
Nie pozniej niz 72 godziny od uzyskania wiedzy
                    Zaktualizowane zgloszenie z dostepnymi informacjami o podatnosci lub incydencie; wstepna ocena zgodności; w razie potrzeby indicators of compromise (IoC)
                    Art.14 Abs.2 lit.b i Art.14 Abs.4 lit.b CRA
                
                
                    **Raport koncowy (14 dni / 1 miesiac)**
Podatnosci: nie pozniej niz 14 dni po dostepnosci aktualizacji bezpieczenstwa lub obejscia; incydenty: nie pozniej niz 1 miesiac po zgloszeniu wstepnym
                    Pelny opis; poziom dotkliwosci; wynik CVSS jesli dostepny; wersje dotkniete; podjete srodki; status aktualizacji bezpieczenstwa
                    Art.14 Abs.2 lit.c i Art.14 Abs.4 lit.c CRA
                
            
        
    

    ## Do kogo trafia zgloszenie?
    
        - Zgloszenie trafia do CSIRT panstwa czlonkowskiego glownego zakladu producenta (Art.14 Abs.1 CRA).
        - W Niemczech: BSI (Bundesamt fuer Sicherheit in der Informationstechnik) jako wlasciwy CSIRT.
        - 
            Kanal techniczny: ENISA Single Reporting Platform.
            Platforma jest prowadzona przez ENISA i automatycznie przekazuje zgloszenia do wlasciwego krajowego CSIRT.
        
        - Status (May 2026): platforma musi byc operacyjna do 11 September 2026 (Art.16 CRA).
    
    
        **WAZNA UWAGA:** Dokladne specyfikacje techniczne i model dostepu do platformy ENISA
        sa okreslane przez Komisje poprzez akt wykonawczy (Art.16 Abs.4 CRA).
        Producenci powinni sledzic komunikaty ENISA i BSI, aby miec aktualne informacje.
    

    ## Skoordynowane ujawnianie
    
        - Po zgloszeniu do CSIRT, ENISA przekazuje zgloszenie do innych dotknietych CSIRT (Art.14 Abs.7 CRA).
        - Ujawnienie publiczne: ENISA publikuje informacje o zgloszonych podatnosciach po uplywie odpowiednich terminow.
        - 
            Dobrowolne ujawnienie (Voluntary Disclosure, Art.14 Abs.8 CRA): producenci moga takze dobrowolnie
            zglaszac podatnosci; jest to uznawane za dobra praktyke i moze byc pozytywnie oceniane przez organy nadzoru.
        
        - 
            security.txt (Art.13 Abs.6 CRA): producenci musza zapewnic kanal kontaktowy dla zgloszen podatnosci od stron trzecich.
            [ /help/schwachstellenmanagement/security-txt](/help/schwachstellenmanagement/security-txt)
        
    

    ## Co producent musi przygotowac wewnetrznie?
    
        - Udokumentowac wewnetrzna procedure vulnerability management (kanal przyjecia, ocena zgodności, eskalacja, lancuch zglaszania)
        - Zapewnic gotowosc 24h: kto zglasza? w jakim jezyku? z jakimi danymi dostepowymi do platformy ENISA?
        - Ustanowic procedure oceny CVSS (dla raportu koncowego)
        - Przechowywanie zgloszen: co najmniej 10 lat (Art.13 Abs.14 CRA)
        - Skonfigurowac i utrzymywac security.txt (Art.13 Abs.6 CRA)
        - Koordynacja z lancuchem dostaw: informowac producentow komponentow
        - Wykorzystywac BSI TR-03183 jako wskazowke przy projektowaniu procesu
    

    ## Sankcje za naruszenia
    
        - 
            Naruszenie obowiazkow zgloszeniowych zgodnie z Art.14: do 10 mln EUR lub 2% swiatowego rocznego obrotu
            (Art.64 Abs.2 CRA - traktowane jako naruszenie innych obowiazkow).
        
        - 
            Wyjatek dla malych i mikroprzedsiebiorstw: brak kar za niedotrzymanie terminu 24h
            (Art.64 Abs.10 CRA zgodnie z Corrigendum 2025/90555). Sam obowiazek zgloszenia pozostaje.
        
        - 
            Egzekwowanie przez krajowe organy nadzoru rynku
            (w Niemczech: BSI zgodnie z Art.35 CRA).
        
    

    
        Powiazane podstawy:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (oznakowanie CE)
    

    ## Oficjalne zrodla
    
        - 
            [
                Art.14 Regulation (EU) 2024/2847 (pelny tekst)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                BSI - Obowiazki zglaszania CRA
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                ENISA - Cyber Resilience Act
            ](https://www.enisa.europa.eu/topics/cyber-resilience-act)
        
        - 
            [
                EC FAQ o CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
