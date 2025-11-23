# Dashboard Production Industrielle - Premier Projet Power BI

## Contexte

**Type** : Projet pédagogique - Formation Data Analyst BI  
**Période** : Semaines 2 (Novembre 2025) 
**Objectif** : Maîtriser connexion Power BI ↔ PostgreSQL et modélisation relationnelle  
**Temps de réalisation** : ~13 heures (apprentissage + projet)

**Note** : Deuxième projet formation - Focus sur SQL avancé et relations entre tables.

---

## Architecture Technique

### Base de Données PostgreSQL

**Table 1 : production** (Données quotidiennes)
- 21 lignes (3 lignes × 7 jours)
- Colonnes : id, ligne, date, produits, rebuts

**Table 2 : lignes** (Référentiel)
- 3 lignes (A, B, C)
- Colonnes : id, nom, capacite_max, localisation, responsable

**Relation** : `production.ligne` → `lignes.nom` (many-to-one)

### Power BI

**Import** :
- Connexion PostgreSQL
- Mode : Import

---

## KPIs et Métriques

### Indicateurs Globaux
- **Production totale** : 22 155 unités
- **Capacité totale** : 4 000 unités/jour
- **Taux d'utilisation global** : 88%
- **Taux rebut moyen** : 3,0%

---

## Insights Business

### Points Clés

1. **Ligne C : Goulet d'étranglement**
   - Taux utilisation : 92% (le plus élevé)
   - Marge faible : 98 unités/jour
   - **Risque** : Peu de flexibilité en cas de pic de demande

2. **Ligne A & B : Sous-utilisées**
   - Taux utilisation : < 86%
   - Marge : 387 unités/jour
   - **Opportunité** : Réallocation charge possible

3. **Performance stable**
   - Taux rebut constant ~3% (acceptable)
   - Pas de variations anormales dans le temps

### Recommandations

➡️ **Rééquilibrer charge** : Transférer production de Ligne C vers Ligne A & B 

---

## 📸 Aperçu Dashboard

### Vue d'Ensemble
![Dashboard Overview](Portfolio Data Analysis S2/Screenshots/dashboard_sql_overview.png)

---

**Visualisation** :
- 7 mesures DAX
- 5 KPI cards
- Graphiques barres groupées
- Graphique évolution temporelle
- 3 Jauges de taux d'utilisation
- 2 slicers interactifs

---

## Auteur

**Bastien M**  
Ingénieur Chef de Projet avec spécialisation en cours de Data Analyst  

---

## Licence

Projet pédagogique à but non commercial.  
Données fictives créées pour l'apprentissage.

---

*Projet réalisé en Novembre 2025 - Formation Data Analyst Mois 1*


```
