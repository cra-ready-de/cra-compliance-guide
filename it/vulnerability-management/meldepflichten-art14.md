---
title: "Obblighi di notifica CRA secondo Art.14: scadenze di 24h, 72h e 14 giorni"
description: "Dal 11 September 2026 i fabbricanti devono notificare vulnerabilita attivamente sfruttate alla piattaforma ENISA entro 24 ore. Tutte le scadenze e gli..."
lastUpdated: "2026-05-02"
lang: it
source: cra-ready.de
---

# Obblighi di notifica CRA secondo Art.14: scadenze di 24h, 72h e 14 giorni

## Introduzione: da quando si applica l obbligo di notifica?
    
        Art.14 CRA si applica dal **11 September 2026**
        (21 mesi dopo l entrata in vigore, Art.71 Abs.2 CRA).
    

    
        Questo e il **primo obbligo CRA vincolante**, anche prima dei requisiti
        generali di sicurezza (December 2027).
    

    
        Riguarda tutti i fabbricanti di prodotti con elementi digitali
        messi a disposizione sul mercato UE.
    

    
        Eccezione: microimprese e piccole imprese sono esentate dalle sanzioni per mancato rispetto
        del termine di 24h (Art.64 Abs.10 CRA, Corrigendum 2025/90555 del 2 July 2025).
        L **OBBLIGO** di notifica rimane comunque.
    

    ## Cosa deve essere notificato?
    Due trigger (Art.14 Abs.1 e Abs.3 CRA):

    ### Trigger 1 - Vulnerabilita attivamente sfruttata
    
        - 
            Definizione: una vulnerabilita nel prodotto del fabbricante di cui il fabbricante ha conoscenza,
            e che viene attivamente sfruttata da attaccanti (Art.14 Abs.1 CRA).
        
        - 
            Obbligo di notifica: immediatamente, al piu tardi entro 24 ore dalla conoscenza
            (Art.14 Abs.2 lit.a CRA).
        
    

    ### Trigger 2 - Incidente grave (Severe Incident)
    
        - 
            Definizione: un incidente che compromette la sicurezza del prodotto e puo avere impatto su
            disponibilita, riservatezza o integrita (Art.14 Abs.3 CRA).
        
        - 
            Obbligo di notifica: immediatamente, al piu tardi entro 24 ore dalla conoscenza
            (Art.14 Abs.4 lit.a CRA).
        
    

    ## Le tre scadenze di notifica in dettaglio
    
    
            
                
                    Scadenza
                    Contenuto
                    Base giuridica
                
            
            
                
                    **Notifica iniziale 24 ore**
Al piu tardi 24 ore dopo la conoscenza
                    Prima notifica (Early Warning); non sono ancora richieste informazioni complete; indicazione se vulnerabilita o incidente suggeriscono un azione illecita o malevola
                    Art.14 Abs.2 lit.a e Art.14 Abs.4 lit.a CRA
                
                
                    **Notifica di follow-up 72 ore**
Al piu tardi 72 ore dopo la conoscenza
                    Notifica aggiornata con informazioni disponibili su vulnerabilita o incidente; prima valutazione della conformità; ove applicabile indicators of compromise (IoC)
                    Art.14 Abs.2 lit.b e Art.14 Abs.4 lit.b CRA
                
                
                    **Rapporto finale (14 giorni / 1 mese)**
Vulnerabilita: al piu tardi 14 giorni dopo disponibilita di aggiornamento di sicurezza o workaround; incidenti: al piu tardi 1 mese dopo la prima notifica
                    Descrizione completa; gravita; punteggio CVSS se disponibile; versioni interessate; misure adottate; stato dell aggiornamento di sicurezza
                    Art.14 Abs.2 lit.c e Art.14 Abs.4 lit.c CRA
                
            
        
    

    ## A chi viene notificato?
    
        - La notifica avviene al CSIRT dello Stato membro della sede principale del fabbricante (Art.14 Abs.1 CRA).
        - In Germania: BSI (Bundesamt fuer Sicherheit in der Informationstechnik) quale CSIRT competente.
        - 
            Canale tecnico: ENISA Single Reporting Platform.
            La piattaforma e gestita da ENISA e inoltra automaticamente le notifiche al CSIRT nazionale competente.
        
        - Stato (May 2026): la piattaforma deve essere operativa entro 11 September 2026 (Art.16 CRA).
    
    
        **NOTA IMPORTANTE:** le specifiche tecniche dettagliate e l accesso alla piattaforma ENISA
        sono definiti dalla Commissione tramite atto di esecuzione (Art.16 Abs.4 CRA).
        I fabbricanti dovrebbero monitorare ENISA e gli annunci BSI per informazioni aggiornate.
    

    ## Divulgazione coordinata
    
        - Dopo la notifica al CSIRT, ENISA inoltra la segnalazione ad altri CSIRT interessati (Art.14 Abs.7 CRA).
        - Comunicazione pubblica: ENISA pubblica informazioni sulle vulnerabilita segnalate dopo periodi adeguati.
        - 
            Divulgazione volontaria (Voluntary Disclosure, Art.14 Abs.8 CRA): i fabbricanti possono anche segnalare
            vulnerabilita su base volontaria; questa e considerata buona prassi e puo essere valutata positivamente
            dalle autorita di vigilanza.
        
        - 
            security.txt (Art.13 Abs.6 CRA): i fabbricanti devono predisporre un canale di contatto per segnalazioni
            di vulnerabilita da parte di terzi.
            [ /help/schwachstellenmanagement/security-txt](/help/schwachstellenmanagement/security-txt)
        
    

    ## Cosa deve preparare internamente il fabbricante?
    
        - Documentare una procedura interna di vulnerability management (canale di ingresso, valutazione della conformità, escalation, catena di notifica)
        - Garantire disponibilita 24h: chi notifica? in quale lingua? con quali credenziali per la piattaforma ENISA?
        - Stabilire una procedura di valutazione CVSS (per il rapporto finale)
        - Conservazione delle notifiche: almeno 10 anni (Art.13 Abs.14 CRA)
        - Configurare e mantenere aggiornato security.txt (Art.13 Abs.6 CRA)
        - Coordinarsi con la supply chain: informare i fabbricanti di componenti
        - Usare BSI TR-03183 come riferimento per la progettazione del processo
    

    ## Sanzioni in caso di violazioni
    
        - 
            Violazione degli obblighi di notifica secondo Art.14: fino a 10 milioni EUR o 2% del fatturato annuo mondiale
            (Art.64 Abs.2 CRA - trattato come violazione di altri obblighi).
        
        - 
            Eccezione per piccole e microimprese: nessuna sanzione per mancato rispetto del termine 24h
            (Art.64 Abs.10 CRA come da Corrigendum 2025/90555). L obbligo di notifica resta invariato.
        
        - 
            Applicazione da parte delle autorita nazionali di vigilanza del mercato
            (in Germania: BSI ai sensi di Art.35 CRA).
        
    

    
        Fondamenti correlati:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (marcatura CE)
    

    ## Fonti ufficiali
    
        - 
            [
                Art.14 Regulation (EU) 2024/2847 (testo completo)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                BSI - Obblighi di notifica CRA
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                ENISA - Cyber Resilience Act
            ](https://www.enisa.europa.eu/topics/cyber-resilience-act)
        
        - 
            [
                EC FAQ CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
