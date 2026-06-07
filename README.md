# Segmentation et Scoring de Risque Bancaire

## Contexte
Système de segmentation client par Machine Learning appliqué
au dataset UCI Credit Card (30 000 clients, 24 variables).

## Méthodologie
1. Preprocessing & Feature Engineering (5 variables dérivées)
2. Comparaison K-Means direct vs ACP + K-Means (retenu : ACP, Silhouette 0.2753)
3. Scoring de risque pondéré (0 à 100)
4. Dashboard Power BI

## Résultats
| Profil | Clients | Taux de défaut |
|--------|---------|----------------|
| Premium | 10 685 | 12% |
| Standard | 12 509 | 17% |
| Gros utilisateur sain | 3 188 | 16% |
| Risque critique | 3 618 | 61% |

## Stack technique
Python · Pandas · Scikit-learn · Matplotlib · Seaborn · Power BI

## Lancer le projet
pip install -r requirements.txt
