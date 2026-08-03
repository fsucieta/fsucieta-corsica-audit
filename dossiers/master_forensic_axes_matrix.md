# 📊 FSUCIETÀ 2.0 — MATRICE MAÎTRESSE DES 30 AXES D'INVESTIGATION
## *Cartographie des Données Publiques, Sources Officielle & Outils Techniques OSINT*

---

> **RAPPEL MÉTHODOLOGIQUE**  
> Chaque axe d'investigation FSUCIETÀ repose sur **trois garanties** :  
> 1. **Zéro Rumeur** : 100% de provenance publique officielle (Ministère des Finances, INPI, Union Européenne, Agence Spatiale Européenne).  
> 2. **Reproductibilité Code** : Traitement par des scripts Python open-source auditables.  
> 3. **Validation Légale** : Citation explicite des articles de loi et codes juridiques applicables.

---

## 🏛️ VOLUME 1 : AXES 01 À 10 (Foncier, Finance & Infiltration Économique)

| N° | Intitulé de l'Axe | Source de Données Officielle | Référence Légale / Cadre | Outil OSINT & Script Dédié |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **Arbitrage Crédit Impôt CIIC** | DGFiP DVF (Demande de Valeurs Foncières) & Liasses Fiscales | CGI Art. 244 quater E | `dvf_cadastre_analyzer.py` & SQLite `cadastre_dvf` |
| **02** | **Fuite de Capitaux Bancaires** | Banque de France, Registre CMF & Signalements TRACFIN | CMF Art. L561-2 | `inpi_rbe_corporate_network_tracker.py` |
| **03** | **Cartels Marchés Publics BTP** | BOAMP, Marchés-Publics.info & Fichiers INFOGREFFE | Code Commande Publique L2141-1 | SQL Join Scraper & Cross-referencer SIREN |
| **04** | **Impunité Professionnels Droit** | Registre National des Notaires & INPI RBE | Code du Notariat & CGI | Graph Solver de Rapprochement SCI / Offshores |
| **05** | **Éviction Démographique** | Recensement INSEE, DVF (+120% prix/m²) & CAF | Loi Littoral & Code Urbanisme | GeoJSON Spatial Polygon Overlay & Pandas Trend |
| **06** | **Privatisation du Maquis** | Cadastre IGN, ONF & Notices Foncières SAFER | Code Forestier Art. L241-1 | `copernicus_esa_satellite_monitor.py` (Sentinel-2) |
| **07** | **Déséquilibre Transport Saisonniers**| Flux Passagers Ports & Aéroports (BdD Transport) | Code des Transports L1231-1 | Time-series Seasonality Spectrum Parser |
| **08** | **Fraude Subventions EPPO FEDER** | Parquet Européen (EPPO) & Base Synergie FEDER | Règlement UE 2021/1060 | EU Subsidy Grant Cross-Checker Script |
| **09** | **Infiltration Sécurité Privée** | Fichier National CNAPS & Base SIRENE INSEE | Code Sécurité Intérieure L612-1 | License Cross-matcher & Background Verify |
| **10** | **Fraude Subventions PAC** | Registre TelePAC & Agence de Paiement ASP | Règlement PAC UE 2021/2115 | Satellite Parcel Polygon Overlay vs Declared Acreage |

---

## 🌊 VOLUME 2 : AXES 11 À 20 (Infrastructures, Énergie & Services Publics)

