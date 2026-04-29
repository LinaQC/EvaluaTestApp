[README.txt](https://github.com/user-attachments/files/27206408/README.txt)
# Projet QA : Validation de l'application EvaluaTest (ISTQB CTFL V4.0)

Ce dépôt contient la documentation complète d'une campagne de test logiciel réalisée dans le cadre de la certification ISTQB CTFL V4.0. Le projet porte sur l'application web **EvaluaTest**, un système de simulation d'examen QCM.

## 👤 Auteur
* **Lina LEGHRARI**


---

## 📋 Résumé du projet
L'objectif était de valider la conformité fonctionnelle et non fonctionnelle de l'application **EvaluaTest**. Ce projet couvre l'intégralité du cycle de vie des tests (STLC), depuis l'analyse des besoins (SRS) jusqu'à la synthèse finale.

### Points forts de la campagne
* **Approche structurée :** Utilisation des techniques ISTQB (Partition d'équivalence, Analyse des valeurs limites).
* **Rigueur QA :** Identification d'anomalies critiques empêchant la mise en production.
* **Décision finale :** **NO GO** (Justifié par des risques de fiabilité sur le calcul des scores).

---

## 📂 Accès aux livrables
*Les documents sont disponibles dans le dossier `/docs`.*

| Document | Description | Format |
| :--- | :--- | :--- |
| **SRS** | Software Requirements Specification | [Google Doc](https://docs.google.com/document/d/1U4sXyXHfKC3fbyVFukPROErrV7XZG-tkyhsolJ3Rt5o/edit?tab=t.0#heading=h.1k06sn1ey1qu) |
| **Plan de Test** | Stratégie, couverture et ressources | [PDF](docs/Plan_de_test_strategie.pdf) |
| **Cas de Test** | Scénarios fonctionnels & non-fonctionnels | [XLSX](docs/Cas_de_test.xlsx) |
| **Rapport d'exécution** | Suivi et résultats des tests | [PDF](docs/Rapport_execution.pdf) |
| **Rapports de bugs** | Analyse détaillée (Tableau) | [CSV](docs/Rapports_de_bugs.csv) |
| **TSR** | Test Summary Report | [PDF](docs/Test_Summary_Report.pdf) |

---

## 🐞 Synthèse des anomalies et preuves
La campagne a révélé des anomalies critiques. Vous trouverez ci-dessous le lien vers les captures d'écran (format PDF) pour chaque bug.

| ID | Titre | Sévérité | Preuve visuelle (PDF) |
| :--- | :--- | :--- | :--- |
| **BUG-001** | Questions dupliquées | Majeure | [Voir preuve](docs/preuves/BUG-001.pdf) |
| **BUG-002** | Réponse incorrecte évaluée correcte | Majeure | [Voir preuve](docs/preuves/BUG-002.pdf) |
| **BUG-003** | Énoncé identique aux réponses | Majeure | [Voir preuve](docs/preuves/BUG-003.pdf) |



---

## 🛠 Outils utilisés
* **Méthodologie :** ISTQB CTFL V4.0
* **Gestion :** Excel, Google Drive
* **Environnement :** Windows 10, Chrome & Firefox

---
*Projet réalisé à des fins de certification professionnelle.*
