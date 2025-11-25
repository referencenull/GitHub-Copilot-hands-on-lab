# 🚀 GitHub Copilot Hands-On Lab
# https://github.com/referencenull/GitHub-Copilot-hands-on-lab

Welcome to the **GitHub Copilot Hands-On Lab**!  
This challenge will guide you through some of the Copilot features — from *Ask* and *Edit* and *Plan* modes to  *Copilot Coding Agent*.  
You’ll work inside your own repository, experimenting freely and discovering how Copilot transforms your workflow and way of working.

---

## 📋 Prerequisites

Before starting this lab, ensure you have:
- [ ] Laptop at the event
- [ ] GitHub account
      <details>
      <summary>🔹 <b>0️⃣ Create GitHub account if you do not already have one</b></summary>
                  Go to: github.com  
                  From upper right corner click: Sign up <br>
                  <img width="250" height="105" alt="image" src="https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef" />
                  <br>
                  Fill in required information and follow the process and then sign in
      </details>

- [ ] GitHub Copilot license
      <details>
      <summary>🔹 <b>1️⃣ Ensure GitHub Copilot is enabled</b></summary>
                         IF you already have GitHub and GitHub Copilot through Enterprise or Business plan check from the administrator that you have Coding Agent enabled                         <br>
                        https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-for-organization/add-copilot-coding-agent<br>
                        OR <br>
                        Open link: [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) and choose "Try for 30 days free" for                          GitHub Copilot Pro  and follow the activation process

