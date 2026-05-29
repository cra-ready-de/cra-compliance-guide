---
title: "SBOM-Anforderungen nach CRA: Software Bill of Materials nach Anhang I"
description: "Der CRA (Verordnung EU 2024/2847) verpflichtet Hersteller zur Erstellung einer SBOM. Was muss enthalten sein? Welche Formate sind geeignet?"
lastUpdated: "2026-05-02"
lang: de
source: cra-ready.de
---

# SBOM-Anforderungen nach CRA: Software Bill of Materials nach Anhang I

## Was ist eine SBOM und warum fordert der CRA sie?
    
        - SBOM = Software Bill of Materials: maschinenlesbare Liste aller Software-Komponenten eines Produkts inklusive Abhängigkeiten.
        - CRA-Anforderung: Anhang I Teil II Nr.1. Hersteller müssen Schwachstellen in Komponenten identifizieren und beheben können.
        - Die SBOM ist Grundlage für Schwachstellenmanagement, Lieferkettensicherheit und technische Dokumentation (Anhang VII CRA).
        - Gilt ab: 11. Dezember 2027.
    

    ## Pflichtinhalt der SBOM nach CRA Anhang I
    Mindestanforderungen (aus Anhang I Teil II Nr.1 CRA):

    
        - Alle Top-Level-Komponenten des Produkts
        - Transitive Abhängigkeiten (Komponenten der Komponenten), soweit für Schwachstellenidentifikation relevant
        - Für jede Komponente: Name, Version, Lieferant/Urheber
        - Eindeutige Identifikatoren (z.B. CPE, PURL)
        - Lizenzinformationen (für Open-Source-Komponenten)
    
    
        **Hinweis:** Der CRA definiert keinen verpflichtenden SBOM-Standard.
        Die Kommission kann per Durchführungsrechtsakt Formate festlegen.
        Bis dahin sind CycloneDX und SPDX de-facto-Standards.
        Formatvergleich:
        [ /help/sbom/sbom-formate](/help/sbom/sbom-formate)
    

    ## SBOM im Lebenszyklus - Aktualisierungspflicht
    
        - Die SBOM muss bei jedem Update aktualisiert werden (Art.13 Abs.5 CRA).
        - Bei Sicherheitsupdates sollte die SBOM-Aktualisierung zeitgleich mit dem Update erfolgen.
        - Aufbewahrung: als Teil der technischen Dokumentation für 10 Jahre.
        - Automatisierung wird empfohlen: SBOM-Generierung in der CI/CD-Pipeline.
    

    ## SBOM und Schwachstellenmanagement
    
        - Die SBOM ermöglicht die schnelle Identifikation betroffener Versionen bei neu bekannten Schwachstellen (CVE-Abgleich).
        - Zusammenspiel mit Art.14 CRA: Die SBOM beschleunigt die 24h-Erstmeldung, weil betroffene Komponenten sofort identifizierbar sind.
        - VEX (Vulnerability Exploitability eXchange) ist ein ergänzendes Format für Aussagen zur Ausnutzbarkeit von Schwachstellen.
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Weitergabe der SBOM
    
        - An Behörden: auf Anfrage der Marktüberwachungsbehörde (Art.13 Abs.12 CRA).
        - An Kunden/Nutzer: Der CRA fordert keine automatische Weitergabe, aber eine Transparenzpflicht gegenüber Nutzern (Art.13 Abs.18 CRA).
        - **Hinweis:** Kommerzielle Vertraulichkeit kann Einschränkungen der öffentlichen SBOM-Weitergabe rechtfertigen.
    

    ## Offizielle Quellen
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Anhang I Teil II)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                https://ec.europa.eu/newsroom/dae/redirection/document/109664
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                https://ntia.gov/sbom (NTIA SBOM Ressourcen)
            ](https://ntia.gov/sbom)
        
        - 
            [
                https://cyclonedx.org (CycloneDX Standard)
            ](https://cyclonedx.org)
        
        - 
            [
                https://spdx.dev (SPDX Standard)
            ](https://spdx.dev)
