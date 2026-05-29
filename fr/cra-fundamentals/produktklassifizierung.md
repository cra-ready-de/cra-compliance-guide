---
title: "Classification des produits CRA : Default, Classe I, Classe II et Critique"
description: "Comment classer votre produit selon Regulation (EU) 2024/2847 ? Default, Important Classe I/II ou Critique, avec les descriptions officielles de..."
lastUpdated: "2026-05-02"
lang: fr
source: cra-ready.de
---

# Classification des produits CRA : Default, Classe I, Classe II et Critique

## Introduction : pourquoi la classification est-elle decisive ?
    
        La classe de produit determine la procedure d évaluation de la conformité et donc l effort et le cout de
        la conformité CRA pour les produits comportant des éléments numériques.
    

    
        La base juridique est **CRA Annex III** (produits importants) et **CRA Annex IV**
        (produits critiques).
    

    
        La specification detaillee est fournie par **Implementing Regulation (EU) 2025/2392** du
        **28 November 2025** (publiee au Journal officiel de l UE le **1 December 2025**).
        Cette regulation fournit des descriptions techniques officielles pour les 28 categories de produits de Annex III et IV,
        et elimine ainsi l incertitude d interpretation existant jusque-la.
    

    
        **IMPORTANT :** Le critere determinant est la **FONCTION PRINCIPALE** du produit,
        et non son nom, son appellation marketing ou ses fonctions secondaires
        (EC FAQ Dec 2025, sections 3.2 and 3.4; Implementing Regulation (EU) 2025/2392, recitals 3-5).
    

    ## Le modele a quatre niveaux
    
        
            
                
                    Niveau
                    Base juridique
                    Exemples (pertinents pour l industrie)
                    Évaluation de la conformité
                
            
            
                
                    **Standard (Default)**
                    Tous les produits NON listes en Annex III ou IV (~90 % de tous les produits)
                    Systemes embarques simples sans fonction reseau, IHM industrielle hors ligne, unites de commande non connectees
                    Auto-évaluation (Module A, Art.32 para.1 CRA)
                
                
                    **Important Classe I**
                    CRA Annex III Classe I + Implementing Regulation (EU) 2025/2392 Annex I Part 1
                    Gestionnaires de mots de passe, systemes de gestion reseau, logiciels de supervision reseau, systemes d exploitation a usage general, routeurs et modems domestiques, commutateurs
                    Auto-évaluation UNIQUEMENT en cas d application de normes harmonisees (Art.32 para.2 CRA) ; sinon organisme notifié requis
                
                
                    **Important Classe II**
                    CRA Annex III Classe II + Implementing Regulation (EU) 2025/2392 Annex I Part 2
                    Hyperviseurs, pare-feu, systemes de detection/prevention d intrusion, systemes industriels d automatisation et de controle (IACS) uniquement lorsqu ils sont utilises par des entites relevant de NIS-2, microprocesseurs resistants a la falsification
                    Organisme notifié OBLIGATOIRE (Art.32 para.3 CRA) OU certification europeenne de cybersécurité (Art.32 para.4)
                
                
                    **Critique**
                    CRA Annex IV + Implementing Regulation (EU) 2025/2392 Annex II
                    Modules materiels de securite (HSM), CI de cartes a puce, cartes a puce et dispositifs similaires, dispositifs pour fonctions de securite avancees (par ex. jetons materiels certifies)
                    Organisme notifié OBLIGATOIRE ou certification europeenne de cybersécurité (Art.33 and 34 CRA)
                
            
        
    

    ## Le test de fonction principale
    
        **NOTE D INTERPRETATION IMPORTANTE :** Un produit est classe selon sa FONCTION PRINCIPALE,
        et non selon ses composants integres.
    

    Exemples issus de la FAQ de la Commission (Dec 2025) :

    
        - Un smartphone avec gestionnaire de mots de passe integre reste dans la categorie standard, car sa fonction principale n est pas la gestion des mots de passe.
        - Une application avec navigateur integre n est pas un produit « navigateur », car sa fonction principale n est pas la navigation web.
        - Un systeme d automatisation industrielle est Classe II UNIQUEMENT lorsque l operateur releve de NIS-2 (Implementing Regulation (EU) 2025/2392).
    
    
        Remarque : la delimitation exacte des produits multi-fonctions peut etre complexe au cas par cas.
        La Commission a annonce des orientations complementaires.
    

    ## Procedures d évaluation de la conformité en bref
    
        - 
            **Module A (auto-évaluation) :** Le fabricant prepare la documentation technique et etablit la
            déclaration de conformité UE. Suffisant pour Default et Classe I avec normes harmonisees.
        
        - 
            **Organisme notifié :** Une tierce partie independante realise l évaluation de la conformité.
            Requis pour Classe I sans normes harmonisees, Classe II et Critique.
        
        - 
            **Etat des organismes notifiés (May 2026) :** Les Etats membres devaient publier les procedures d evaluation et
            de designation des organismes d évaluation de la conformité avant 11 June 2026 (Art.35 CRA).
            Les Etats membres doivent garantir un nombre suffisant d organismes notifiés avant 11 December 2026 (Art.35 para.2 CRA).
        
    
    
        Details de la procedure :
        [ /help/konformitaet/konformitaetsbewertung](/help/konformitaet/konformitaetsbewertung)
    

    ## Familles de produits
    
        Les fabricants ayant plus d un produit n ont pas besoin de lancer un projet de conformite separe pour chaque produit.
        Les produits ayant des caracteristiques proches peuvent etre regroupes en familles de produits.
    

    Dimensions pertinentes (selon les orientations de la Commission) :

    
        - Meme usage prevu et usage raisonnablement previsible
        - Actifs similaires (cles cryptographiques, fonctions reseau)
        - Memes profils de menace
        - Composants logiciels communs / chevauchements SBOM
    

    
        Fondamentaux associes :
        [ /help/cra-grundlagen/geltungsbereich](/help/cra-grundlagen/geltungsbereich),
        [ /help/konformitaet/ce-kennzeichnung](/help/konformitaet/ce-kennzeichnung) (marquage CE),
        [ /help/schwachstellenmanagement/meldepflichten-art14](/help/schwachstellenmanagement/meldepflichten-art14)
    

    ## Sources officielles
    
        - 
            [
                Regulation (EU) 2024/2847, Annex III and IV
            ](https://eur-lex.europa.eu/eli/reg/2024/2847/oj)
        
        - 
            [
                Implementing Regulation (EU) 2025/2392 (categories de produits officielles)
            ](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=OJ:L_202502392)
        
        - 
            [
                BSI CRA Flyer #2 - Classification des produits
            ](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Cyber_Resilience_Act/cyber_resilience_act_node.html)
        
        - 
            [
                EC CRA FAQ (Dec 2025), sections 3.1-3.4
            ](https://ec.europa.eu/newsroom/dae/redirection/document/109664)
