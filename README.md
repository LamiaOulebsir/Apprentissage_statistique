# TP – Support Vector Machines (SVM)

## Présentation
Ce dépôt contient le compte-rendu du TP consacré aux **Support Vector Machines (SVM)**.  
L’objectif de ce travail est de mettre en pratique les notions vues en cours à travers plusieurs expériences de classification supervisée :  
- comparaison de noyaux (linéaire, polynômial, RBF),  
- étude sur le jeu de données *Iris*,  
- reconnaissance de visages avec le jeu de données *LFW*,  
- impact des variables de nuisance sur les performances,  
- réduction de dimension via **ACP (PCA)**,  
- exploration interactive avec une interface graphique (`svm_gui.py`).  



## Organisation du dépôt

├── README.md # Présentation et instructions
├── src/ # Scripts Python
│ ├── svm_script.py # Code principal du TP
│ ├── svm_source.py # Fonctions utilitaires
│ └── svm_gui.py # Interface graphique pour manipuler les SVM
├── rapport/
│ ├── TP_ML_SVM.tex # Rapport LaTeX
│ └── TP_ML_SVM.pdf # Rapport compilé en PDF
└── .gitignore # Fichiers/dossiers ignorés par Git


---

## Génération du rapport sur Overleaf

1. **Téléchargement des fichiers**  
   - Récupérez tout le contenu du dépôt : `tp.tex`, `image/`, `src/(si vous souhaitez les exécuter pour reproduire les résultats)` et `requirements.txt`.

2. **Création du projet sur Overleaf**  
   - Connectez-vous sur [Overleaf](https://www.overleaf.com/)  
   - Cliquez sur **Nouveau projet → Import project** et importez les fichiers  

3. **Compilation du document**  
   - Sélectionnez `tp.tex` comme fichier principal  
   - Cliquez sur **Recompiler** pour générer le PDF  

4. **Téléchargement du PDF**  
   - Une fois la compilation terminée, vous pouvez télécharger le PDF généré  

