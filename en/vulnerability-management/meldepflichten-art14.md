---
title: "CRA Reporting Obligations under Art.14: 24h, 72h and 14-day Deadlines"
description: "From 11 September 2026, manufacturers must report actively exploited vulnerabilities to the ENISA platform within 24 hours. All deadlines and..."
lastUpdated: "2026-05-02"
lang: en
source: cra-ready.de
---

# CRA Reporting Obligations under Art.14: 24h, 72h and 14-day Deadlines

## Introduction: When do the reporting obligations apply?
    
        Art.14 CRA applies from **11 September 2026**
        (21 months after entry into force, Art.71 para.2 CRA).
    

    
        This is the **first binding CRA obligation**, even before the general
        security requirements (December 2027).
    

    
        It applies to all manufacturers of products with digital elements
        made available on the EU market.
    

    
        Exception: micro and small enterprises are exempt from fines for missing
        the 24h deadline (Art.64 para.10 CRA, Corrigendum 2025/90555 of 2 July 2025).
        The **OBLIGATION** to report still applies.
    

    ## What must be reported?
    Two triggers (Art.14 para.1 and para.3 CRA):

    ### Trigger 1 - Actively exploited vulnerability
    
        - 
            Definition: A vulnerability in the manufacturer's own product where the manufacturer has knowledge
            that attackers are actively exploiting it (Art.14 para.1 CRA).
        
        - 
            Reporting obligation: immediately, no later than 24 hours after becoming aware
            (Art.14 para.2 lit.a CRA).
        
    

    ### Trigger 2 - Severe incident
    
        - 
            Definition: An incident that affects the security of the product and can impact
            availability, confidentiality, or integrity (Art.14 para.3 CRA).
        
        - 
            Reporting obligation: immediately, no later than 24 hours after becoming aware
            (Art.14 para.4 lit.a CRA).
        
    

    ## The three reporting deadlines in detail
    
    
            
                
                    Deadline
                    Content
                    Legal basis
                
            
            
                
                    **24-hour initial report**
No later than 24 hours after becoming aware
                    Initial report (early warning); full information is not yet required; indication whether the vulnerability or incident suggests unlawful or malicious action
                    Art.14 para.2 lit.a and Art.14 para.4 lit.a CRA
                
                
                    **72-hour follow-up report**
No later than 72 hours after becoming aware
                    Updated report with available information on the vulnerability or incident; initial assessment; where applicable indicators of compromise (IoC)
                    Art.14 para.2 lit.b and Art.14 para.4 lit.b CRA
                
                
                    **Final report (14 days / 1 month)**
Vulnerabilities: no later than 14 days after availability of a security update or workaround; incidents: no later than 1 month after initial report
                    Complete description; severity; CVSS score where available; affected versions; measures taken; status of the security update
                    Art.14 para.2 lit.c and Art.14 para.4 lit.c CRA
                
            
        
    

    ## Who receives the report?
    
        - Reporting is made to the CSIRT of the Member State of the manufacturer's main establishment (Art.14 para.1 CRA).
        - In Germany: BSI (Federal Office for Information Security) as the competent CSIRT.
        - 
            Technical channel: ENISA Single Reporting Platform.
            The platform is operated by ENISA and automatically forwards reports to the competent national CSIRT.
        
        - Status (May 2026): The platform must be operational by 11 September 2026 (Art.16 CRA).
    
    
        **IMPORTANT NOTE:** The precise technical specifications and access model for the ENISA platform
        are defined by the Commission via implementing act (Art.16 para.4 CRA).
        Manufacturers should monitor ENISA and BSI announcements for current information.
    

    ## Coordinated disclosure
    
        - After reporting to the CSIRT, ENISA forwards the report to other affected CSIRTs (Art.14 para.7 CRA).
        - Public disclosure: ENISA publishes information on reported vulnerabilities after appropriate time periods.
        - 
            Voluntary disclosure (Art.14 para.8 CRA): manufacturers may also report vulnerabilities voluntarily;
            this is considered good practice and may be viewed positively by supervisory authorities.
        
        - 
            security.txt (Art.13 para.6 CRA): manufacturers must provide a contact channel for third-party vulnerability reports.
            [ /help/schwachstellenmanagement/security-txt](/help/schwachstellenmanagement/security-txt)
        
    

    ## What must manufacturers prepare internally?
    
        - Document an internal vulnerability management procedure (intake channel, assessment, escalation, reporting chain)
        - Ensure 24h readiness: who reports, in which language, and with which ENISA platform credentials?
        - Establish a CVSS scoring process (for final reporting)
        - Retention of reports: at least 10 years (Art.13 para.14 CRA)
        - Set up and maintain security.txt (Art.13 para.6 CRA)
        - Coordinate with the supply chain: inform component manufacturers
        - Use BSI TR-03183 as practical guidance for process design
    

    ## Sanctions for non-compliance
    
        - 
            Breach of reporting obligations under Art.14: up to EUR 10 million or 2% of worldwide annual turnover
            (Art.64 para.2 CRA - treated as breach of other obligations).
        
        - 
            Exception for small and micro enterprises: no fines for missing the 24h deadline
            (Art.64 para.10 CRA as corrected by Corrigendum 2025/90555). The reporting obligation itself remains.
        
        - 
            Enforcement by national market surveillance authorities
            (in Germany: BSI pursuant to Art.35 CRA).
        
    

    
        Related fundamentals:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
    

    ## Official sources
    
        - 
            [
                Art.14 Regulation (EU) 2024/2847 (full text)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                BSI - CRA reporting obligations
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                ENISA - Cyber Resilience Act
            ](https://www.enisa.europa.eu/topics/cyber-resilience-act)
        
        - 
            [
                EC CRA FAQ (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
