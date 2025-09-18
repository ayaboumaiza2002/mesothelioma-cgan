# Génération de Données Mésothéliome avec cGAN

🎯 **Objectif**  
Utiliser un GAN conditionnel (cGAN) pour générer des données médicales synthétiques similaires aux données réelles du Mésothéliome.  

📁 **Dataset réel**  
- Données tabulaires  
- 324 lignes (patients atteints ou non de Mésothéliome)  

🛠️ **Technologies utilisées**  
- Python  
- TensorFlow / Keras  
- Pandas, Scikit-learn  
- Matplotlib, Seaborn  
- Flask 

🧪 **Étapes du projet**  
1. Prétraitement des données (normalisation, split par classe)  
2. Entraînement d'un modèle cGAN sur les données réelles  
3. Génération de nouvelles données synthétiques  
4. Évaluation des données générées à l'aide de classifieurs ML (Gradient Boosting) entraînés sur les données réelles  
5. Déploiement du modèle sous forme d'API Flask

📊 **Résultats**  
- Le classifieur Gradient Boosting atteint **+90% de précision** sur les données générées  

👩‍💻 **Réalisé par**  
Aya Boumaiza — Master Informatique Constantine 2  
Spécialité : Data Science et Systèmes Intelligents  
