# TP3 – Support Vector Machines (SVM)

## Présentation
Ce dépôt contient le compte-rendu du TP consacré aux **Support Vector Machines (SVM)**.  
L’objectif de ce travail est de mettre en pratique les notions vues en cours à travers plusieurs expériences de classification supervisée :  
- comparaison de noyaux (linéaire, polynômial, RBF),  
- étude sur le jeu de données *Iris*,  
- reconnaissance de visages avec le jeu de données *LFW*,  
- impact des variables de nuisance sur les performances,  
- réduction de dimension via *ACP (PCA)*,  
- exploration interactive avec une interface graphique (`svm_gui.py`).  




## Organisation du dépôt
```
├── README.md # Présentation et instructions
├── src/ # Scripts Python
│ ├── svm_script.py # Code principal du TP
│ ├── svm_source.py # Fonctions utilitaires
│ └── svm_gui.py # Interface graphique pour manipuler les SVM
├── rapport/
│ ├── TP_SVM.tex # Rapport LaTeX
│ ├── TP_SVM.pdf # Rapport compilé en PDF
  └── images # dossier contenant les images utilisées dans le rapport 
├── requirements.txt # Dépendances Python du projet
└── .gitignore # Fichiers/dossiers ignorés par Git

```
---

## Génération du rapport LaTeX

Pour compiler le fichier `TP_SVM.tex` et générer le rapport au format PDF, suivez les étapes ci-dessous :

1. **Télécharger les fichiers**  
   - Récupérez tout le contenu du dépôt :  
     - `TP_SVM.tex` : fichier LaTeX principal  
     - `images/` : dossier contenant les images utilisées dans le rapport  
     - `src/` : dossier contenant les scripts Python (optionnel pour la génération du rapport)  

2. **Créer un projet sur Overleaf**  
   - Connectez-vous sur [Overleaf](https://www.overleaf.com/)  
   - Cliquez sur **Nouveau projet → Import project**  
   - Importez tous les fichiers et dossiers nécessaires  

3. **Compiler le document**  
   - Sélectionnez `TP_SVM.tex` comme fichier principal  
   - Cliquez sur **Recompiler** pour générer le PDF  

4. **Télécharger le PDF**  
   - Une fois la compilation terminée, vous pouvez télécharger le PDF généré
  



## Auteurs

- [RADOUAN Naima](https://github.com/naimaradouan)  
- [OULEBSIR Lamia ](https://github.com/LamiaOulebsir)


