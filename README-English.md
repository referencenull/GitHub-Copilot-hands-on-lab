# 🚀 GitHub Copilot Hands-On Lab - Microsoft x Software Finland

Welcome to the **GitHub Copilot Hands-On Lab** workshop!  
This challenge will guide you through Copilot's features — from *Ask*, *Edit*, and *Plan* modes all the way to the *Copilot Coding Agent*.  
You will work in your own repository, experiment freely, and see how Copilot can change your workflow and approach to programming.

---

## 📋 Prerequisites

Before you start this lab, please ensure you have:

<details>
  <summary><ins>GitHub Account</ins></summary>
  🔹 <b>Create a GitHub account. We recommend using your personal email so that your organization's policies don't restrict your experimentation.</b>
    - Go to: [github.com](https://github.com/)
    - Click "Sign up" in the top right corner.<br><br>
    ![GitHub signup](https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef)
    <br>
    Fill in the required information, follow the instructions, and sign in.
</details>

<details>
  <summary><ins>GitHub Copilot License</ins></summary>
  🔹 <b>Ensure you have the required GitHub Copilot license</b>
    - Open this link: [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) <br> and select the middle "Pro" option
    ![Copilot pricing](https://github.com/user-attachments/assets/d156511d-4f1b-4a2e-8be9-a9338b196099)
    - You will need to enter payment details (credit card or PayPal), but you will not be charged if you cancel after the lab.
  📘 **Documentation:**
  - [Getting started with GitHub Copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
</details>

## 🎯 Lab Objectives

By the end of the lab:
- You will have created a GitHub account and enabled Copilot
- You will have created a working application without writing a single line of code yourself
- You will have used Copilot to understand and enhance existing code

## 💬 Step 1 – Create a project environment

**Goal:** 1. Create an environment and place for your code (**repository**) where you can test Copilot. 2. Create a task (**issue**).

<details>
<summary>🔹 <b><ins>Create an empty repository and issue</ins></b></summary>
- Open a new browser window or tab, go to [github.com](https://github.com), and sign in (if not already).
- Click your profile picture in the top right and choose "Repositories".
    ![Repositories](https://github.com/user-attachments/assets/432d8e28-e96c-4ec6-8c93-10db18ddb2b5)
- Click the "New" button to create a new repository.
    ![New Repo](https://github.com/user-attachments/assets/6be9be56-4d73-4e80-a53e-1ec511b9be5c)
- 1. Name your repository. <br>2. Select "Add README" to "On". <br>3. Click "Create repository".
    ![Repo details](https://github.com/user-attachments/assets/6c264ca6-274f-451c-acf2-1660cb6856c6)
- To create the task/description, go to the top menu and click "Issues".
    ![Issues](https://github.com/user-attachments/assets/5732bb4e-3f46-4351-830d-36c51f522019)
- Then click "New issue".
    ![New issue](https://github.com/user-attachments/assets/c02a53f9-85c8-4ef6-9914-bc2eead556f0)
- Set the title to: "Create a web app to manage inventory of a retail store"
- Use the following as the description:  
    - Create a web app where the user can manage an inventory. User can browse products, add and delete products and change the quantity of products. Make the app look modern and easy to use. (etc.)
    ![Issue description](https://github.com/user-attachments/assets/3c11073b-31d1-4a5f-bfff-4b4d000b40bf)
</details>

## 🧩 Step 2 – Let the AI Get to Work

**Goal:** Assign the created issue to the Coding Agent to work on it.

<details>
<summary>🔹 <b><ins>Assign the issue to the Coding Agent and let it work in the background</ins></b></summary>

Once the issue is created, you can assign it to Copilot Coding Agent and see what happens:

- Click "Assign to Copilot"
    ![Assign Copilot](https://github.com/user-attachments/assets/a19ffcb6-02c3-450c-a3fe-f62fc9860e88)
- Click "Assign"
    ![Assign](https://github.com/user-attachments/assets/7ff48ee8-a024-42e0-be87-fe52418ef88e)
- Click the "WIP..." link next to the issue title to follow what the Coding Agent is doing.
    ![WIP](https://github.com/user-attachments/assets/ded50f10-9698-4feb-81c4-5eb5a6678975)
- Coding Agent updates its progress there. Click "View session" for details.
    ![View session](https://github.com/user-attachments/assets/0995db07-710b-41f1-a93a-2efffabaf695)
- Now you can:
    1. Observe what the Coding Agent is doing.
    2. Add further suggestions or changes. For example, write, "Target this web app for company selling..." and continue with, e.g., motorcycles, skateboards, or something else.
    ![Session suggestions](https://github.com/user-attachments/assets/6717f8ce-9e50-4004-a660-9920e2fb2208)
- The Coding Agent's work can take more than 10 minutes, so meanwhile, you can prepare the development environment and return later.
📘 [About GitHub Coding Agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)
</details>

## 🧩 Step 3 – Prepare the environment to test and modify the code

**Goal:** Open a cloud-based development environment (Codespaces), where you can explore and modify your code in Visual Studio Code.

<details>
<summary>🔹 <b><ins>Open the repository in Codespaces and experiment with Copilot in VS Code</ins></b></summary>

- In your browser, go back from the Coding Agent session.
- Click the "<> Code" tab at the top.
    ![Code tab](https://github.com/user-attachments/assets/56b3ab92-8374-4a90-88b4-be932593f08c)
- Click the green "Code" button, choose Codespaces, and "Create Codespace on main". Wait for the environment to open.
    ![Codespace](https://github.com/user-attachments/assets/f1d5868f-beee-4321-b8ea-fc7ee971a229)
- Once Codespace is launched and VS Code opens, you might need to:
    1. Connect your GitHub account:
        ![GH connect](https://github.com/user-attachments/assets/d8cca31f-f959-43f6-aa59-c04cffb494c5)
    2. Activate GitHub Copilot:
        ![Copilot activation](https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75)
    Afterwards, you are ready to work with Copilot in your dev environment. You can do this in several ways, the simplest being the chat window in the lower right corner.
        ![Copilot chat](https://github.com/user-attachments/assets/d8957fdc-50c3-4c52-82e2-2df26457bb06)
    1. Write commands/prompts for Copilot
    2. Select Copilot mode: Chat, Edit, Agent
    3. Choose the AI model
    4. This symbol shows Copilot's state (active/inactive, thinking)
Now, let's go back to the GitHub.com portal to see if the Coding Agent is done. We'll return here later!
</details>

---

## 🧩 Step 4 – Back to GitHub.com to review and approve Coding Agent's changes

<details>
<summary>🔹 <b><ins>Review what the Coding Agent did and approve the pull request</ins></b></summary>

Now the Coding Agent has finished and you can review the result

- In the top menu, choose "Pull requests"
    ![PRs](https://github.com/user-attachments/assets/e7efabcd-9f6d-45c4-9194-c3e127d7b016)
- Click open the pull request.
    ![PR details](https://github.com/user-attachments/assets/eb2846f1-e5d6-4669-b5cf-1a4b54e13dc0)
- Review the code generated by Copilot
- Scroll down and click "Ready for review"
    ![Ready for review](https://github.com/user-attachments/assets/4d4fb966-d2a0-41ba-88c6-d598ad72ce9d)
- Then "Merge pull request"
    ![Merge PR](https://github.com/user-attachments/assets/5eef7210-e81c-4dda-95b4-b692af464c75)
- Finally, "Confirm merge"
    ![Confirm merge](https://github.com/user-attachments/assets/d069dcaa-61ad-4b1c-845d-34f3e50ed87a)
Now Copilot's code is merged in your project/repo, and you can explore, run, and modify it. Let's return to the development environment (Codespaces & VS Code).
</details>

---

## 🧮 Step 5 – Download changes into your development environment

<details>
<summary>🔹 <b><ins>Back to Codespaces to update changes and explore/modify your code</ins></b></summary>

- Download Copilot's changes from the bottom left menu (Synchronize Changes)
    ![Sync](https://github.com/user-attachments/assets/5c258cad-c81f-473c-a0b2-17c41c02e25d)
    ![Sync 2](https://github.com/user-attachments/assets/15108c6d-9ee5-459e-b93b-21c5fd7d4e74)
- Now you can run the application built by Copilot. How? Ask Copilot!
- Note: you can directly accept Copilot's suggested commands and run them in the terminal.
- Make code changes, e.g., add a button that explodes confetti on the screen.  
    ("Add button that will blow confetti on the screen")
Some other things to try:
- Open any code file, select a line, and ask Copilot to explain what it does.
- Ask Copilot to explain your project's content from a business perspective—even have it generate HTML documentation.

</details>

---

## 🧮 Step 6 – Modify the app even more

<details>
<summary>🔹 <b><ins>Now that you already know how to create issues and assign them to the Copilot Coding Agent, try creating a new issue, or several, and let the Agent work on them. Let's make some more c[...]
</summary>

- Refer to Step 1 for issue creation and Step 2. Think up some changes, make several issues and assign them to the agent.
- You can also follow agent progress in VS Code by selecting "Agent sessions" from the left menu
    ![Agent sessions](https://github.com/user-attachments/assets/06855fff-d387-4b2c-a168-dae6cc55629a)
- While the agents are working, try making your own changes with Copilot in VS Code. Ask it to do things, like add images to products or something else entirely.
</details>

---

## 🧠 Share your findings & discuss

- What is the difference between Coding Agent and Copilot Agent mode?
- What surprised you most about Copilot?
- What feature felt the most natural or useful?
- Could this benefit non-programmers?

---

## ✅ Checklist

| Step | Description | Done |
|------|-------------|------|
| 1    | Create project environment | ☐ |
| 2    | Let the AI get to work    | ☐ |
| 3    | Prepare the environment for coding/testing | ☐ |
| 4    | Back to GitHub.com to review and approve changes | ☐ |
| 5    | Modify the application with Copilot in VS Code | ☐ |
| 6    | Modify the application more | ☐ |
| 🧠   | Share your thoughts        | ☐ |

---

Enjoy experimenting and exploring Copilot! 🎉
