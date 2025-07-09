# 🧠 Agent Python avec LLM + Mistral API

Ce projet est un **agent Python automatisé** qui interagit avec un **LLM via l'API de Mistral**, pour effectuer des tâches comme :

- Générer du code Python
- Écrire ce code dans un fichier
- Exécuter le fichier
- S'arrêter automatiquement une fois la tâche accomplie

## 🔧 Fonctionnalités

- Utilise les fonctions personnalisées suivantes :
  - `writeFile(path, content)` — écrit du code dans un fichier
  - `launchPythonFile(path)` — exécute un script Python
  - `stop()` — met fin à l'exécution de l'agent
- Lecture de la clé API via une variable d’environnement pour la sécurité
- Lecture multiple d'étapes (en JSON) dans les réponses du LLM

---

## 🚀 Lancer le projet

### 1. Cloner ce dépôt

```bash
git clone https://github.com/JosephEboue/intro_agent_ai.git
cd intro_agent_ai
