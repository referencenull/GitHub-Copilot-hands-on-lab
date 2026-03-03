# 🚀 Atelier pratique GitHub Copilot - Microsoft x Software Finland

Bienvenue dans l’atelier **GitHub Copilot Hands-On Lab** !  
Ce challenge vous guide à travers les fonctionnalités de Copilot — des modes *Ask*, *Edit* et *Plan* jusqu’au *Copilot Coding Agent*.  
Vous travaillerez dans votre propre dépôt, expérimenterez librement et verrez comment Copilot peut changer votre flux de travail et votre approche de la programmation.

---

## 📋 Prérequis

Avant de commencer cet atelier, assurez-vous d’avoir :

<details>
  <summary><ins>Compte GitHub</ins></summary>
  🔹 <b>Créez un compte GitHub. Nous recommandons d’utiliser votre adresse e-mail personnelle afin que les politiques de votre organisation ne limitent pas vos expérimentations.</b>
    - Allez sur : [github.com](https://github.com/)
    - Cliquez sur « Sign up » en haut à droite.<br><br>
    ![GitHub signup](https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef)
    <br>
    Renseignez les informations demandées, suivez les instructions et connectez-vous.
</details>

<details>
  <summary><ins>Licence GitHub Copilot</ins></summary>
  🔹 <b>Assurez-vous de disposer de la licence GitHub Copilot requise</b>
    - Ouvrez ce lien : [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) <br> et sélectionnez l’option « Pro » (celle du milieu)
    ![Copilot pricing](https://github.com/user-attachments/assets/d156511d-4f1b-4a2e-8be9-a9338b196099)
    - Vous devrez saisir des informations de paiement (carte bancaire ou PayPal), mais vous ne serez pas facturé si vous annulez après l’atelier.
  📘 **Documentation :**
  - [Getting started with GitHub Copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
</details>

## 🎯 Objectifs de l’atelier

À la fin de l’atelier :
- Vous aurez créé un compte GitHub et activé Copilot
- Vous aurez créé une application fonctionnelle sans écrire une seule ligne de code vous-même
- Vous aurez utilisé Copilot pour comprendre et améliorer du code existant

## 💬 Étape 1 – Créer un environnement de projet

**Objectif :** 1. Créer un environnement et un espace pour votre code (**dépôt/repository**) où vous pouvez tester Copilot. 2. Créer une tâche (**issue**).

<details>
<summary>🔹 <b><ins>Créer un dépôt vide et une issue</ins></b></summary>
- Ouvrez une nouvelle fenêtre/onglet de navigateur, allez sur [github.com](https://github.com) et connectez-vous (si ce n’est pas déjà fait).
- Cliquez sur votre photo de profil en haut à droite puis choisissez « Repositories ».
    ![Repositories](https://github.com/user-attachments/assets/432d8e28-e96c-4ec6-8c93-10db18ddb2b5)
- Cliquez sur le bouton « New » pour créer un nouveau dépôt.
    ![New Repo](https://github.com/user-attachments/assets/6be9be56-4d73-4e80-a53e-1ec511b9be5c)
- 1. Donnez un nom à votre dépôt. <br>2. Activez « Add README » sur « On ». <br>3. Cliquez sur « Create repository ».
    ![Repo details](https://github.com/user-attachments/assets/6c264ca6-274f-451c-acf2-1660cb6856c6)
- Pour créer la tâche/description, allez dans le menu du haut et cliquez sur « Issues ».
    ![Issues](https://github.com/user-attachments/assets/5732bb4e-3f46-4351-830d-36c51f522019)
- Puis cliquez sur « New issue ».
    ![New issue](https://github.com/user-attachments/assets/c02a53f9-85c8-4ef6-9914-bc2eead556f0)
- Mettez le titre : « Create a web app to manage inventory of a retail store »
- Utilisez le texte suivant comme description :  
    - Create a web app where the user can manage an inventory. User can browse products, add and delete products and change the quantity of products. Make the app look modern and easy to use. (etc.)
    ![Issue description](https://github.com/user-attachments/assets/3c11073b-31d1-4a5f-bfff-4b4d000b40bf)
</details>

## 🧩 Étape 2 – Laisser l’IA travailler

**Objectif :** Assigner l’issue créée au Coding Agent pour qu’il travaille dessus.

<details>
<summary>🔹 <b><ins>Assigner l’issue au Coding Agent et le laisser travailler en arrière-plan</ins></b></summary>

Une fois l’issue créée, vous pouvez l’assigner à Copilot Coding Agent et observer ce qui se passe :

- Cliquez sur « Assign to Copilot »
    ![Assign Copilot](https://github.com/user-attachments/assets/a19ffcb6-02c3-450c-a3fe-f62fc9860e88)
- Cliquez sur « Assign »
    ![Assign](https://github.com/user-attachments/assets/7ff48ee8-a024-42e0-be87-fe52418ef88e)
- Cliquez sur le lien « WIP... » à côté du titre de l’issue pour suivre ce que fait le Coding Agent.
    ![WIP](https://github.com/user-attachments/assets/ded50f10-9698-4feb-81c4-5eb5a6678975)
- Le Coding Agent met à jour sa progression ici. Cliquez sur « View session » pour voir les détails.
    ![View session](https://github.com/user-attachments/assets/0995db07-710b-41f1-a93a-2efffabaf695)
- Vous pouvez maintenant :
    1. Observer ce que fait le Coding Agent.
    2. Ajouter des suggestions ou modifications. Par exemple, écrivez : « Target this web app for company selling... » puis continuez avec, par ex., des motos, des skateboards, ou autre.
    ![Session suggestions](https://github.com/user-attachments/assets/6717f8ce-9e50-4004-a660-9920e2fb2208)
- Le travail du Coding Agent peut prendre plus de 10 minutes ; pendant ce temps, vous pouvez préparer l’environnement de développement et revenir plus tard.
📘 [About GitHub Coding Agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)
</details>

## 🧩 Étape 3 – Préparer l’environnement pour tester et modifier le code

**Objectif :** Ouvrir un environnement de développement cloud (Codespaces) pour explorer et modifier votre code dans Visual Studio Code.

<details>
<summary>🔹 <b><ins>Ouvrir le dépôt dans Codespaces et expérimenter Copilot dans VS Code</ins></b></summary>

- Dans votre navigateur, revenez depuis la session du Coding Agent.
- Cliquez sur l’onglet « <> Code » en haut.
    ![Code tab](https://github.com/user-attachments/assets/56b3ab92-8374-4a90-88b4-be932593f08c)
- Cliquez sur le bouton vert « Code », choisissez Codespaces, puis « Create Codespace on main ». Attendez l’ouverture de l’environnement.
    ![Codespace](https://github.com/user-attachments/assets/f1d5868f-beee-4321-b8ea-fc7ee971a229)
- Une fois le Codespace lancé et VS Code ouvert, il se peut que vous deviez :
    1. Connecter votre compte GitHub :
        ![GH connect](https://github.com/user-attachments/assets/d8cca31f-f959-43f6-aa59-c04cffb494c5)
    2. Activer GitHub Copilot :
        ![Copilot activation](https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75)
    Ensuite, vous êtes prêt·e à travailler avec Copilot dans votre environnement de développement. La façon la plus simple est la fenêtre de chat en bas à droite.
        ![Copilot chat](https://github.com/user-attachments/assets/d8957fdc-50c3-4c52-82e2-2df26457bb06)
    1. Écrivez des commandes/prompts pour Copilot
    2. Sélectionnez le mode Copilot : Chat, Edit, Agent
    3. Choisissez le modèle d’IA
    4. Ce symbole montre l’état de Copilot (actif/inactif, en réflexion)
Maintenant, retournons au portail GitHub.com pour voir si le Coding Agent a terminé. Nous reviendrons ici plus tard !
</details>

---

## 🧩 Étape 4 – Retour sur GitHub.com pour relire et approuver les changements du Coding Agent

<details>
<summary>🔹 <b><ins>Relire ce que le Coding Agent a fait et approuver la pull request</ins></b></summary>

À présent, le Coding Agent a terminé, et vous pouvez relire le résultat.

- Dans le menu du haut, choisissez « Pull requests »
    ![PRs](https://github.com/user-attachments/assets/e7efabcd-9f6d-45c4-9194-c3e127d7b016)
- Ouvrez la pull request.
    ![PR details](https://github.com/user-attachments/assets/eb2846f1-e5d6-4669-b5cf-1a4b54e13dc0)
- Relisez le code généré par Copilot
- Faites défiler et cliquez sur « Ready for review »
    ![Ready for review](https://github.com/user-attachments/assets/4d4fb966-d2a0-41ba-88c6-d598ad72ce9d)
- Puis « Merge pull request »
    ![Merge PR](https://github.com/user-attachments/assets/5eef7210-e81c-4dda-95b4-b692af464c75)
- Enfin, « Confirm merge »
    ![Confirm merge](https://github.com/user-attachments/assets/d069dcaa-61ad-4b1c-845d-34f3e50ed87a)
Le code de Copilot est maintenant fusionné dans votre projet/dépôt, et vous pouvez l’explorer, l’exécuter et le modifier. Retournons dans l’environnement de développement (Codespaces & VS Code).
</details>

---

## 🧮 Étape 5 – Récupérer les changements dans votre environnement de développement

<details>
<summary>🔹 <b><ins>Retour dans Codespaces pour mettre à jour les changements et explorer/modifier votre code</ins></b></summary>

- Récupérez les changements de Copilot via le menu en bas à gauche (« Synchronize Changes »)
    ![Sync](https://github.com/user-attachments/assets/5c258cad-c81f-473c-a0b2-17c41c02e25d)
    ![Sync 2](https://github.com/user-attachments/assets/15108c6d-9ee5-459e-b93b-21c5fd7d4e74)
- Vous pouvez maintenant exécuter l’application construite par Copilot. Comment ? Demandez à Copilot !
- Remarque : vous pouvez accepter directement les commandes suggérées par Copilot et les exécuter dans le terminal.
- Faites des modifications de code, par ex. ajoutez un bouton qui déclenche des confettis à l’écran.  
    (« Add button that will blow confetti on the screen »)
Autres idées à essayer :
- Ouvrez un fichier de code, sélectionnez une ligne, et demandez à Copilot d’expliquer ce qu’elle fait.
- Demandez à Copilot d’expliquer le contenu de votre projet du point de vue métier — ou même de générer une documentation HTML.

</details>

---

## 🧮 Étape 6 – Modifier davantage l’application

<details>
<summary>🔹 <b><ins>Maintenant que vous savez déjà créer des issues et les assigner au Copilot Coding Agent, essayez de créer une nouvelle issue (ou plusieurs) et laissez l’Agent travailler dessus. Faisons quelques [...]
</summary>

- Référez-vous à l’Étape 1 pour la création d’issues et à l’Étape 2. Imaginez des changements, créez plusieurs issues et assignez-les à l’agent.
- Vous pouvez aussi suivre la progression des agents dans VS Code en sélectionnant « Agent sessions » dans le menu de gauche
    ![Agent sessions](https://github.com/user-attachments/assets/06855fff-d387-4b2c-a168-dae6cc55629a)
- Pendant que les agents travaillent, essayez de faire vos propres modifications avec Copilot dans VS Code. Demandez-lui de faire des choses, comme ajouter des images aux produits, ou tout autre chose.
</details>

---

## 🧠 Partagez vos retours & discutez

- Quelle est la différence entre Coding Agent et le mode Copilot Agent ?
- Qu’est-ce qui vous a le plus surpris à propos de Copilot ?
- Quelle fonctionnalité vous a semblé la plus naturelle ou la plus utile ?
- Est-ce que cela pourrait bénéficier à des non-programmeurs ?

---

## ✅ Checklist

| Étape | Description | Fait |
|------|-------------|------|
| 1    | Créer l’environnement de projet | ☐ |
| 2    | Laisser l’IA travailler    | ☐ |
| 3    | Préparer l’environnement pour coder/tester | ☐ |
| 4    | Retour sur GitHub.com pour relire et approuver les changements | ☐ |
| 5    | Modifier l’application avec Copilot dans VS Code | ☐ |
| 6    | Modifier davantage l’application | ☐ |
| 🧠   | Partager vos retours        | ☐ |

---

Bonnes expérimentations et bonne exploration de Copilot ! 🎉
