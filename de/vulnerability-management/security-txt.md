---
title: "security.txt nach Art.13 Abs.6 CRA: Kontaktweg für Schwachstellenmeldungen"
description: "Art.13 Abs.6 der Verordnung (EU) 2024/2847 verpflichtet Hersteller zur Einrichtung einer security.txt-Datei als Kontaktweg für Schwachstellenmeldungen Dritter."
lastUpdated: "2026-05-02"
lang: de
source: cra-ready.de
---

# security.txt nach Art.13 Abs.6 CRA: Kontaktweg für Schwachstellenmeldungen

## Was fordert Art.13 Abs.6 CRA?
    
        - Hersteller müssen einen einfach zugänglichen Kontaktweg bereitstellen, damit Dritte (Sicherheitsforscher, Nutzer) Schwachstellen melden können.
        - security.txt (RFC 9116) ist der de-facto-Standard hierfür.
        - Pfad: https://{domain}/.well-known/security.txt
        - Gilt ab: 11. Dezember 2027 (allgemeine CRA-Anforderungen), aber Best Practice ist die sofortige Einrichtung.
    

    ## Mindestinhalt der security.txt (RFC 9116)
    ```
`Contact: mailto:security@example.com
Expires: 2027-01-01T00:00:00z
Preferred-Languages: de, en
Policy: https://example.com/security-policy`
```

    ## Empfohlene Zusatzfelder für CRA-Konformität
    
        - **Encryption:** Link zu PGP-Schlüssel
        - **Acknowledgments:** Hall of Fame für Melder
        - **Hiring:** optional
        - **CSAF:** Link zu CSAF-Dokument falls vorhanden (Art.14 Abs.9 CRA)
    

    ## Zusammenspiel mit Art.14 Meldepflichten
    
        - security.txt = eingehende Meldungen von Dritten (Art.13 Abs.6 CRA)
        - Art.14 Meldungen = ausgehende Meldungen des Herstellers an CSIRT/ENISA
        - Beides ist erforderlich und ergänzt sich
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Offizielle Quellen
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Art.13 Abs.6)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                https://www.rfc-editor.org/rfc/rfc9116 (RFC 9116 security.txt Standard)
            ](https://www.rfc-editor.org/rfc/rfc9116)
        
        - 
            [
                https://securitytxt.org (Generator-Tool)
            ](https://securitytxt.org)