📘 **Documentation:**
- [Getting started with GitHub Copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
</details>


## 🎯 Lab Objectives

By the end of this lab, you will:
- Set up your GitHub account and access GitHub Copilot
- Create applications using various GitHub Copilot tools
- Use GitHub Copilot to understand and improve existing code


## 💬 Phase 1 – Create repo and issue

**Goal:** Setup basic envrionment/repo where you can test and try GitHub Copilot

<details>
<summary>🔹 <b>2️⃣ Create empty repo and issue</b></summary>

Try questions like:
- [ ]  Click your profile picture at the top right and choose  "Repositories" from the menu <br>
      <img width="490" height="187" alt="image" src="https://github.com/user-attachments/assets/e7ad7952-dcc7-4fca-ba1a-3ec94d9a65f3" />
         
- [ ]  Click "New" button to create new repo. Give it a name and description (like "This is a web application to manage inventory")
- [ ] Click "Issues" from the top menu and then button "New issue"
- [ ]  Give it a title (e.g. "Create new web application") and description (e.g.  "Create a new web application where user can manage their inventory sales items. User can add new items, delete and browse them. Create also test list of items in local database.")
- [ ]  Click "Add README" toogle from "Off" to "On"
- [ ]  Click "Create"
      
 💡 **Details** The more detailed description you give the better results you will get later from Copilot. Think this as you would write an work description to any human developer or team member.
</details>

## 🧩 Phase 2 – Assign issue to Coding Agent

**Goal:** Let the Coding Agent do the work.

<details>
<summary>🔹 <b>3️⃣ Assign issue to Coding Agent and let it work on the background</b></summary>

Now that the issue is created we can give it to the Copilot Coding Agent to work on and find out what happens:

- [ ] Click "Assign to Copilot" <br>
      <img width="486" height="265" alt="image" src="https://github.com/user-attachments/assets/db85f0a1-eb39-4d05-ab2a-7e72e5fd73a1" />
      
- [ ] Optional: Write additional instructions to "Optional prompt" if you like
- [ ] Click "Assign"

Next we can follow what the Coding Agent is doing:
- [ ] Click "WIP..." (followed by your issues title) link <br>
      <img width="94" height="89" alt="image" src="https://github.com/user-attachments/assets/e18fa4c6-ee0c-45a6-a374-2c20c0a3e413" />

- [ ] Here the Coding Agent will update it work but to look deeper what it is doing you can click "View session" button: <br>
      <img width="314" height="118" alt="image" src="https://github.com/user-attachments/assets/dafceb61-2153-4373-acc8-3e1dc206fe1f" />

- [ ] See and explore what Coding agent is doing.
      The whole activity can take over 10 minutes so let's come back later to see the complete process and meanwhile do something else.

📘 [About GitHub Coding Agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)

</details>

## 🧩 Phase 3 – Open repo in Codespaces

**Goal:** Use Copilot in VS Code from GitHub cloud based coding environment, Codespaces.

<details>
<summary>🔹 <b>4️⃣ Open the repo in Codespaces and explore Copilot in Visual Studio Code</b></summary>

- [ ] Click "<>Code" from the top menu  
- [ ] Click green "Code"-button, select Codespaces and "Create Codespaces on main" and wait the environment to be set up. Codespaces is a cloud development environment created to you automatically by GitHub. 
- [ ] When the VS Code environment is setup GitHub Copilot is almost ready to use and can be found on the right of the screen, but we still need to finish the setup to enable AI features from the bottom right corner <br>
       <img width="330" height="168" alt="image" src="https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75" />
       
And now we are ready to go
- [ ] First we could generate the instruction file, as suggested, for Copilot by clicking "Generate agent insctructions" <br>
      <img width="236" height="200" alt="image" src="https://github.com/user-attachments/assets/15ee7203-c44a-4a0e-84fb-9bbf31a96bc1" /> <br>
      
- [ ] We can follow Copilot working and accept its suggestions when it needs our interaction e.g. running commands on console. It might also ask more details from you.
- [ ] When Copilot is done with the work you can push green "Keep" button to keep the code changes
- [ ] Explore the copilot-instructions.md file that was created. This is where you can easily put general coding instructions for Copilot .i.e. coding standards, frameworks to use, workflows, repositiry structure...

</details>
<details>
<summary>🔹 <b>5️⃣ Explore different modes of Copilot</b></summary>

- [ ] There are different options how you can use Copilot: Ask, Edit and Agent.
      
Ask Mode

Ask mode is designed for quick, context-aware answers to programming questions. It allows you to highlight code, type a query, and receive explanations, suggestions, or code snippets without modifying your code. This mode is ideal for understanding code functionality, exploring libraries, or solving specific problems like structuring SQL queries or debugging JavaScript closures. It’s a lightweight, non-intrusive way to get unstuck while staying focused on your task.

Edit Mode

Edit mode enables you to make precise code changes across one or more files by describing the desired updates in natural language. Copilot generates inline, review-ready edits, allowing you to approve or reject changes before they are applied. This mode is perfect for tasks like refactoring, adding error handling, or adhering to specific coding standards. It ensures you remain in control while accelerating repetitive or tedious tasks

Agent Mode

Agent mode is the most powerful and autonomous of the three. It allows Copilot to execute high-level tasks, such as building features, fixing bugs, or scaffolding entire sections of an application. Unlike Edit mode, Agent mode reasons across your entire project, applies multi-step changes, and runs commands or tools as needed. While it automates complex workflows, it requires clear instructions and is best suited for experienced developers who can guide its actions effectively

</details>

---

## 🧩 Phase 4 – Back to GitHub.com and Coding Agent
<details>
<summary>🔹 <b>6️⃣Let's explore what coding agent has done and accept the pull request it made</b></summary>

Now the coding agent should have finished it work and we can see what it came up with

- [ ] Go to "Pull requests" from the top menu then open the pull request shown  
- [ ] Explore the outcome of Copilot, scroll down and click "Ready for review" button and then "Merge pull request" button when it turns green and finally "Confirm merge" 

Now the code that Copilot created has been pulled to our codebase
</details>

---

<details>
<summary>🔹 <b>7️⃣ Back to Codespaces to explore and modify the code</b></summary>

- [ ] From left menu open "Source control" and then pull the changes Copilot made <br>
      <img width="357" height="274" alt="image" src="https://github.com/user-attachments/assets/d3ffa87c-c1ae-4f16-ae30-86b233b385ef" /> <br>

- [ ] Now we can run the application Copilot has created to us. But how? Let's ask from Copilot. Notice that you can insert the commands Copilot suggest directly to console.
- [ ] Let's do some code changes. Maybe add button that blows confetti on the screen? Remember to accept the code suggestion by clicking the green "Keep"
      ("Add button that will blow confetti on the screen")
- [ ] You can also ask Copilot to explain the code and maybe create html documentation.
- [ ] Maybe open some code file, select few lines of code and ask Copilot to explain the code?

</details>

---

## 🧮 Phase 5 – Modify application using Copilot Agent from VS Code

<details>
<summary>🔹 <b>8️⃣ Modify application by creating a new issue and give it to Coding Agent to work in the background</b></summary>

- [ ] From the menu on the left in VS code click GitHub icon and then "+" to create an new issue  <br>
      <img width="252" height="166" alt="image" src="https://github.com/user-attachments/assets/128bcfca-44c4-49ed-99b9-a8f620fa6311" /> <br>
      Change "Issue Title" to "Add images" <br>
      Add description like "Add images to product. Add also test images to the database" <br>
      Then create issue by clicking the check mark <br>
      <img width="186" height="60" alt="image" src="https://github.com/user-attachments/assets/4c0bee8c-1688-4246-995a-19a5ba2f2e8b" /> <br>

- [ ] Open the newly created issue and assign it to Copilot. You can see Copilot starting to work on it
- [ ] You can also watch the progress by clicking from the left menu the "Agent sessions"
- [ ] And also as previously go to GitHub.com and "Pull requests" to see the progress .

---

## 🧠 Optional 1 – Try again creating new repo and new solution. Focus more on descriptions of repo, README and issues.

---

## 🧠 Optional 2 – Share Your Insights

- [ ] What surprised you most about Copilot’s behavior?  
- [ ] Did different models produce noticeably different results?  
- [ ] Which feature felt most natural or valuable?

---

## ✅ Completion Checklist

| Step | Description | Done |
|------|--------------|------|
| 1 | Create repo and issue| ☐ |
| 2 | Assign issue to coding agent | ☐ |
| 3 | Open code in Codespaces | ☐ |
| 4 | Accept changes from Coding Agent (merge pull request) | ☐ |
| 5 | Modify application using Copilot in VS Code | ☐ |
| Optional 1| Try everything again | ☐ |
| ✨ | Share insights | ☐ |

---

Happy hacking and exploring Copilot! 🎉
