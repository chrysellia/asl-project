python -m venv venv
venv\Scripts\activate
pip install jupyterlab
jupyter-lab

## Description
Mini-Projet : Analyse Sémantique Latente (LSA)

Objectif :
Réaliser une analyse sémantique latente (LSA) sur un petit corpus de documents (ex : extraits d’articles Wikipédia) pour identifier les thèmes dominants et comprendre la structure sémantique cachée du corpus.

## Instructions
Tâches principales :
1. Construire une matrice terme-document :
   - Extraire un ensemble de textes (corpus court).
   - Nettoyer les données textuelles (tokenisation, suppression des mots vides, etc.).
   - Calculer la matrice TF-IDF (Term Frequency - Inverse Document Frequency).

2. Appliquer la Décomposition en Valeurs Singulières (SVD) :
   - Utiliser la SVD sur la matrice TF-IDF.
   - Extraire les thèmes dominants à partir des composantes principales.

3. Interpréter les vecteurs latents :
   - Identifier les termes les plus représentatifs dans chaque composante.
   - Étiqueter les thèmes en fonction de ces termes.

Tâche avancée (optionnelle) :
- Comparer votre implémentation LSA avec une décomposition SVD via SciPy :
  - Utiliser la fonction scipy.linalg.svd pour générer une autre décomposition.
  - Comparer les vecteurs obtenus afin de valider les résultats.

Contraintes :
- Seules les bibliothèques autorisées pour cette tâche sont celles de traitement de texte classiques (comme Numpy, Scikit-learn) et SciPy pour la comparaison.
- Présentez les résultats dans un format lisible (ex : tableau de thèmes, mots-clés par thème, etc.).
- Soyez capable de justifier chaque étape de traitement (prétraitement, choix de k, etc.).

Livrables attendus :
- Code Python commenté
- Rapport expliquant les étapes suivies et les interprétations
- Résultats obtenus

Bibliothèques autorisées :
- Scikit-learn (pour TF-IDF et SVD)
- SciPy (uniquement pour comparaison avec votre SVD)

## Noms des membres
- CHRYSOSTOME Priscillia (M1 en MSI)
- SOLOFONIAINA Anjara Mirindra (M1 en I2AD)

## lien vers rapport et slides
- Rapport du projet (PDF): (./report/Rapport-asl.pdf)
- Slides de présentation : (./presentation_LSA.pdf)