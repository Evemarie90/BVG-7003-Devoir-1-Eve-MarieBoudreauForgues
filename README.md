# BVG-7003-Devoir-1-Eve-MarieBoudreauForgues


🧰 📝 🖌️**Raison d'utilisation** : Ce script a été développé afin de permettre l'identification de gènes spécifiques à partir d'un jeu de données de transcriptomiques. Plus précisément il peut être utiliser pour identifier des marqueurs génétiques pouvent être utilisés dans un test visant à determiner le sexe des plantes. À titre d'exemple, il pourrait permettre d'isoler les données d'expression pour des gènes spécifiques REM16 (ids loci: LOC115699937) et FT1 (ids loci: LOC115696989) au sein d'un jeu de données transcriptominques de la plante Cannabis Sativa. 

🧬 🧬 🧬**Données d'entrée** Les données de transcriptomnique doivent représentés l'expréssion génique normalisés des plantes analysées. La première colonne du fichier qui sera soumis à ce script doit contenir les IDS des gènes, alors que la première ligns contient les noms des échantillions suivi du sexe des plantes. 


📊 📊 📊 **Résultats du script :** Ce script R effectue en premier l'analyse des données de transcriptomique en visant à isoler l'expression des gènes REM16 et FT1. Le script permet aussi de produire trois graphiques :
- Un graphique montrant les niveaux d'expression de REM16 regroupés par sexe (mâle vs femelle).
- Un graphique montrant les niveaux d'expression de FT1 regroupés par sexe (mâle vs femelle).
- Un graphique combiné (REM16 et FT1) montrant les niveaux d'expression des deux gènes pour comparer leur expression globale. 

🧮 🧮 🧮**Procédure et instructions**

Avant de débuter, assurez vous d'avoir une version à jour de l'application R studio ainsi que d'avoir téléchargé les packages suivant :

- ggplot2
- knitr

1. Téléchargez ou copiez le script Rmarkdown directement dans votre application Rstudio
2. Enregistrer le jeu de données en exemple : 2_Data_RNASeq_Cannabis_Sex.csv et mémoriser l'emplacement où il est enregister.
3. Copier le filepath du jeu de données et importer les datas dans R 
4. Exécuter le script en prenant bien soin de lire les sections en bleu afin de personnaliser les différences sections.
5. Le fichier produit 3 graphiques qui montre les différents niveaux d'expression tel que mentionné à la section résultats du script. 



