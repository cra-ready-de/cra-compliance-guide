---
title: "security.txt selon Art.13 Abs.6 CRA : canal de contact pour les notifications de vulnerabilites"
description: "Art.13 Abs.6 de la Regulation (EU) 2024/2847 oblige les fabricants a mettre en place un fichier security.txt comme canal de contact pour les..."
lastUpdated: "2026-05-02"
lang: fr
source: cra-ready.de
---

# security.txt selon Art.13 Abs.6 CRA : canal de contact pour les notifications de vulnerabilites

## Que demande Art.13 Abs.6 CRA ?
    
        - Les fabricants doivent fournir un canal de contact facilement accessible afin que des tiers (chercheurs en securite, utilisateurs) puissent signaler des vulnerabilites.
        - security.txt (RFC 9116) est le standard de-facto pour cela.
        - Chemin : https://{domain}/.well-known/security.txt
        - Applicable a partir du : 11 December 2027 (exigences CRA generales), mais la mise en place immediate est une bonne pratique.
    

    ## Contenu minimal de security.txt (RFC 9116)
    ```
`Contact: mailto:security@example.com
Expires: 2027-01-01T00:00:00z
Preferred-Languages: de, en
Policy: https://example.com/security-policy`
```

    ## Champs supplementaires recommandes pour la conformite CRA
    
        - **Encryption :** lien vers la cle PGP
        - **Acknowledgments :** hall of fame des declarants
        - **Hiring :** optionnel
        - **CSAF :** lien vers un document CSAF s il existe (Art.14 Abs.9 CRA)
    

    ## Interaction avec les obligations de notification selon Art.14
    
        - security.txt = notifications entrantes de tiers (Art.13 Abs.6 CRA)
        - Notifications Art.14 = notifications sortantes du fabricant vers CSIRT/ENISA
        - Les deux sont requis et se completent
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Sources officielles
    
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
                https://securitytxt.org (outil de generation)
            ](https://securitytxt.org)
