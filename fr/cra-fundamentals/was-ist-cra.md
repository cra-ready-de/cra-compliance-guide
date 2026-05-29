---
title: "Qu\"
description: "Explication du Cyber Resilience Act (Regulation (EU) 2024/2847) : objectifs, champ d\"
lastUpdated: "2026-05-02"
lang: fr
source: cra-ready.de
---

# Qu\

## Introduction : Qu'est-ce que le Cyber Resilience Act ?
    
        Le Cyber Resilience Act (CRA) est la **Regulation (EU) 2024/2847** du Parlement européen et du Conseil.
        La Regulation est en vigueur depuis le **11 December 2024** et a été publiée au Journal officiel de l'Union européenne
        le **20 November 2024**.
    

    
        En tant que règlement horizontal, le CRA s'applique directement dans tous les États membres de l'UE ; une transposition nationale n'est pas nécessaire.
        L'objectif est d'établir un cadre harmonisé de cybersécurité pour les produits comportant des éléments numériques sur l'ensemble du cycle de vie du produit.
    

    ## Pourquoi le CRA a-t-il été introduit ?
    
        - Augmentation des cyberattaques contre les produits connectés (IoT, OT et installations industrielles).
        - Avant le CRA, le cadre juridique était fragmenté avec des exigences non uniformes dans l'UE.
        - Le CRA complète la directive NIS-2 : NIS-2 se concentre sur les organisations, le CRA se concentre sur les produits.
    

    ## Qu'est-ce qu'un "produit comportant des éléments numériques" ?
    
        La définition applicable figure à l'**Art.3 Nr.1 CRA**. Sont visés les produits dont la fonction prévue
        dépend totalement ou partiellement d'un logiciel ou d'un traitement de données.
    

    Exemples typiques :

    
        - Routeurs industriels
        - Automates SPS/PLC
        - Logiciels SCADA
        - Passerelles IIoT
        - Systèmes Linux embarqués
        - Systèmes de gestion de réseau
    
    
        Ne sont notamment pas couverts par le CRA les domaines de produits disposant d'une réglementation sectorielle propre,
        par exemple les dispositifs médicaux (MDR), les véhicules et les produits aéronautiques.
    

    ## Qui est concerné ?
    
        Sont notamment concernés les fabricants (**Art.3 Nr.13**), les mandataires (**Art.3 Nr.17**),
        les importateurs (**Art.3 Nr.18**) et les distributeurs (**Art.3 Nr.19**).
        Pour les stewards de logiciels open source (**Art.3 Nr.14**), les obligations sont limitées.
    

    
        Détails sur la délimitation des rôles :
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich)
    

    ## Qu'impose concrètement le CRA ?
    Les exigences peuvent être structurées en trois piliers :

    ### a) Exigences de sécurité (Annex I Part I)
    
        - Secure-by-design et secure-by-default
        - Surface d'attaque minimale et absence de vulnérabilités connues exploitables lors de la mise sur le marché
        - Chiffrement, contrôle d'accès et protection de l'intégrité
    

    ### b) Traitement des vulnérabilités (Annex I Part II + Art.14)
    
        - 
            Période de support : au moins 5 ans OU la durée d'utilisation attendue du produit, selon la période la plus longue
            (Art.13 Abs.8 CRA).
        
        - 
            **REMARQUE IMPORTANTE :** Le terme "expected use time"
            (expected use time / voraussichtliche Nutzungsdauer) n'est pas défini de manière exhaustive à l'Art.3 CRA.
            La Commission et les autorités nationales de surveillance préciseront ce terme par catégorie de produits et par secteur.
            Les fabricants devraient justifier leur estimation de la durée d'utilisation attendue dans la documentation technique (Annex VII).
        
        - Notification des vulnérabilités activement exploitées : 24h / 72h / 14 jours
    
    
        Détails sur la chaîne de notification :
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ### c) Transparence et documentation
    
        - 
            SBOM :
            [ /help/sbom/sbom-anforderungen](/help/sbom/sbom-anforderungen)
        
        - déclaration de conformité UE (DoC) et marquage CE
        - 
            Aperçu du marquage CE :
            [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung)
        
        - Documentation technique selon Annex VII
    

    ## Normes harmonisées - état 2026
    
        **REMARQUE IMPORTANTE POUR LES FABRICANTS :**
        La conformité technique ne sera pas évaluée uniquement au regard du texte de la Regulation,
        mais aussi au regard des normes harmonisées (Harmonised Standards) élaborées par CEN, CENELEC et ETSI
        sur la base du mandat de normalisation M/606 (décision de la Commission C(2025)618 du **3 February 2025**).
    

    État actuel (May 2026) :

    
        - Normes horizontales de type A et type B (traitement des vulnérabilités) : objectif de finalisation August 2026
        - Normes verticales de type C (spécifiques aux catégories de produits) : objectif de finalisation October 2026
        - Première publication au Journal officiel de l'UE : vraisemblablement Q2 2027
    
    
        Jusqu'à la publication des normes harmonisées, les fabricants peuvent s'appuyer sur des normes existantes
        (par ex. IEC 62443, ETSI EN 303 645), sans obtenir pour autant la présomption de conformité au CRA.
        BSI TR-03183 offre déjà une orientation pratique.
    

    ## Classification des produits en un coup d'œil
    
        
            
                
                    Catégorie
                    Description courte
                    Voie d'évaluation de la conformité
                
            
            
                
                    Default
                    Non listé dans Annex III/IV
                    Contrôle interne / auto-évaluation
                
                
                    Classe I
                    Catégories de produits importantes selon le CRA
                    Selon les normes harmonisées / évaluation par un tiers possible
                
                
                    Classe II
                    Criticité et risque plus élevés
                    En règle générale, évaluation de la conformité plus stricte
                
                
                    Critique
                    Produits avec un impact particulier sur la sécurité
                    Voie orientée certification / organisme notifié
                
            
        
    
    
        Détails sur la classification :
        [ /help/cra-grundlagen/produktklassifizierung](/help/cra-grundlagen/produktklassifizierung)
    

    
        Remarque : Implementing Regulation (EU) 2025/2392 (**28 November 2025**) fournit des descriptions techniques officielles
        pour les 28 catégories de produits.
    

    ## Sanctions
    
        - 
            Jusqu'à 15 millions EUR ou 2,5 % du chiffre d'affaires annuel mondial
            (pour les violations des obligations des fabricants, Art.64 Abs.1 CRA)
        
        - 
            Jusqu'à 10 millions EUR ou 2 % pour les autres opérateurs économiques (Art.64 Abs.2 CRA)
        
        - 
            Corrigendum 2025/90555 (**2 July 2025**) : Art.64 Abs.10 - les microentreprises et petites entreprises sont exemptées d'amendes
            en cas de non-respect des délais de l'obligation de notification sous 24h
        
    
    
        **REMARQUE IMPORTANTE :** Les montants indiqués sont les plafonds MAXIMAUX fixés à l'Art.64 CRA
        pour l'ensemble de l'UE. La fixation et l'exécution effectives des amendes relèvent des autorités nationales
        de surveillance du marché (en Allemagne : BSI en tant qu'autorité compétente selon l'Art.35 CRA).
        Les procédures et la pratique peuvent varier entre les États membres.
    

    ## Sources officielles
    
        - 
            [
                Regulation (EU) 2024/2847 dans EUR-Lex (texte intégral)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Stratégie numérique de la CE - aperçu CRA
            ](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
        
        - 
            [
                BSI - Cyber Resilience Act
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                FAQ de la Commission sur le CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (catégories de produits)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
