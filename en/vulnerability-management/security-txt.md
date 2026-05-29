---
title: "security.txt under Art.13(6) CRA: Contact channel for vulnerability reports"
description: "Art.13(6) of Regulation (EU) 2024/2847 requires manufacturers to provide a security.txt file as a contact channel for third-party vulnerability reports."
lastUpdated: "2026-05-02"
lang: en
source: cra-ready.de
---

# security.txt under Art.13(6) CRA: Contact channel for vulnerability reports

## What does Art.13 Abs.6 CRA require?
    
        - Manufacturers must provide an easily accessible contact channel so that third parties (security researchers, users) can report vulnerabilities.
        - security.txt (RFC 9116) is the de-facto standard for this.
        - Path: https://{domain}/.well-known/security.txt
        - Applies from: 11 December 2027 (general CRA requirements), but immediate setup is best practice.
    

    ## Minimum content of security.txt (RFC 9116)
    ```
`Contact: mailto:security@example.com
Expires: 2027-01-01T00:00:00z
Preferred-Languages: de, en
Policy: https://example.com/security-policy`
```

    ## Recommended additional fields for CRA conformity
    
        - **Encryption:** link to PGP key
        - **Acknowledgments:** hall of fame for reporters
        - **Hiring:** optional
        - **CSAF:** link to CSAF document if available (Art.14 Abs.9 CRA)
    

    ## Interaction with Art.14 reporting obligations
    
        - security.txt = incoming third-party reports (Art.13 Abs.6 CRA)
        - Art.14 reports = outgoing manufacturer reports to CSIRT/ENISA
        - Both are required and complementary
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Official sources
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Art.13 Abs.6)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                https://www.rfc-editor.org/rfc/rfc9116 (RFC 9116 security.txt standard)
            ](https://www.rfc-editor.org/rfc/rfc9116)
        
        - 
            [
                https://securitytxt.org (generator tool)
            ](https://securitytxt.org)
