# AÏA — Prototype clinique

Application HTML de démonstration pour le suivi clinique des violences faites aux femmes et du psychotrauma.

**Version en ligne** : v0.4 (rigueur clinique niveau praticien diplômé EMDR Europe).
**Statut** : prototype produit. Validation clinique en cours.

## Contenu

App single-page autonome (HTML + vanilla JS, persistance localStorage), comportant :

- **Côté praticien** : dossier patiente, 9 échelles validées (WAST, Danger Assessment Campbell, PCL-5, PHQ-9, GAD-7, PTCI-9, IES-R, ITQ, DES-T), CMI guidé HAS 2011, plan de sécurité, module EMDR complet (protocole 8 phases avec scripts Shapiro 2018, 4 domaines de cognitions dont Honte ajoutée par Parnell, Guide praticien intégré couvrant TAI / interweave / protocoles spécifiques R-TEP, inversé, Progressive, AF-EMDR, DeTUR / indications & contre-indications / bibliographie), module TCC (Impact Statement, stuck points CPT Resick, tableau de Beck, hiérarchie d\\\exposition Foa).
- **Côté patiente** : journal, ancrage 5-4-3-2-1, cohérence cardiaque, plan de sécurité personnel, carnet de pensées (Beck simplifié), contenus pédagogiques EMDR/TCC, accès rapide aux numéros d\\\urgence (3919, 17, 114, 3114, 119, 3018).

## Nouveautés v0.4 (mise à jour clinique EMDR)

- 4 domaines de cognitions : Responsabilité / Sécurité / Choix / **Honte** (ajout Parnell).
- EMDR_PHASES enrichi : pour chaque phase, objectif clinique + critère de passage.
- Click sur une phase = modale avec script Shapiro verbatim (phases 3, 4, 5, 6).
- Bouton **📖 Guide praticien** : modale 8 sections dépliables (TAI, 8 phases tabulaires, touchstone & accès, interweave cognitif, 4 domaines CN/CP, protocoles spécifiques, indications/CI, bibliographie complète).
- Affichage Phase courante avec bouton "Modifier la phase courante".

## Avertissements

- **Échelles** : versions paraphrasées pour démo. Production = versions officielles validées (BEH 2021, Campbell 2009, DSM-5, Cloitre 2018, Weiss & Marmar 1997, Foa 1999, Carlson & Putnam 1993).
- **Données** : la patiente "Anaïs M." est entièrement fictive.
- **Pas un dispositif médical**. Pas un substitut au soin. En cas d\\\urgence : 3919, 17, 3114.

## Sources cliniques

HAS (2007, 2025), INSERM (2015), OMS (2013), MIPROF/ONVF, Cn2r, EMDR France, IFEMDR, EMDR Europe, EMDRIA, Trauma Aid France, ISTSS, Shapiro 2018, Leeds 2016, Parnell 2013, Tarquinio & Iracane-Coste Dunod 2022, Van der Hart 2006, Gonzalez & Mosquera 2012, Van der Kolk 2014, Porges 2011, Siegel 2012, Resick (CPT), Foa (PE), Beck.
