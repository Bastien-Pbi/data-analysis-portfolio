# Dashboard Production Industrielle - Premier Projet Power BI

## Contexte

**Type** : Projet pédagogique - Formation Data Analyst BI  
**Période** : Semaines 1 (Octobre 2025) 
**Objectif** : Maîtriser les fondamentaux Power BI
**Temps de réalisation** : ~15 heures (apprentissage + projet)

**Note** : Premier projet Power BI réalisé dans le cadre de ma formation. Focus sur les concepts fondamentaux.

---

## Objectif du Projet

Créer un dashboard interactif pour visualiser et analyser les données de production de 3 lignes industrielles (A, B, C) sur une période de 5 jours.

**Questions business** :
- Quelle ligne est la plus performante ?
- Quel est le taux de rebut moyen ?
- Comment évolue la production dans le temps ?
- Y a-t-il des différences entre shifts (Matin/Soir) ?

---

## Technologies Utilisées

### Power BI
- **Power BI Desktop** : Création dashboards et visuels
- **Power Query** : Transformation et nettoyage données
- **DAX** : Calculs et mesures personnalisées

---

## Données

**Source** : Dataset fictif créé pour la formation

**Structure** :
- **15 lignes** de données
- **Colonnes** : Ligne, Date, Produits, Rebuts, Shift, Responsable
- **Période** : 14-18 janvier 2025
- **3 lignes** de production : A, B, C

**Volume** :
- Production totale : 17 670 unités
- Taux rebut moyen : 3,0%

---

## KPIs Suivis

### Indicateurs Principaux
- **Production Totale** 
- **Production Moyenne**
- **Total Rebuts**
- **Taux Rebut Moyen**
- **Nombre de jours**

### Analyses
- Production par ligne (A, B, C)
- Évolution temporelle (tendances)
- Répartition par shift (Matin/Soir)

---

## Dashboard - Aperçu

### Page Unique : Vue d'Ensemble

**Composants** :
- 5 cartes KPI en haut (métriques clés)
- Graphique barres : Production par ligne
- Graphique lignes : Évolution temporelle
- Graphique secteurs : Répartition par shift
- 3 Slicers interactifs : Date, Ligne, Shift

![Dashboard Screenshot](screenshots/dashboard_sql.png)

---

## Structure du Repository
```
Dashboard_Production_S1S2/
├── README.md (ce fichier)
├── screenshots/
│   └── dashboard_overview.png
│   └── dashboard_focus ligne A.png
│   └── dashboard_Shift Matin.png
├── data/
│   └── production_data.xlsx
```

*Note : Le fichier .pbix (Power BI) n'est pas uploadé car trop volumineux pour GitHub*

---

## Améliorations Futures Possibles

Ce projet pourrait être enrichi avec :

- [ ] Connexion directe Power BI ↔ PostgreSQL (au lieu d'Excel)
- [ ] Relations entre plusieurs tables (lignes, responsables, shifts)
- [ ] Mesures DAX avancées (Time Intelligence : YTD, MoM)
- [ ] Page supplémentaire : Analyse détaillée par responsable
- [ ] Tooltips personnalisés sur visuels
- [ ] Thème Power BI personnalisé
- [ ] Actualisation automatique données

---

## Auteur

**Bastien M**  
Ingénieur Chef de Projet avec spécialisation en cours de Data Analyst  

---

## Licence

Projet pédagogique à but non commercial.  
Données fictives créées pour l'apprentissage.

---

*Projet réalisé en Octobre 2025 - Formation Data Analyst Mois 1*

```
