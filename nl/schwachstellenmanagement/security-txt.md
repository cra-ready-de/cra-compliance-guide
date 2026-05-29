---
title: "security.txt volgens Art.13 Abs.6 CRA: contactkanaal voor kwetsbaarheidsmeldingen"
description: "Art.13 Abs.6 van Regulation (EU) 2024/2847 verplicht fabrikanten om een security.txt-bestand in te richten als contactkanaal voor..."
lastUpdated: "2026-05-02"
lang: nl
source: cra-ready.de
---

# security.txt volgens Art.13 Abs.6 CRA: contactkanaal voor kwetsbaarheidsmeldingen

## Wat vereist Art.13 Abs.6 CRA?
    
        - Fabrikanten moeten een eenvoudig toegankelijk contactkanaal aanbieden, zodat derden (security-onderzoekers, gebruikers) kwetsbaarheden kunnen melden.
        - security.txt (RFC 9116) is hiervoor de de-facto-standaard.
        - Pad: https://{domain}/.well-known/security.txt
        - Geldt vanaf: 11 December 2027 (algemene CRA-vereisten), maar directe inrichting is best practice.
    

    ## Minimale inhoud van security.txt (RFC 9116)
    ```
`Contact: mailto:security@example.com
Expires: 2027-01-01T00:00:00z
Preferred-Languages: de, en
Policy: https://example.com/security-policy`
```

    ## Aanbevolen extra velden voor CRA-conformiteit
    
        - **Encryption:** link naar PGP-sleutel
        - **Acknowledgments:** hall of fame voor melders
        - **Hiring:** optioneel
        - **CSAF:** link naar CSAF-document indien beschikbaar (Art.14 Abs.9 CRA)
    

    ## Samenhang met meldplichten volgens Art.14
    
        - security.txt = inkomende meldingen van derden (Art.13 Abs.6 CRA)
        - Art.14-meldingen = uitgaande meldingen van de fabrikant aan CSIRT/ENISA
        - Beide zijn verplicht en vullen elkaar aan
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Officiele bronnen
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Art.13 Abs.6)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                https://www.rfc-editor.org/rfc/rfc9116 (RFC 9116 security.txt-standaard)
            ](https://www.rfc-editor.org/rfc/rfc9116)
        
        - 
            [
                https://securitytxt.org (generator-tool)
            ](https://securitytxt.org)
