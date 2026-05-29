---
title: "What is the Cyber Resilience Act (CRA)?"
description: "The Cyber Resilience Act (Regulation EU 2024/2847) explained: objectives, scope, affected products, and what manufacturers need to know now."
lastUpdated: "2026-05-02"
lang: en
source: cra-ready.de
---

# What is the Cyber Resilience Act (CRA)?

## Introduction: What is the Cyber Resilience Act?
    
        The Cyber Resilience Act (CRA) is **Regulation (EU) 2024/2847** of the European Parliament and of the Council.
        The Regulation has applied since **11 December 2024** and was published in the Official Journal of the EU
        on **20 November 2024**.
    

    
        As a horizontal regulation, the CRA applies directly in all EU Member States; no national transposition is required.
        Its objective is to establish harmonized cybersecurity requirements for products with digital elements across the full
        product lifecycle.
    

    ## Why was the CRA introduced?
    
        - Rising cyberattacks against connected products (IoT, OT, and industrial systems).
        - Before the CRA, the EU legal framework was fragmented and inconsistent across jurisdictions.
        - The CRA complements the NIS-2 Directive: NIS-2 focuses on organizations, while the CRA focuses on products.
    

    ## What is a "product with digital elements"?
    
        The relevant definition is set out in **Art.3 No.1 CRA**. It covers products whose intended function depends,
        fully or partly, on software or data processing.
    

    Typical examples include:

    
        - Industrial routers
        - PLC/SPS controllers
        - SCADA software
        - IIoT gateways
        - Embedded Linux systems
        - Network management systems
    
    
        Product domains with dedicated sector regulation are outside CRA scope, e.g. medical devices (MDR), vehicles,
        and aviation products.
    

    ## Who is affected?
    
        The CRA affects manufacturers (**Art.3 No.13**), authorized representatives (**Art.3 No.17**),
        importers (**Art.3 No.18**), and distributors (**Art.3 No.19**).
        Open-source software stewards (**Art.3 No.14**) are subject to limited obligations.
    

    
        For role-by-role details, see:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich)
    

    ## What does the CRA require in practice?
    The requirements can be grouped into three pillars:

    ### a) Security requirements (Annex I Part I)
    
        - Secure-by-design and secure-by-default
        - Minimal attack surface and no known exploitable vulnerabilities at market placement
        - Encryption, access control, and integrity protection
    

    ### b) Vulnerability handling (Annex I Part II + Art.14)
    
        - 
            Support period: at least 5 years OR the expected use time of the product, whichever period is longer
            (Art.13 para.8 CRA).
        
        - 
            **IMPORTANT NOTE:** The term "expected use time"
            (expected use time / voraussichtliche Nutzungsdauer) is not conclusively defined in Art.3 CRA.
            The Commission and national supervisory authorities will further specify this concept by product category and industry.
            Manufacturers should justify their assessment of expected use time in the technical documentation (Annex VII).
        
        - Reporting of actively exploited vulnerabilities: 24h / 72h / 14-day
    
    
        Details of the reporting chain:
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ### c) Transparency and documentation
    
        - 
            SBOM:
            [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
        
        - EU Declaration of Conformity (DoC) and CE marking
        - 
            CE marking overview:
            [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
        
        - Technical documentation under Annex VII
    

    ## Harmonised standards - status as of 2026
    
        **IMPORTANT NOTE FOR MANUFACTURERS:**
        Technical conformity will ultimately be assessed not only against the regulatory text, but also against harmonised
        standards developed by CEN, CENELEC, and ETSI under standardisation request M/606
        (Commission Decision C(2025)618 of 3 February 2025).
    

    Current status (May 2026):

    
        - Horizontal Type A and Type B standards (vulnerability handling): target completion August 2026
        - Vertical Type C standards (product-category specific): target completion October 2026
        - First publication in the Official Journal of the EU: expected in Q2 2027
    
    
        Until harmonised standards are published, manufacturers may rely on existing standards
        (e.g. IEC 62443, ETSI EN 303 645), but without obtaining CRA presumption of conformity.
        BSI TR-03183 already provides practical implementation guidance.
    

    ## Product classification at a glance
    
        
            
                
                    Category
                    Short description
                    Conformity Assessment Route
                
            
            
                
                    Default
                    Not listed in Annex III/IV
                    Internal control / self-assessment
                
                
                    Class I
                    Important CRA categories
                    Depending on harmonised standards / third-party route possible
                
                
                    Class II
                    Higher criticality and risk profile
                    Typically stricter conformity assessment route
                
                
                    Critical
                    Products with especially high security relevance
                    Certification / Notified Body-oriented route
                
            
        
    
    
        Detailed classification guidance:
        [ /help/cra-grundlagen/produktklassifizierung](/help/cra-grundlagen/produktklassifizierung)
    

    
        Note: Implementing Regulation (EU) 2025/2392 (28.11.2025) provides official technical descriptions
        for all 28 product categories.
    

    ## Sanctions
    
        - 
            Up to EUR 15 million or 2.5% of worldwide annual turnover
            (for breaches of manufacturer obligations, Art.64 para.1 CRA)
        
        - 
            Up to EUR 10 million or 2% for other economic operators (Art.64 para.2 CRA)
        
        - 
            Corrigendum 2025/90555 (2 July 2025): Art.64 para.10 - micro and small enterprises are exempt from fines
            for deadline failures under the 24h reporting obligation
        
    
    
        **IMPORTANT NOTE:** The amounts above are the EU-wide maximum ceilings established in Art.64 CRA.
        The actual determination and enforcement of fines is carried out by national market surveillance authorities
        (in Germany: BSI as competent authority under CRA Art.35). Procedures and enforcement practice may vary
        across Member States.
    

    ## Official sources
    
        - 
            [
                Regulation (EU) 2024/2847 in EUR-Lex (full text)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                EC Digital Strategy - CRA overview
            ](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
        
        - 
            [
                BSI - Cyber Resilience Act
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                Commission CRA FAQ (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (product categories)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
