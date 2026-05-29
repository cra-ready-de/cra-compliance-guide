---
title: "SBOM Requirements under CRA: Software Bill of Materials per Annex I"
description: "The CRA (Regulation EU 2024/2847) requires manufacturers to create an SBOM. What must it contain? Which formats are suitable?"
lastUpdated: "2026-05-02"
lang: en
source: cra-ready.de
---

# SBOM Requirements under CRA: Software Bill of Materials per Annex I

## What is an SBOM and why does the CRA require it?
    
        - SBOM = Software Bill of Materials: machine-readable list of all software components in a product, including dependencies.
        - CRA requirement: Annex I Part II No.1. Manufacturers must be able to identify and remediate vulnerabilities in components.
        - The SBOM is the basis for vulnerability management, supply chain security and technical documentation (Annex VII CRA).
        - Applies from: 11 December 2027.
    

    ## Mandatory SBOM content under CRA Annex I
    Minimum requirements (from Annex I Part II No.1 CRA):

    
        - All top-level components of the product
        - Transitive dependencies (components of components) where relevant for vulnerability identification
        - For each component: name, version, supplier/author
        - Unique identifiers (e.g. CPE, PURL)
        - License information (for open-source components)
    
    
        **Note:** The CRA does not define a mandatory SBOM standard.
        The Commission may define formats by implementing act.
        Until then, CycloneDX and SPDX are de-facto standards.
        Format comparison:
        [ /help/sbom/sbom-formate](/help/sbom/sbom-formate)
    

    ## SBOM in the lifecycle - update obligation
    
        - The SBOM must be updated with every product update (Art.13 Abs.5 CRA).
        - For security updates, SBOM updates should be released at the same time.
        - Retention: part of technical documentation for 10 years.
        - Automation is recommended: SBOM generation in the CI/CD pipeline.
    

    ## SBOM and vulnerability management
    
        - The SBOM enables quick identification of affected versions when new vulnerabilities become known (CVE matching).
        - Interaction with Art.14 CRA: SBOM data accelerates the 24h initial report because affected components are immediately identifiable.
        - VEX (Vulnerability Exploitability eXchange) is a complementary format for exploitability statements.
        - [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## SBOM sharing
    
        - To authorities: upon request of the market surveillance authority (Art.13 Abs.12 CRA).
        - To customers/users: the CRA does not require automatic distribution, but it requires transparency toward users (Art.13 Abs.18 CRA).
        - **Note:** Commercial confidentiality may justify restrictions on public SBOM disclosure.
    

    ## Official Sources
    
        - 
            [
                https://eur-lex.europa.eu/eli/reg/2024/2847/oj (Annex I Part II)
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
                https://ntia.gov/sbom (NTIA SBOM resources)
            ](https://ntia.gov/sbom)
        
        - 
            [
                https://cyclonedx.org (CycloneDX standard)
            ](https://cyclonedx.org)
        
        - 
            [
                https://spdx.dev (SPDX standard)
            ](https://spdx.dev)
