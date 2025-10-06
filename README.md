# NeoChatAI

Une application de chatbot simple et puissante construite avec un backend Python et une interface utilisateur web.

## 🚀 Description

Ce projet est une application web qui fournit une interface de chat pour interagir avec un modèle d'intelligence artificielle. Le backend gère la logique du chatbot et le frontend offre une interface utilisateur simple et réactive.

---

## 🛠️ Pile Technologique

* **Backend**: Python (probablement avec Flask ou FastAPI)
* **Frontend**: HTML, CSS, JavaScript
* **Dépendances**: Gérées via `requirements.txt`

---

## ⚙️ Installation et Lancement

Suivez ces étapes pour faire fonctionner le projet sur votre machine locale.

1.  **Cloner le dépôt**
    ```bash
    git clone <URL_DU_DÉPÔT>
    cd NeoChatAI
    ```

2.  **Créer et activer un environnement virtuel**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Sur Windows, utilisez `venv\Scripts\activate`
    ```

3.  **Installer les dépendances**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Lancer l'application**

    Le script `run_and_tunnel_auto_stop.sh` simplifie le processus. Il démarre le serveur et crée un tunnel public (probablement avec ngrok ou cloudflared) pour un accès facile.

    * Rendre le script exécutable :
        ```bash
        chmod +x run_and_tunnel_auto_stop.sh
        ```
    * Exécuter le script :
        ```bash
        ./run_and_tunnel_auto_stop.sh
        ```

    Alternativement, vous pouvez lancer le serveur manuellement (par exemple `python app/main.py`) et ouvrir le fichier `frontend/index.html` dans votre navigateur.

---

## 📂 Structure du projet

# README.md (contenu simulé)
