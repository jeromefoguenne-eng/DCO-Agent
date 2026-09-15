# 🎓 Agent DCO FWB — Assistant IA pour les Délégués aux Contrats d'Objectifs

[![Fédération Wallonie-Bruxelles](https://img.shields.io/badge/Enseignement-FWB-blue.svg)](https://www.enseignement.be)
[![Pacte pour un Enseignement d'excellence](https://img.shields.io/badge/Pacte-Excellence-green.svg)](https://www.pactegouvernance.be)
[![Antigravity Powered](https://img.shields.io/badge/AI-Antigravity%20Agent-purple.svg)](https://github.com/jeromefoguenne-eng/DCO-Agent)

Bienvenue sur le dépôt officiel de l'**Agent DCO FWB**, un assistant IA conçu sur-mesure pour accompagner les **Délégués aux Contrats d'Objectifs (DCO)** de la Fédération Wallonie-Bruxelles dans leurs missions d'analyse, d'évaluation et de co-pilotage des établissements scolaires.

---

## 🎯 Objectifs & Posture de l'Agent DCO

L'Agent DCO agit comme un **co-pilote stratégique, analytique et réflexif**. Il incarne et fait respecter la **Posture professionnelle du DCO** :
- 🎧 **Écoute active & Empathie** : Prise en compte du contexte de l'école (ISE) et de la réalité du terrain.
- 🤝 **Bienveillance exigeante** : Valorisation des réussites combinée à une rigueur sur l'efficacité des actions.
- 💡 **Questionnement réflexif** : Questionner de manière constructive plutôt qu'imposer des solutions.
- 🔍 **Esprit d'analyse & Esprit critique** : Diagnostic rigoureux fondé sur des données probantes.
- ⚖️ **Neutralité institutionnelle & Transparence** : Équité absolue, impartialité et règles du jeu claires.

---

## 🧰 Matrice des 10 Compétences (*Skills*) Intégrées

L'agent combine **4 compétences métier FWB** et **6 compétences techniques avancées** :

```
agent-dco-fwb/
├── skills/
│   ├── analyse-plan-pilotage/        # [Métier] Diagnostic, cohérence SMART, 5 axes du Pacte
│   ├── redaction-rapports-dco/       # [Métier] Rédaction institutionnelle (lecture, 3 ans, 6 ans)
│   ├── dialogue-posture-recherche/   # [Métier] Posture DCO, écoute, neutralité & questionnement réflexif
│   ├── banque-leviers-actions/       # [Métier] Catalogue de leviers & pistes pédagogiques
│   ├── unlimited-ocr/                # [Tech] Extraction OCR de PDF scannés et volumineux
│   ├── excel-automation/             # [Tech] Traitement des tableaux d'indicateurs FWB
│   ├── presentation-architect/       # [Tech] Génération de présentations PowerPoint
│   ├── office-productivity/          # [Tech] Mise en page officielle Word/PDF
│   ├── conseiller-pedagogique/       # [Pedagogy] Expertise technopédagogique & FWB (Hélène)
│   └── stop-slop/                    # [Quality] Élimination du jargon IA & ton administratif pur
```

---

## 📚 Base de Connaissances (*Knowledge Base*)

L'agent s'appuie sur un dossier `knowledge/` contenant la législation et les guides de référence FWB :

- **`01-legislation-decrets/`** : Décret du 13 septembre 2018 (Contrats d'objectifs et pilotage), Pacte d'Excellence (Avis n°3).
- **`02-circulaires-fwb/`** : Directives AGFE et guides méthodologiques de l'Inspection.
- **`03-indicateurs-et-statistiques/`** : Notice d'interprétation des indicateurs FWB et des indices socio-économiques (ISE N1-N20).
- **`04-trames-et-grilles-officielles/`** : Modèles réglementaires de rapports de lecture, d'évaluation intermédiaire et finale.
- **`05-glossaire-institutionnel-fwb.md`** : Définition des termes et sigles FWB (PO, CE, CoPS, AGERS, WBE, EAL, DCO...).
- **`06-posture-et-deontologie-dco.md`** : Charte de la posture DCO (Écoute, bienveillance, transparence, esprit d'analyse et critique, neutralité).

---

## 🚀 Utilisation lors de la Formation

### 1. Installation pour Antigravity / Agentic IDE
1. Cloner ce repository :
   ```bash
   git clone https://github.com/jeromefoguenne-eng/DCO-Agent.git
   ```
2. Ouvrir le dossier dans votre environnement de travail Antigravity / Gemini CLI.
3. L'agent détectera automatiquement le prompt système `AGENT_INSTRUCTIONS.md`, la base de connaissance dans `knowledge/` et l'ensemble des compétences dans `skills/`.

### 2. Exemples de Prompts pour la Formation
- **Analyse d'un Plan de Pilotage avec Esprit Critique** :
  > *"Analyse le plan de pilotage ci-joint. Garde un esprit critique sur la faisabilité de l'action 2 et propose un diagnostic neutre basé sur les faits."*
- **Préparation de réunion avec Questionnement Réflexif** :
  > *"Je rencontre le Chef d'Établissement. Prépare-moi 7 questions réflexives bienveillantes mais exigeantes pour l'amener à réévaluer ses objectifs d'échec scolaire."*

---

## 🔒 Confidentialité & RGPD

> [!IMPORTANT]
> **Règle absolue No-PII (Données à caractère personnel)** : Ne chargez jamais dans l'agent des données identifiantes d'élèves, de parents ou d'enseignants. Anonymisez toujours les documents d'école avant traitement.

---

## 📄 Licence & Crédits

- **Conception & Ingénierie Pédagogique** : Jérôme Foguenne (Formation IA DCO FWB)
- **Cadre Réglementaire & Charte de Posture** : Fédération Wallonie-Bruxelles (Décret Pilotage 2018 / Pacte pour un Enseignement d'excellence)
- **Licence** : MIT — Usage libre pour les acteurs éducatifs FWB.
