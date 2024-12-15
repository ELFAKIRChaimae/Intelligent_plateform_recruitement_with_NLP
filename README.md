# LP Recrutement

📚 **Table des matières**
- [Description](#-description)
- [Fonctionnalités](#-fonctionnalités)
- [Technologies utilisées](#️-technologies-utilisées)
- [Installation](#-installation)
- [Démo](#-démo)

---

## ✨ Description
LP Recrutement est une application innovante qui utilise le traitement du langage naturel (NLP) pour faciliter le processus de recrutement. Elle permet aux recruteurs de créer des offres d'emploi et aux candidats de soumettre leur CV. L'application calcule la similarité entre les CVs et les offres d'emploi, optimisant ainsi le processus de sélection.

---

## 🔥 Fonctionnalités
### **Pour les recruteurs** 
- **Création d'offres d'emploi** : 
  - Ajout de détails tels que la description, le salaire et les compétences requises.

### **Pour les candidats**
- **Soumission de CV** :
  - Les candidats peuvent télécharger leur CV pour postuler directement aux offres.

### **Analyse NLP**
- **Calcul de similarité** :
  - **Méthode** : Utilise le modèle BERT pour encoder les textes des CVs et des offres d'emploi.
  - **Outil** : Calcul de similarité cosinus avec `sklearn`.
- **Tests pour les candidats** :
  - **Méthode** : Génération de questions techniques basées sur les CVs et descriptions de postes en utilisant le modèle Llama.
  - **Outil** : API Groq pour générer des questions et évaluer les réponses.

---

## ⚙️ Technologies utilisées
- **Frontend** : React pour l'interface utilisateur.
- **Backend** : Flask pour la gestion des API et services côté serveur.
- **Base de données** : MongoDB pour le stockage des données.
- **NLP** :
  - **Encodage de texte** : Modèle BERT pour traiter les CVs et les offres d'emploi.
  - **Génération de questions** : API Groq avec le modèle Llama.
  - **Évaluation des réponses** : Calcul de similarité cosinus avec `sklearn`.

---

## 📦 Installation

### Étape 1 : Cloner le dépôt
```bash
git clone https://github.com/votre-utilisateur/LP-Recrutement.git
cd LP-Recrutement

## Interface 


