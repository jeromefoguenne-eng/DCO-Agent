---
name: token-optimization
description: Optimisation de la dépense de tokens, compression de contexte (RTK/Caveman), élagage documentaire et routage économique des requêtes IA.
---

# Compétence : Optimisation des Tokens & Éco-Conception IA (`omniroute-manager`)

## But
Réduire de 30% à 80% la consommation de tokens et les coûts d'API lors de l'analyse de volumineux Plans de Pilotage, circulaires et rapports d'évaluation, tout en augmentant la vitesse de réponse de l'Agent DCO.

---

## 🛠️ Techniques d'Optimisation des Tokens

### 1. Élagage et Extraction Ciblée (Document Trimming)
Lorsqu'un Plan de Pilotage ou un document de 30+ pages est soumis à l'agent :
- **Ne pas charger l'intégralité du texte brut** si une seule section est analysée.
- **Extraire uniquement les sections pertinentes** (ex: isoler l'Axe 1 et l'Axe 2 pour l'évaluation des savoirs fondamentaux).
- Utiliser la compétence `unlimited-ocr` pour convertir le document en Markdown structuré avant d'injecter uniquement la sous-partie utile.

### 2. Compression de Contexte (RTK & Caveman via OmniRoute)
- Exploiter la passerelle locale **OmniRoute** (`http://localhost:20128`) si disponible.
- Activer la compression de prompt **RTK (Real-Time Knowledge compression)** pour éliminer les redondances dans les sorties d'outils et les pièces jointes longues (gain de 15% à 95% de tokens).
- Privilégier les modèles ou combos virtuels économiques (`auto/best-free` ou `auto/cheap`).

### 3. Réponses Synthétiques & Zéro-Verbosité Inutile
- Éliminer les formules de politesse répétitives ou les récapitulatifs verbeux.
- Formater les synthèses de lecture en tableaux Markdown denses et en listes à puces concises.
- Appliquer la compétence `stop-slop` pour supprimer les bavardages IA non indispensables.

---

## 💡 Impact pour la Formation et l'Usage DCO
- **Rapidité d'exécution** : Des réponses 2 à 3 fois plus rapides pour les DCO lors des séances de formation.
- **Réduction des coûts** : Préservation des quotas gratuits et prévention des erreurs 429 (*Rate Limit*).
