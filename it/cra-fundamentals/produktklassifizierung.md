---
title: "Classificazione dei prodotti CRA: Default, Classe I, Classe II e Critico"
description: "Come classificare il tuo prodotto secondo Regulation (EU) 2024/2847? Default, Importante Classe I/II o Critico, con descrizioni ufficiali da..."
lastUpdated: "2026-05-02"
lang: it
source: cra-ready.de
---

# Classificazione dei prodotti CRA: Default, Classe I, Classe II e Critico

## Introduzione: perche la classificazione e decisiva?
    
        La classe di prodotto determina la procedura di valutazione della conformità e quindi lo sforzo e il costo della
        conformita CRA per i prodotti con elementi digitali.
    

    
        La base giuridica e **CRA Annex III** (prodotti importanti) e **CRA Annex IV**
        (prodotti critici).
    

    
        L ulteriore specificazione e fornita da **Implementing Regulation (EU) 2025/2392** del
        **28 November 2025** (pubblicato nella Gazzetta ufficiale dell UE il **1 December 2025**).
        Questa regulation fornisce descrizioni tecniche ufficiali per tutte le 28 categorie di prodotti in Annex III e IV,
        eliminando l incertezza interpretativa esistente fino a quel momento.
    

    
        **IMPORTANTE:** Il criterio decisivo e la **FUNZIONE PRINCIPALE** del prodotto,
        non il suo nome, la denominazione marketing o funzioni secondarie
        (EC FAQ Dec 2025, sections 3.2 and 3.4; Implementing Regulation (EU) 2025/2392, recitals 3-5).
    

    ## Il modello a quattro livelli
    
        
            
                
                    Livello
                    Base giuridica
                    Esempi (rilevanti per l industria)
                    Valutazione della conformità
                
            
            
                
                    **Standard (Default)**
                    Tutti i prodotti NON elencati in Annex III o IV (~90% di tutti i prodotti)
                    Sistemi embedded semplici senza funzione di rete, HMI industriale offline, unita di controllo non connesse
                    Autovalutazione (Modulo A, Art.32 para.1 CRA)
                
                
                    **Importante Classe I**
                    CRA Annex III Classe I + Implementing Regulation (EU) 2025/2392 Annex I Part 1
                    Gestori di password, sistemi di gestione di rete, software di monitoraggio di rete, sistemi operativi di uso generale, router e modem domestici, switch
                    Autovalutazione SOLO con applicazione di norme armonizzate (Art.32 para.2 CRA); altrimenti organismo notificato richiesto
                
                
                    **Importante Classe II**
                    CRA Annex III Classe II + Implementing Regulation (EU) 2025/2392 Annex I Part 2
                    Hypervisor, firewall, sistemi di intrusion detection/prevention, sistemi industriali di automazione e controllo (IACS) solo quando utilizzati da entita soggette a NIS-2, microprocessori resistenti alla manomissione
                    Organismo notificato OBBLIGATORIO (Art.32 para.3 CRA) O certificazione europea di cybersicurezza (Art.32 para.4)
                
                
                    **Critico**
                    CRA Annex IV + Implementing Regulation (EU) 2025/2392 Annex II
                    Hardware security modules (HSM), IC per smart card, smart card e dispositivi simili, dispositivi per finalita di sicurezza avanzata (es. hardware token certificati)
                    Organismo notificato OBBLIGATORIO o certificazione europea di cybersicurezza (Art.33 and 34 CRA)
                
            
        
    

    ## Il test della funzione principale
    
        **NOTA INTERPRETATIVA IMPORTANTE:** Un prodotto e classificato in base alla sua FUNZIONE PRINCIPALE,
        non in base ai componenti integrati.
    

    Esempi dalle EC FAQ (Dec 2025):

    
        - Uno smartphone con gestore password integrato rimane nella categoria standard, perche la sua funzione principale non e la gestione delle password.
        - Un app con browser incorporato non e un prodotto "browser", perche la funzione principale non e la navigazione.
        - Un sistema di automazione industriale e Classe II SOLO quando l operatore rientra in NIS-2 (Implementing Regulation (EU) 2025/2392).
    
    
        Nota: i confini esatti per prodotti multifunzione possono essere complessi nei singoli casi.
        La Commissione ha annunciato ulteriori linee guida.
    

    ## Panoramica delle procedure di valutazione della conformità
    
        - 
            **Modulo A (autovalutazione):** Il fabbricante prepara la documentazione tecnica e rilascia la
            dichiarazione di conformità UE. Sufficiente per Default e Classe I con norme armonizzate.
        
        - 
            **Organismo notificato:** Una terza parte indipendente esegue la valutazione della conformità.
            Richiesto per Classe I senza norme armonizzate, Classe II e Critico.
        
        - 
            **Stato degli organismi notificati (May 2026):** Gli Stati membri dovevano pubblicare procedure di valutazione e
            designazione degli organismi di valutazione della conformita entro 11 June 2026 (Art.35 CRA).
            Gli Stati membri devono garantire un numero sufficiente di organismi notificati entro 11 December 2026 (Art.35 para.2 CRA).
        
    
    
        Dettagli della procedura:
        [ /help/konformitaet/konformitaetsbewertung](/help/konformitaet/konformitaetsbewertung)
    

    ## Famiglie di prodotti
    
        I fabbricanti con piu di un prodotto non devono avviare un progetto di conformita separato per ogni prodotto.
        I prodotti con caratteristiche simili possono essere raggruppati in famiglie di prodotti.
    

    Dimensioni rilevanti (dalle linee guida della Commissione):

    
        - Stessa destinazione d uso e uso prevedibile
        - Asset simili (chiavi crittografiche, funzioni di rete)
        - Stessi profili di minaccia
        - Componenti software condivisi / sovrapposizioni SBOM
    

    
        Fondamenti correlati:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (marcatura CE),
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Fonti ufficiali
    
        - 
            [
                Regulation (EU) 2024/2847, Annex III and IV
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (categorie ufficiali di prodotti)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
        
        - 
            [
                BSI CRA Flyer #2 - Classificazione dei prodotti
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                EC CRA FAQ (Dec 2025), sections 3.1-3.4
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
