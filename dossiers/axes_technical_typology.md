# 🛠️ TYPOLOGIE TECHNIQUE DES 30 AXES FSUCIETÀ
## *Répartition des Outillages : Géospatial (Satellites), Financier (Registres & Graphes) et Statistique (Économétrie)*

---

## 🛰️ FAMILLE A : AXES GÉOSPATIAUX & SATELLITAIRES (Imagerie SIG / Radar Nécessaire)

> **Principe** : Ces dossiers nécessitent de prouver une **altération physique du sol**, une emprise foncière non déclarée ou une modification environnementale visible depuis l'espace.

* **Outils Utilisés** : Satellites ESA Copernicus Sentinel-2 (Indice Optique NDVI/NDWI), Radar Sentinel-1 SAR (excavation), Cartographie Cadastrale IGN, Polygon Overlay SIG.
* **Les Axes Concernés** :
  * 🌲 **Axe 06 (Privatisation du Maquis)** : Défrichage illégal et ouvertures de pistes en zone protégée.
  * 🌾 **Axe 10 (Fraude Subventions PAC)** : Décalage entre les parcelles agricoles déclarées et l'occupation réelle du sol.
  * 💧 **Axe 19 (Capture Ressource en Eau)** : Indice d'humidité NDWI mesurant l'arrosage illégal de golfs/resorts en période d'arrêté sécheresse.
  * ⛏️ **Axe 21 (Monopoles Carrières & Granulats)** : Analyse de la surface d'excavation des carrières hors du périmètre autorisé DREAL.
  * 🏖️ **Axe 29 (Concessions Marinas & DPM)** : Emprise des installations privées sur le Domaine Public Maritime.

---

## 🗄️ FAMILLE B : AXES FINANCIERS & JURIDIQUES (Imagerie Inutile — Registres & Graphes)

> **Principe** : Ces dossiers reposent sur des **flux de capitaux**, des réseaux de sociétés écrans, des arbitrages fiscaux et des ententes sur marchés publics. L'imagerie géographique y est inutile ; l'outil maître est le **Graph Solver et l'analyse de registres**.

* **Outils Utilisés** : Registre des Bénéficiaires Effectifs (INPI RBE), Liasses Fiscales DGFiP, Graph Solvers NetworkX (nœuds d'actionnariat), Base SIRENE INSEE, BODACC.
* **Les Axes Concernés** :
  * 🏦 **Axe 01 (Arbitrage Crédit Impôt CIIC)** : Montages holdings et déduction fiscale Art. 244 quater E.
  * 💸 **Axe 02 (Fuite de Capitaux Bancaires)** : Modélisation des flux de refinancement bancaires (CMF L561-2).
  * 🏗️ **Axe 03 (Cartels Marchés Publics BTP)** : Détection des ententes entre entreprises candidates (BOAMP / INFOGREFFE).
  * ⚖️ **Axe 04 (Impunité Professionnels du Droit)** : Rapprochement entre gérants de SCI, notaires et montages offshores.
  * 🇪🇺 **Axe 08 (Fraude Subventions EPPO FEDER)** : Croisement des attributions de fonds européens avec les projets exécutés.

---

## 📈 FAMILLE C : AXES SOCIO-ÉCONOMIQUES & STATISTIQUES (Modélisation Économétrique)

> **Principe** : Ces dossiers analysent des **tendances de prix, la désertification des services publics et des ruptures d'équité**. L'outil principal est le traitement de séries temporelles (Pandas) et la modélisation spatiale d'accès au soin (Isochrones).

* **Outils Utilisés** : Séries temporelles DVF/INSEE, modèles d'isochrones de temps de trajet (SAMU/Médecins), scrapers de tarifs maritimes/aériens, réindexation DGF.
* **Les Axes Concernés** :
  * 🏡 **Axe 05 (Éviction Démographique)** : Modélisation de l'écart entre le prix au m² (DVF) et le revenu moyen des ménages résidents.
  * 🚢 **Axe 11 (Chantage DSP Maritime)** : Reconstitution de la grille tarifaire du fret et calcul des surcoûts insulaires.
  * 🏥 **Axe 16 (Étranglement Hospitalier T2A)** : Comparaison des tarifs d'activité hospitalière ATIH / ARS.
  * 🚑 **Axe 22 (Désertification Médicale ARS)** : Calcul de la carte des isochrones (temps d'accès aux urgences en minutes).
  * 📡 **Axe 24 (Fracture Numérique THD)** : Croisement des cartes ARCEP du réseau fibre avec la densité rurale.

---

> **RÉSUMÉ**  
> L'écosystème FSUCIETÀ déploie **l'outil juste pour l'axe juste**, évitant toute surcharge inutile et garantissant une crédibilité scientifique irréprochable.
