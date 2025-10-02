# Développement d’un assistant téléphonique intelligent avec FastAPI, Twilio et OpenAI

##  Description
Ce projet démontre la mise en place d’un **assistant téléphonique intelligent** utilisant :
- **FastAPI** pour l’API backend,
- **Twilio** pour la gestion des appels téléphoniques,
- **OpenAI GPT** pour générer des réponses naturelles et contextuelles.

L’objectif est de permettre à un utilisateur d’appeler un numéro Twilio et d’interagir en direct avec un assistant vocal propulsé par l’IA.

---

## Technologies utilisées
- [FastAPI](https://fastapi.tiangolo.com/) — Framework Python moderne pour créer des APIs.
- [Uvicorn](https://www.uvicorn.org/) — Serveur ASGI performant.
- [Twilio](https://www.twilio.com/) — API de communication (voix, SMS).
- [OpenAI](https://platform.openai.com/) — Modèles GPT pour la génération de texte.
- [Ngrok](https://ngrok.com/) — Tunnel sécurisé pour exposer le serveur local.
- [Nest Asyncio](https://pypi.org/project/nest-asyncio/) — Compatibilité avec les environnements Jupyter/Colab.

---

## Structure des blocs
- **Block 0 — Installation & Ngrok**  
  Installe les dépendances et configure le tunnel public.
- **Block 1 — Variables d’environnement**  
  Définit les identifiants Twilio et OpenAI.
- **Block 2 — Application FastAPI**  
  Gère les endpoints `/call`, `/voice`, `/bot` et la logique de conversation.
- **Block 3 — Test du bot (simulation Twilio)**  
  Permet de tester l’IA directement via une requête HTTP.
- **Block 4 — Test santé du serveur**  
  Vérifie que l’API est bien active.
- **Block 5 — Déclenchement d’un appel réel**  
  Lance un appel téléphonique automatisé via Twilio.

---

##  Prérequis
1. Compte [Twilio](https://www.twilio.com/) avec un numéro de téléphone acheté.
2. Clé API [OpenAI](https://platform.openai.com/).
3. Installation de Python 3.9+.
4. Compte [Ngrok](https://ngrok.com/) pour exposer le serveur local.

---

## ▶️ Lancement du projet
1. Clonez le repo :
   ```bash
   git clone https://github.com/votre-repo/assistant-telephonique.git
   cd assistant-telephonique
