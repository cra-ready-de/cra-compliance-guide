---
title: "security.txt secondo Art.13 Abs.6 CRA: canale di contatto per segnalazioni di vulnerabilita"
description: "Art.13 Abs.6 della Regulation (EU) 2024/2847 obbliga i fabbricanti a predisporre un file security.txt come canale di contatto per segnalazioni di..."
lastUpdated: "2026-05-02"
lang: it
source: cra-ready.de
---

# security.txt secondo Art.13 Abs.6 CRA: canale di contatto per segnalazioni di vulnerabilita

## Cosa richiede Art.13 Abs.6 CRA?
    
        - I fabbricanti devono fornire un canale di contatto facilmente accessibile, in modo che terzi (ricercatori di sicurezza, utenti) possano segnalare vulnerabilita.
        - security.txt (RFC 9116) e lo standard de-facto per questo scopo.
        - Percorso: https://{domain}/.well-known/security.txt
        - Si applica dal: 11 December 2027 (requisiti CRA generali), ma la predisposizione immediata e best practice.
    

    ## Contenuto minimo di security.txt (RFC 9116)
    ```
`Contact: mailto:security@example.com
Expires: 2027-01-01T00:00:00z
Preferred-Languages: de, en
Policy: https://example.com/security-policy`
```

    ## Campi aggiuntivi consigliati per la conformita CRA
    
        - **Encryption:** link alla chiave PGP
        - **Acknowledgments:** hall of fame dei segnalatori
        - **Hiring:** opzionale
        - **CSAF:** link al documento CSAF se disponibile (Art.14 Abs.9 CRA)
    

    ## Interazione con gli obblighi di notifica secondo Art.14
    
        - security.txt = segnalazioni in ingresso da terzi (Art.13 Abs.6 CRA)
        - Notifiche Art.14 = notifiche in uscita del fabbricante verso CSIRT/ENISA
        - Entrambi sono obbligatori e complementari
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Fonti ufficiali
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Art.13 Abs.6)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                https://www.rfc-editor.org/rfc/rfc9116 (standard RFC 9116 security.txt)
            ](https://www.rfc-editor.org/rfc/rfc9116)
        
        - 
            [
                https://securitytxt.org (strumento generatore)
            ](https://securitytxt.org)
