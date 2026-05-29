---
title: "Obligations de notification CRA selon Art.14 : delais de 24h, 72h et 14 jours"
description: "A partir du 11 September 2026, les fabricants doivent notifier les vulnerabilites activement exploitees a la plateforme ENISA dans les 24 heures. Tous..."
lastUpdated: "2026-05-02"
lang: fr
source: cra-ready.de
---

# Obligations de notification CRA selon Art.14 : delais de 24h, 72h et 14 jours

## Introduction : a partir de quand l obligation de notification s applique-t-elle ?
    
        Art.14 CRA s applique a partir du **11 September 2026**
        (21 mois apres l entree en vigueur, Art.71 Abs.2 CRA).
    

    
        Il s agit de la **premiere obligation CRA contraignante**, meme avant les exigences
        generales de securite (December 2027).
    

    
        Elle concerne tous les fabricants de produits comportant des éléments numériques
        mis a disposition sur le marche de l UE.
    

    
        Exception : les microentreprises et petites entreprises sont exemptees d amendes en cas de non-respect
        du delai de 24h (Art.64 Abs.10 CRA, Corrigendum 2025/90555 du 2 July 2025).
        L **OBLIGATION** de notification demeure.
    

    ## Que faut-il notifier ?
    Deux declencheurs (Art.14 Abs.1 et Abs.3 CRA) :

    ### Declencheur 1 - Vulnerabilite activement exploitee
    
        - 
            Definition : une vulnerabilite dans le propre produit du fabricant, pour laquelle le fabricant sait
            qu elle est activement exploitee par des attaquants (Art.14 Abs.1 CRA).
        
        - 
            Obligation de notification : immediatement, au plus tard dans les 24 heures apres prise de connaissance
            (Art.14 Abs.2 lit.a CRA).
        
    

    ### Declencheur 2 - Incident grave (Severe Incident)
    
        - 
            Definition : un incident qui affecte la securite du produit et peut avoir un impact sur
            la disponibilite, la confidentialite ou l integrite (Art.14 Abs.3 CRA).
        
        - 
            Obligation de notification : immediatement, au plus tard dans les 24 heures apres prise de connaissance
            (Art.14 Abs.4 lit.a CRA).
        
    

    ## Les trois delais de notification en detail
    
    
            
                
                    Delai
                    Contenu
                    Base juridique
                
            
            
                
                    **Notification initiale 24 heures**
Au plus tard 24 heures apres prise de connaissance
                    Premiere notification (Early Warning) ; informations completes non encore requises ; indication si la vulnerabilite ou l incident suggere un acte illicite ou malveillant
                    Art.14 Abs.2 lit.a et Art.14 Abs.4 lit.a CRA
                
                
                    **Notification de suivi 72 heures**
Au plus tard 72 heures apres prise de connaissance
                    Notification mise a jour avec informations disponibles sur la vulnerabilite ou l incident ; premiere évaluation de la conformité ; le cas echeant indicateurs de compromission (IoC)
                    Art.14 Abs.2 lit.b et Art.14 Abs.4 lit.b CRA
                
                
                    **Rapport final (14 jours / 1 mois)**
Vulnerabilites : au plus tard 14 jours apres disponibilite d une mise a jour de securite ou d un contournement ; incidents : au plus tard 1 mois apres notification initiale
                    Description complete ; gravite ; score CVSS si disponible ; versions affectees ; mesures prises ; etat de la mise a jour de securite
                    Art.14 Abs.2 lit.c et Art.14 Abs.4 lit.c CRA
                
            
        
    

    ## A qui notifier ?
    
        - La notification est faite au CSIRT de l Etat membre de l etablissement principal du fabricant (Art.14 Abs.1 CRA).
        - En Allemagne : BSI (Bundesamt fuer Sicherheit in der Informationstechnik) en tant que CSIRT competent.
        - 
            Canal technique : ENISA Single Reporting Platform.
            La plateforme est exploitee par ENISA et transmet automatiquement les notifications au CSIRT national competent.
        
        - Statut (May 2026) : la plateforme doit etre operationnelle au plus tard le 11 September 2026 (Art.16 CRA).
    
    
        **NOTE IMPORTANTE :** les specifications techniques detaillees et l acces a la plateforme ENISA
        sont fixes par la Commission via acte d execution (Art.16 Abs.4 CRA).
        Les fabricants doivent suivre les publications ENISA et BSI pour les informations a jour.
    

    ## Divulgation coordonnee
    
        - Apres notification au CSIRT, ENISA transfere la notification aux autres CSIRT concernes (Art.14 Abs.7 CRA).
        - Publication publique : ENISA publie des informations sur les vulnerabilites notifiees apres un delai approprie.
        - 
            Divulgation volontaire (Voluntary Disclosure, Art.14 Abs.8 CRA) : les fabricants peuvent aussi notifier
            volontairement des vulnerabilites ; cela est considere comme une bonne pratique et peut etre evalue positivement
            par les autorites de surveillance.
        
        - 
            security.txt (Art.13 Abs.6 CRA) : les fabricants doivent fournir un canal de contact pour les notifications
            de vulnerabilites par des tiers.
            [ /help/schwachstellenmanagement/security-txt](/help/schwachstellenmanagement/security-txt)
        
    

    ## Que doit preparer le fabricant en interne ?
    
        - Documenter une procedure interne de gestion des vulnerabilites (canal d entree, évaluation de la conformité, escalade, chaine de notification)
        - Assurer une capacite 24h : qui notifie ? dans quelle langue ? avec quels acces a la plateforme ENISA ?
        - Etablir un processus de notation CVSS (pour le rapport final)
        - Conservation des notifications : au moins 10 ans (Art.13 Abs.14 CRA)
        - Mettre en place et maintenir security.txt (Art.13 Abs.6 CRA)
        - Coordination avec la chaine d approvisionnement : informer les fabricants de composants
        - Utiliser BSI TR-03183 comme reference pour la conception du processus
    

    ## Sanctions en cas de non-conformite
    
        - 
            Violation des obligations de notification selon Art.14 : jusqu a 10 millions EUR ou 2 % du chiffre d affaires
            annuel mondial (Art.64 Abs.2 CRA - traite comme violation d autres obligations).
        
        - 
            Exception pour les petites et microentreprises : pas d amendes en cas de non-respect du delai de 24h
            (Art.64 Abs.10 CRA dans la version Corrigendum 2025/90555). L obligation de notification elle-meme demeure.
        
        - 
            Mise en oeuvre par les autorites nationales de surveillance du marche
            (en Allemagne : BSI conformement a Art.35 CRA).
        
    

    
        Fondamentaux lies :
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (marquage CE)
    

    ## Sources officielles
    
        - 
            [
                Art.14 Regulation (EU) 2024/2847 (texte integral)
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                BSI - Obligations de notification CRA
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                ENISA - Cyber Resilience Act
            ](https://www.enisa.europa.eu/topics/cyber-resilience-act)
        
        - 
            [
                EC FAQ CRA (Dec 2025)
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
