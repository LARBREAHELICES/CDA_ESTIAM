# Structure du tableau de bord étudiant – Titre CDA Niveau 6

### 🗂 Feuille 1 : *Suivi des compétences professionnelles*

| **Bloc / Activité Type**                                                                     | **Compétence Professionnelle**                                 | **Description synthétique**                                      | **% d’avancement** | **Date de début** | **Date de validation** | **Formateur valideur** | **Commentaires / Actions à mener**                     |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------ | ----------------- | ---------------------- | ---------------------- | ------------------------------------------------------ |
| **Activité Type 1 : Développer une application sécurisée**                                   | Installer et configurer son environnement de travail           | Installation IDE, Git, conteneurs, base locale, conformité ANSSI | 80 %               | 15/09/2025        | 10/10/2025             | —                      | Vérifier doc technique et cohérence Docker             |
|                                                                                              | Développer des interfaces utilisateur                          | Interfaces sécurisées et accessibles (RGAA)                      | 60 %               | 01/10/2025        | —                      | —                      | Ajouter tests unitaires et validations des formulaires |
|                                                                                              | Développer des composants métier                               | Logique applicative sécurisée et testée                          | 40 %               | 01/11/2025        | —                      | —                      | Prévoir refactoring selon normes POO                   |
|                                                                                              | Contribuer à la gestion d’un projet informatique               | Planification, suivi, compte rendu                               | 75 %               | 01/09/2025        | 30/11/2025             | —                      | Compléter le reporting Agile                           |
| **Activité Type 2 : Concevoir et développer une application sécurisée organisée en couches** | Analyser les besoins et maquetter une application              | Cahier des charges, maquettes, dossiers de conception            | 50 %               | 01/12/2025        | —                      | —                      | Revoir maquettes UX/UI                                 |
|                                                                                              | Définir l’architecture logicielle d’une application            | Architecture multicouche, sécurité, eco-conception               | 25 %               | 15/12/2025        | —                      | —                      | Préparer dossier technique                             |
|                                                                                              | Concevoir et mettre en place une base de données relationnelle | Modélisation, scripts SQL, sécurité                              | 60 %               | 15/01/2026        | —                      | —                      | Tester sauvegarde/restauration                         |
|                                                                                              | Développer des composants d’accès aux données SQL et NoSQL     | ORM, accès sécurisés, tests                                      | 30 %               | 01/02/2026        | —                      | —                      | Préparer tests de sécurité et intégrité                |
| **Activité Type 3 : Préparer le déploiement d’une application sécurisée**                    | Préparer et exécuter les plans de tests d’une application      | Tests intégration, sécurité, non-régression                      | 20 %               | 01/04/2026        | —                      | —                      | Définir plan de tests automatisés                      |
|                                                                                              | Préparer et documenter le déploiement d’une application        | Scripts de déploiement, procédures CI/CD                         | 10 %               | 01/05/2026        | —                      | —                      | Créer documentation technique                          |
|                                                                                              | Contribuer à la mise en production dans une démarche DevOps    | CI/CD, qualité du code, automatisation                           | 0 %                | 01/06/2026        | —                      | —                      | Pipeline à créer sur GitLab                            |
| **Compétences transversales**                                                                | Communiquer en français et en anglais                          | Communication technique B1/A2                                    | 50 %               | 01/09/2025        | —                      | —                      | Rédiger documentation bilingue                         |
|                                                                                              | Mettre en œuvre une démarche de résolution de problème         | Diagnostic et solution technique structurée                      | 70 %               | 01/09/2025        | —                      | —                      | Journal de résolution à compléter                      |
|                                                                                              | Apprendre en continu (veille, documentation)                   | Veille technologique, éco-conception                             | 40 %               | 01/09/2025        | —                      | —                      | Ajouter sources de veille                              |

---

### 📊 Dash (accueil) : *Synthèse de progression automatique*

| **Activité Type**         | **Nb de compétences** | **% moyen d’avancement** | **Date moyenne de validation** | **Statut global**            |
| ------------------------- | --------------------- | ------------------------ | ------------------------------ | ---------------------------- |
| Activité Type 1           | 4                     | 64 %                     | 15/12/2025                     | En cours                     |
| Activité Type 2           | 4                     | 41 %                     | —                              | À poursuivre                 |
| Activité Type 3           | 3                     | 10 %                     | —                              | Non entamé                   |
| Compétences transversales | 3                     | 53 %                     | —                              | En développement             |
| **Total global**          | **14**                | **42 %**                 | —                              | **Formation en progression** |

---

### ⚙️ Recommandations de mise en forme (Excel / Sheets)

* Colonnes **% d’avancement** avec barres de progression (mise en forme conditionnelle).
* Colonne **Statut global** colorée automatiquement :

  * 🟩 *Validée* si 100 %
  * 🟨 *En cours* si 30–99 %
  * 🟥 *Non entamée* si 0 %
* Formule moyenne automatique du % par activité type.
* Saisie automatique de la **date de validation** à partir de la case “% = 100”.
* Graphique radar ou jauge pour visualiser la progression globale.
