---
title: "CRA Product Classification: Default, Class I, Class II and Critical"
description: "How to classify your product under Regulation EU 2024/2847? Default, Important Class I/II or Critical – with official descriptions from Implementing..."
lastUpdated: "2026-05-02"
lang: en
source: cra-ready.de
---

# CRA Product Classification: Default, Class I, Class II and Critical

## Introduction: Why is classification decisive?
    
        The product class determines the conformity assessment procedure and therefore the effort and cost of
        CRA compliance.
    

    
        The legal basis is **CRA Annex III** (important products) and **CRA Annex IV**
        (critical products).
    

    
        Further specification is provided by **Implementing Regulation (EU) 2025/2392** of
        **28 November 2025** (published in the Official Journal of the EU on **1 December 2025**).
        This Regulation provides official technical descriptions for all 28 product categories in Annex III and IV,
        removing the interpretative uncertainty that existed until then.
    

    
        **IMPORTANT:** The decisive criterion is the product's **CORE FUNCTION**, not its name,
        marketing label, or secondary functions
        (EC FAQ Dec 2025, sections 3.2 and 3.4; Implementing Regulation 2025/2392, recitals 3-5).
    

    ## The four-level model
    
        
            
                
                    Level
                    Legal basis
                    Examples (industry-relevant)
                    Conformity assessment
                
            
            
                
                    **Standard (Default)**
                    All products NOT listed in Annex III or IV (~90% of all products)
                    Simple embedded systems without network function, offline industrial HMI, non-connected control units
                    Self-assessment (Module A, Art.32 para.1 CRA)
                
                
                    **Important Class I**
                    CRA Annex III Class I + Implementing Regulation 2025/2392 Annex I Part 1
                    Password managers, network management systems, network monitoring software, general-purpose operating systems, home routers and modems, switches
                    Self-assessment ONLY when harmonised standards are applied (Art.32 para.2 CRA); otherwise Notified Body required
                
                
                    **Important Class II**
                    CRA Annex III Class II + Implementing Regulation 2025/2392 Annex I Part 2
                    Hypervisors, firewalls, intrusion detection/prevention systems, industrial automation and control systems (IACS) only when used by entities falling under NIS-2, tamper-resistant microprocessors
                    Notified Body MANDATORY (Art.32 para.3 CRA) OR EU cybersecurity certification (Art.32 para.4)
                
                
                    **Critical**
                    CRA Annex IV + Implementing Regulation 2025/2392 Annex II
                    Hardware security modules (HSM), smart-card ICs, smart cards and similar devices, devices for advanced security purposes (e.g. certified hardware tokens)
                    Notified Body MANDATORY or EU cybersecurity certification (Art.33 and 34 CRA)
                
            
        
    

    ## The core function test
    
        **IMPORTANT INTERPRETATION NOTE:** A product is classified by its CORE FUNCTION,
        not by integrated components.
    

    Examples from the EC FAQ (Dec 2025):

    
        - A smartphone with an integrated password manager remains in the standard category because its core function is not password management.
        - An app with an embedded browser is not a "browser" product because its core function is not browsing.
        - An industrial automation system is Class II ONLY when the operator falls under NIS-2 (Implementing Regulation 2025/2392).
    
    
        Note: Exact boundaries for multi-function products can be complex in individual cases.
        The Commission has announced further guidance.
    

    ## Conformity assessment procedures at a glance
    
        - 
            **Module A (self-assessment):** The manufacturer prepares technical documentation and issues the
            EU declaration of conformity. Sufficient for Default and Class I with harmonised standards.
        
        - 
            **Notified Body:** An independent third party assesses conformity.
            Required for Class I without harmonised standards, Class II, and Critical.
        
        - 
            **Status of Notified Bodies (May 2026):** Member States had to publish procedures for assessment and
            designation of conformity assessment bodies by 11 June 2026 (Art.35 CRA).
            Member States should ensure sufficient Notified Bodies by 11 December 2026 (Art.35 para.2 CRA).
        
    
    
        Procedure details:
        [ /help/konformitaet/konformitaetsbewertung](/help/konformitaet/konformitaetsbewertung)
    

    ## Product families
    
        Manufacturers with more than one product do not need to run a separate conformity project for every product.
        Products with similar characteristics can be grouped into product families.
    

    Relevant dimensions (from Commission guidance):

    
        - Same intended purpose and foreseeable use
        - Similar assets (cryptographic keys, network functions)
        - Same threat profiles
        - Shared software components / SBOM overlaps
    

    
        Related fundamentals:
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung),
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Official sources
    
        - 
            [
                Regulation (EU) 2024/2847, Annex III and IV
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (official product categories)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
        
        - 
            [
                BSI CRA Flyer #2 - Product classification
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                EC CRA FAQ (Dec 2025), sections 3.1-3.4
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
