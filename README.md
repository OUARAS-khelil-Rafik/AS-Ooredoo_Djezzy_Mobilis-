# 📊 AS-Ooredoo\_Djezzy\_Mobilis

> **Projet de Fin d'Études** – Analyse des sentiments appliquée aux opérateurs télécoms algériens : Ooredoo, Djezzy et Mobilis.

## 🧠 Objectif du Projet

Ce projet a pour but d'évaluer la position concurrentielle d’Ooredoo sur le marché algérien en analysant les sentiments exprimés par les clients sur les réseaux sociaux et autres plateformes. L'analyse est réalisée à l'aide de techniques d'intelligence artificielle, notamment le traitement du langage naturel (NLP) et l'apprentissage profond.

## 📁 Structure du Répertoire

Le projet est organisé comme suit :

```plaintext
AS-Ooredoo_Djezzy_Mobilis/
├── Data/
│   └── Données brutes et prétraitées
├── Results/
│   └── Résultats des modèles et visualisations
├── notebooks/
│   └── Annotate_AS_VADER.ipynb
│   └── Annotate_IA_Model_Comments.ipynb
│   └── Annotate_IA_Model_Posts.ipynb
│   └── Pretraitement_AS.ipynb
│   └── Training_AS.ipynb
│   └── Training_AS_DL_DziriBert.ipynb
│   └── Training_AS_DL_DziriBertV2.ipynb
│   └── Training_AS_DL_LSTM.ipynb
└── README.md
```

## 🛠️ Technologies et Outils Utilisés

* **Langages** : Python
* **Bibliothèques** :

  * Pandas, NumPy
  * Matplotlib, Seaborn
  * Scikit-learn
  * TensorFlow, Keras
  * NLTK, VADER
  * Transformers (DziriBERT)
* **Environnements** :

  * Jupyter Notebook
  * Google Colab([GitHub][2], [GitHub][1])

## 📊 Méthodologie

1. **Collecte de Données** : Récupération de commentaires et publications liés aux opérateurs télécoms algériens.
2. **Prétraitement** : Nettoyage des données, suppression des stop words, lemmatisation, etc.
3. **Annotation** : Utilisation de VADER pour l'annotation automatique des sentiments.
4. **Modélisation** :

   * Modèles traditionnels : SVM, Random Forest
   * Apprentissage profond : LSTM, DziriBERT
5. **Évaluation** : Analyse des performances des modèles à l'aide de métriques telles que la précision, le rappel et le F1-score.
6. **Visualisation** : Représentation graphique des résultats pour une meilleure interprétation.([GitHub][1])

## 📈 Résultats

* **Modèle DziriBERT** : Offre une précision élevée dans la détection des sentiments, surpassant les modèles traditionnels.
* **Comparaison des Opérateurs** :

  * Ooredoo : Sentiments majoritairement positifs.
  * Djezzy : Sentiments mitigés.
  * Mobilis : Sentiments majoritairement négatifs.([GitHub][2])

## 📌 Points Forts

* Utilisation d'un modèle pré-entraîné spécifiquement pour la langue arabe (DziriBERT).
* Analyse comparative entre trois opérateurs majeurs en Algérie.
* Approche combinée de méthodes traditionnelles et d'apprentissage profond.([GitHub][1])

## 🚀 Comment Exécuter le Projet

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/OUARAS-khelil-Rafik/AS-Ooredoo_Djezzy_Mobilis-.git
   ```

2. Installer les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

3. Lancer les notebooks Jupyter pour explorer les différentes étapes du projet.

## 📬 Contact

Pour toute question ou suggestion, n'hésitez pas à me contacter :

* **OUARAS Khelil Rafik**

  * Email : [kh.ouaras@univ-alger.dz](mailto:kh.ouaras@univ-alger.dz)
  * GitHub : [OUARAS-khelil-Rafik](https://github.com/OUARAS-khelil-Rafik)
  * LinkedIn : [OUARAS Khelil Rafik](https://www.linkedin.com/in/ouaras-khelil-rafik/)([GitHub][2])

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

*Ce projet a été réalisé dans le cadre du Projet de Fin d'Études à l'Université d'Alger, Faculté des Sciences, Département d'Informatique.*

[1]: https://github.com/OUARAS-khelil-Rafik/AS-Ooredoo_Djezzy_Mobilis-?utm_source=chatgpt.com "OUARAS-khelil-Rafik/AS-Ooredoo_Djezzy_Mobilis - GitHub"
[2]: https://github.com/OUARAS-khelil-Rafik?utm_source=chatgpt.com "OUARAS-khelil-Rafik - GitHub"