| N° | Intitulé de l'Axe | Source de Données Officielle | Référence Légale / Cadre | Outil OSINT & Script Dédié |
| :--- | :--- | :--- | :--- | :--- |
| **11** | **Chantage DSP Maritime** | Délibérations Assemblée de Corse & Rapports DSP | CGCT Art. L1411-1 | Ferry Tariff Scraper & Subsidy Audit Engine |
| **12** | **Rente Énergétique ZNI CSPE** | CRE (Commission Régulation Énergie) & EDF SEI | Code de l'Énergie L121-7 | CSPE Surcharge Calculation Engine |
| **13** | **Racket TGAP & Crise Déchets** | ADEME, SYVADEC & Registres TGAP Douanes | CGI Art. 266 sexies | Waste Tonnage & TGAP Tax Calculator |
| **14** | **Exclusion Numérique Marchés** | Plateformes Régionales Open Data & APIs Publiques | Code Commande Publique L2120-1 | `bufitonu_platform_connector.py` |
| **15** | **Dépopulation Rurale DGF** | DGCL (Dotation Globale de Fonctionnement) & INSEE | CGCT Art. L2334-1 | DGF Formula Re-indexer & Rural Variance Model |
| **16** | **Étranglement Hospitalier T2A** | ARS (Agence Régionale Santé) & Données ATIH | Code Santé Publique L6111-1 | Hospital T2A Activity-based Pricing Analyzer |
| **17** | **Fuite des Cerveaux Jeunes** | Parcoursup, Registres CAPES Éducation Nationale | Code de l'Éducation L612-3 | Youth Mobility & Brain Drain Flow Mapper |
| **18** | **Monopoles Aconage Portuaire** | Grand Port Maritime & Registres Douaniers | Code des Ports Maritimes L531-1 | Freight Concession Tariff Monitor |
| **19** | **Capture Ressource en Eau** | Agence de l'Eau & Arrêtés Préfectoraux Sécheresse | Code de l'Environnement L214-1 | Copernicus NDWI Water Index Satellite Monitor |
| **20** | **Verrouillage Logement Social** | OHC (Office Habitat de la Corse) & Demandes HLM | Code Construction & Habitation | Social Housing Applicant Wait-list Auditor |

---

## 🌄 VOLUME 3 : AXES 21 À 30 (Ressources Naturelles, Patrimoine & Économie Rurale)

| N° | Intitulé de l'Axe | Source de Données Officielle | Référence Légale / Cadre | Outil OSINT & Script Dédié |
| :--- | :--- | :--- | :--- | :--- |
| **21** | **Monopoles Carrières & Granulats**| DREAL ICPE (Installations Classées) & Mercuriales | Code de l'Environnement L511-1 | Spatial Quarry Excavation Footprint (Radar SAR) |
| **22** | **Désertification Médicale ARS** | Annuaire Santé ARS & Délais d'Intervention SAMU | Code Santé Publique L1431-1 | Isochrone Driving-Time GIS Map Generator |
| **23** | **Refus Crédit Économie Sociale** | Banque de France ESS & Registres Coopératifs | Code Monétaire et Financier | Banking Credit Refusal Variance Model |
| **24** | **Fracture Numérique THD** | ARCEP (Couverture Fibre) & Projet THD Corse | Code Postes & Comms Électroniques | Fiber Coverage vs Rural Commune GIS Overlay |
| **25** | **Spéculation Droits AOP Viticoles**| INAO (Droits de Plantation) & Douanes CVI | Code Rural Art. L642-1 | Vineyard Parcel Ownership & Droits Mapper |
| **26** | **Abandon Service Postal Rural** | Contrat de Présence Postale La Poste & ARCEP | Code Postes & Comms Électroniques | Rural Distance-to-Service Metric Engine |
| **27** | **Usucapion & Capture Indivision** | Titres Notariés, Jugements Tribunal & Cadastre Nap. | Code Civil Art. 2258 (Usucapion) | Land Genealogy & Indivision Graph Solver |
| **28** | **Dégradation Routière Poids Lourds**| Budgets Voirie Collectivité de Corse & Trafic Poids Lourds | Code de la Route L110-1 | Road Degradation Cost Attribution Model |
| **29** | **Concessions Marinas Yachting** | DDTM (Concessions AOT Domaine Public Maritime) | Code Général Propriété Personnes Pub. | Yacht AIS Tracking vs Port Fee Receipts Matcher |
| **30** | **Séquestration Patrimoine Musées** | Base Joconde Ministère Culture & Musées de Corse | Code du Patrimoine L410-1 | Heritage Artifact Provenance & Catalog Audit |

---

> **CONCLUSION**  
> Tous les outils mentionnés ci-dessus sont regroupés dans le dossier `osint_tools/` du dépôt GitHub maître :  
> 👉 [github_repository_master_pack/osint_tools/](file:///C:/Users/PC-Bureau/Desktop/docucu/github_repository_master_pack/osint_tools/)
