---
title: "security.txt wedlug Art.13 Abs.6 CRA: kanal kontaktowy do zgloszen podatnosci"
description: "Art.13 Abs.6 Regulation (EU) 2024/2847 zobowiazuje producentow do udostepnienia pliku security.txt jako kanalu kontaktowego dla zgloszen podatnosci od..."
lastUpdated: "2026-05-02"
lang: pl
source: cra-ready.de
---

# security.txt wedlug Art.13 Abs.6 CRA: kanal kontaktowy do zgloszen podatnosci

## Co wymaga Art.13 Abs.6 CRA?
    
        - Producenci musza zapewnic latwo dostepny kanal kontaktowy, aby strony trzecie (badacze bezpieczenstwa, uzytkownicy) mogly zglaszac podatnosci.
        - security.txt (RFC 9116) jest de-facto standardem do tego celu.
        - Sciezka: https://{domain}/.well-known/security.txt
        - Obowiazuje od: 11 December 2027 (ogolne wymagania CRA), ale natychmiastowe wdrozenie to best practice.
    

    ## Minimalna zawartosc security.txt (RFC 9116)
    ```
`Contact: mailto:security@example.com
Expires: 2027-01-01T00:00:00z
Preferred-Languages: de, en
Policy: https://example.com/security-policy`
```

    ## Zalecane pola dodatkowe dla zgodnosci z CRA
    
        - **Encryption:** link do klucza PGP
        - **Acknowledgments:** hall of fame dla zglaszajacych
        - **Hiring:** opcjonalne
        - **CSAF:** link do dokumentu CSAF, jesli jest dostepny (Art.14 Abs.9 CRA)
    

    ## Powiazanie z obowiazkami zgloszeniowymi z Art.14
    
        - security.txt = przychodzace zgloszenia od stron trzecich (Art.13 Abs.6 CRA)
        - Zgloszenia Art.14 = wychodzace zgloszenia producenta do CSIRT/ENISA
        - Oba sa wymagane i wzajemnie sie uzupelniaja
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Oficjalne zrodla
    
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
                https://securitytxt.org (narzedzie generatora)
            ](https://securitytxt.org)
