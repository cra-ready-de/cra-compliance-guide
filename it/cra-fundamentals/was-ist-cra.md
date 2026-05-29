---
title: "Che cos\"
description: "Spiegazione del Cyber Resilience Act (Regulation (EU) 2024/2847): obiettivi, ambito di applicazione, prodotti interessati e cosa i fabbricanti devono..."
lastUpdated: "2026-05-02"
lang: it
source: cra-ready.de
---

# Che cos\

## Introduzione: che cos'è il Cyber Resilience Act?
    
        Il Cyber Resilience Act (CRA) è la **Regulation (EU) 2024/2847** del Parlamento europeo e del Consiglio.
        La Regulation è in vigore dal **11 December 2024** ed è stata pubblicata nella Gazzetta ufficiale dell'Unione europea
        il **20 November 2024**.
    

    
        In quanto regolamento orizzontale, il CRA si applica direttamente in tutti gli Stati membri dell'UE; non è richiesto recepimento nazionale.
        L'obiettivo è creare un quadro uniforme di cybersicurezza per i prodotti con elementi digitali lungo l'intero ciclo di vita del prodotto.
    

    ## Perché è stato introdotto il CRA?
    
        - Aumento degli attacchi informatici contro prodotti connessi (IoT, OT e impianti industriali).
        - Prima del CRA esisteva un quadro normativo frammentato con requisiti non uniformi nell'UE.
        - Il CRA integra la direttiva NIS-2: la NIS-2 si concentra sulle organizzazioni, il CRA sui prodotti.
    

    ## Che cos'è un "prodotto con elementi digitali"?
    
        La definizione rilevante si trova nell'**Art.3 Nr.1 CRA**. Rientrano i prodotti la cui funzione prevista
        dipende totalmente o parzialmente da software o trattamento dei dati.
    

    Esempi tipici:

    
        - Router industriali
        - Sistemi SPS/PLC
        - Software SCADA
        - Gateway IIoT
        - Sistemi Linux embedded
        - Sistemi di gestione della rete
    
    
        Non rientrano nel CRA, tra l'altro, i settori di prodotto con regolamentazione settoriale propria,
        ad esempio i dispositivi medici (MDR), i veicoli e i prodotti aeronautici.
    

    ## Chi è interessato?
    
        Sono interessati in particolare i fabbricanti (**Art.3 Nr.13**), i mandatari (**Art.3 Nr.17**),
        gli importatori (**Art.3 Nr.18**) e i distributori (**Art.3 Nr.19**).
        Per gli open-source software stewards (**Art.3 Nr.14**) valgono obblighi limitati.
    

    
        Dettagli sulla distinzione dei ruoli:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich)
    

    ## Cosa richiede concretamente il CRA?
    I requisiti possono essere strutturati in tre pilastri:

    ### a) Requisiti di sicurezza (Annex I Part I)
    
        - Secure-by-design e secure-by-default
        - Superficie di attacco minima e assenza di vulnerabilità note sfruttabili all'immissione sul mercato
        - Crittografia, controllo degli accessi e protezione dell'integrità
    

    ### b) Gestione delle vulnerabilità (Annex I Part II + Art.14)
    
        - 
            Periodo di supporto: almeno 5 anni OPPURE la durata d'uso prevista del prodotto, a seconda di quale periodo sia più lungo
            (Art.13 Abs.8 CRA).
        
        - 
            **NOTA IMPORTANTE:** Il termine "expected use time"
            (expected use time / voraussichtliche Nutzungsdauer) non è definito in modo esaustivo nell'Art.3 CRA.
            La Commissione e le autorità nazionali di vigilanza specificheranno ulteriormente questo concetto per categoria di prodotto e settore.
            I fabbricanti dovrebbero motivare la loro stima della durata d'uso prevista nella documentazione tecnica (Annex VII).
        
        - Segnalazione delle vulnerabilità attivamente sfruttate: 24h / 72h / 14 giorni
    
    
        Dettagli sulla catena di segnalazione:
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ### c) Trasparenza e documentazione
    
        - 
            SBOM:
            [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
        
        - dichiarazione di conformità UE (DoC) e marcatura CE
        - 
            Panoramica della marcatura CE:
            [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
        
        - Documentazione tecnica secondo Annex VII
    

    ## Norme armonizzate - stato 2026
    
        **NOTA IMPORTANTE PER I FABBRICANTI:**
        La conformità tecnica sarà valutata in definitiva non solo rispetto al testo della Regulation,
        ma anche rispetto alle norme armonizzate (Harmonised Standards) elaborate da CEN, CENELEC ed ETSI
        sulla base del mandato di normazione M/606 (Decisione della Commissione C(2025)618 del **3 February 2025**).
    

    Stato attuale (May 2026):

    
        - Norme orizzontali di tipo A e tipo B (gestione delle vulnerabilità): obiettivo di completamento August 2026
        - Norme verticali di tipo C (specifiche per categoria di prodotto): obiettivo di completamento October 2026
        - Prima pubblicazione nella Gazzetta ufficiale dell'UE: presumibilmente Q2 2027
    
    
        Fino alla pubblicazione delle norme armonizzate, i fabbricanti possono fare riferimento a norme esistenti
        (ad es. IEC 62443, ETSI EN 303 645), senza ottenere però la presunzione di conformità CRA.
        BSI TR-03183 offre già ora un orientamento pratico.
    

    ## Classificazione dei prodotti in sintesi
    
        
            
                
                    Categoria
                    Descrizione breve
                    Percorso di valutazione della conformità
                
            
            
                
                    Default
                    Non elencato in Annex III/IV
                    Controllo interno / autovalutazione
                
                
                    Classe I
                    Categorie di prodotti importanti secondo il CRA
                    In base alle norme armonizzate / possibile valutazione di terza parte
                
                
                    Classe II
                    Maggiore criticità e rischio
                    Di norma valutazione della conformità più rigorosa
                
                
                    Critico
                    Prodotti con particolare rilevanza per la sicurezza
                    Percorso orientato alla certificazione / organismo notificato
                
            
        
    
    
        Dettagli sulla classificazione:
        [ /help/cra-grundlagen/produktklassifizierung](/help/cra-grundlagen/produktklassifizierung)
    

    
        Nota: Implementing Regulation (EU) 2025/2392 (**28 November 2025**) fornisce descrizioni tecniche ufficiali
        per tutte le 28 categorie di prodotti.
    

    ## Sanzioni
    
        - 
            Fino a 15 milioni di EUR o al 2,5% del fatturato annuo mondiale
            (per violazioni degli obblighi dei fabbricanti, Art.64 Abs.1 CRA)
        
        - 
            Fino a 10 milioni di EUR o al 2% per gli altri operatori economici (Art.64 Abs.2 CRA)
        
        - 
            Corrigendum 2025/90555 (**2 July 2025**): Art.64 Abs.10 - microimprese e piccole imprese sono esentate dalle sanzioni
            per il mancato rispetto dei termini dell'obbligo di segnalazione entro 24h
        
    
    
        **NOTA IMPORTANTE:** Gli importi indicati sono i LIMITI MASSIMI previsti dall'Art.64 CRA
        per l'intera UE. La determinazione e l'esecuzione effettive delle sanzioni spettano alle autorità nazionali
        di sorveglianza del mercato (in Germania: BSI quale autorità competente ai sensi dell'Art.35 CRA).
        Procedure e prassi possono variare tra gli Stati membri.
    

    ## Fonti ufficiali
    
        - 
            [
                Regulation (EU) 2024/2847 in EUR-Lex (testo completo)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                EC Digital Strategy - panoramica CRA
            ](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
        
        - 
            [
                BSI - Cyber Resilience Act
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                FAQ della Commissione sul CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (categorie di prodotti)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
