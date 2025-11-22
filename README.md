# 🚀 GitHub Copilot Hands-On Lab
# https://github.com/referencenull/GitHub-Copilot-hands-on-lab

Welcome to the **GitHub Copilot Hands-On Lab**!  
This challenge will guide you through some of the Copilot features — from *Ask* and *Edit* and *Plan* modes to  *Copilot Coding Agent*.  
You’ll work inside your own repository, experimenting freely and discovering how Copilot transforms your workflow and way of working.

---

## 🧭 Phase 0 (prerequisites) – Setup & Preparation

**Goal:** Get your environment ready for Copilot experimentation.

<details>
<summary>🔹 <b>1️⃣ Create GitHub account if you do not already have one</b></summary>

- [ ]  Go to: github.com  

- [ ] From upper right corner click: Sign up
      <img width="357" height="150" alt="image" src="https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef" />
      <br>
- [ ]  Fill in required information and follow the process and then sign in
</details>
<details>
<summary>🔹 <b>2️⃣ Ensure GitHub Copilot is enabled</b></summary>

- [ ] If you already had GitHub and GitHub Copilot through Enterprise or Business plan check from the administrator that you have Coding Agent enabled
      https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-for-organization/add-copilot-coding-agent
- [ ] Open link: [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) and choose "Try for 30 days free" for Pro and follow the process

📘 **Documentation:**
- [Getting started with GitHub Copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
- [Setting up GitHub Copilot in VS Code](https://code.visualstudio.com/docs/copilot/setup)
</details>

## 💬 Phase 1 – Create repo and issue

**Goal:** Setup basic envrionment/repo where you can test and try GitHub Copilot

<details>
<summary>🔹 <b>3️⃣ Create empty repo and issue</b></summary>

Try questions like:
- [ ]  Click your profile picture at the top right and choose  "Repositories" from the menu <br>
      <img width="490" height="187" alt="image" src="https://github.com/user-attachments/assets/e7ad7952-dcc7-4fca-ba1a-3ec94d9a65f3" />
      <br>     
- [ ]  Click "New" button to create new repo. Give it a name and description (like "This is a web application to manage inventory")
- [ ] Click "Issues" from the top menu and then button "New issue"
- [ ]  Give it a title (e.g. "Create new web application") and description (e.g.  "Create a new web application where user can manage their inventory sales items. User can add new items, delete and browse them. Create also test list of items in local database.")
- [ ]  Click "Add README" toogle from "Off" to "On"
- [ ]  Click "Create"
      
 💡 **Details**The more detailed description you give the better results you will get. Think this as you would write an issue to any human developer or team member.
</details>

## 🧩 Phase 2 – Assign issue to Coding Agent

**Goal:** Let the Coding Agent do all the work.

<details>
<summary>🔹 <b>4️⃣ Assign issue to Coding Agent and let it work on the background</b></summary>

Now that the issue is created when can give it to the Copilot Coding Agent and find out what happens:

- [ ] Click "Assign to Copilot"
      <img width="541" height="294" alt="image" src="https://github.com/user-attachments/assets/db85f0a1-eb39-4d05-ab2a-7e72e5fd73a1" />
      <br>
- [ ] Write additional instructions to "Optional prompt" if you like but it is not mandatory
- [ ] Click "Assign"

Next we can follow what the Coding Agent is doing:
- [ ] Click "WIP..." (followed by your issues title) link
      <img width="94" height="89" alt="image" src="https://github.com/user-attachments/assets/e18fa4c6-ee0c-45a6-a374-2c20c0a3e413" />

- [ ] Here the Coding Agent will update it work but to look deeper what it is doing you can click "View session" button:
      <img width="314" height="118" alt="image" src="https://github.com/user-attachments/assets/dafceb61-2153-4373-acc8-3e1dc206fe1f" />

- [ ] See and explore what Coding agent is doing.
      The whole activity can take over 10 minutes so let's come back later to see the complete process and meanwhile do something else.

📘 [About GitHub Coding Agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)

</details>

<details>
<summary>🔹 <b>5️⃣ Open the repo in Codespace and explore Copilot in Visual Studio Code</b></summary>

- [ ] Click "<>Code" from the top left  
- [ ] Click green "Code"-button, select Codespaces and "Create Codespaces on main" and wait the environment to be set up.
- [ ] When the CS Code environment is setup the GitHub Copilot is ready to use and can be found on the left of the screen, but we still need to finish the setup to enable AI features from the bottom right corner
       <img width="330" height="168" alt="image" src="https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75" />
      And now we are ready to go
- [ ] First we could generate the instruction file for Copilot by clicking "Generate agent insctructions"
      <img width="236" height="200" alt="image" src="https://github.com/user-attachments/assets/15ee7203-c44a-4a0e-84fb-9bbf31a96bc1" />
- [ ] We can follow Copilot working and accept its suggestions when it needs our interaction e.g. running commands on console. It might also ask more details to which you can answer by writing 
- [ ] When Copilot is done with the work you can push green "Keep" button to keep the code changes
- [ ] 



---

<details>
<summary>🔹 <b>8️⃣ Generate a new issue</b></summary>

Once you’ve discussed a potential change, ask Copilot Chat to create a new issue.

- [ ] “Generate a new issue proposing a refactor of this method.”  
- [ ] “File an issue to add input validation.”  

Let Copilot generate the issue content directly.
</details>

---

<details>
<summary>🔹 <b>9️⃣ Assign the new issue to Copilot Coding Agent</b></summary>

You can do this in two ways:

- [ ] In Copilot Chat, say **“Assign this issue to the Copilot Coding Agent.”**  
- [ ] **Or** on **GitHub.com** → open the issue → click **Assignees** → select **@copilot**.

Observe how the Coding Agent interprets and plans the task.

📘 [Copilot Coding Agent overview](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)
</details>

---

## 🧮 Phase 4 – Reviewing and Reflection

**Goal:** Use Copilot to review and reason about existing work.

<details>
<summary>🔹 <b>🔟 Request a Copilot code review (on GitHub.com)</b></summary>

- [ ] Go to your repository on **GitHub.com**.  
- [ ] Find an existing Pull Request (in your org’s main project or your own branch).  
- [ ] Assign **@copilot** as a reviewer.  

Copilot will analyze the diff and comment directly on the PR.

> ⚠️ This action **updates the PR** with Copilot’s review comments.  
> 💡 *Alternative:* If you prefer, create a **duplicate PR** (from your hackathon branch) and assign Copilot there — this preserves the original untouched.

📘 [Using Copilot for Pull Request reviews](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/request-a-code-review/use-code-review)
</details>

---

## 🧠 Optional – Share Your Insights

- [ ] What surprised you most about Copilot’s behavior?  
- [ ] Did different models produce noticeably different results?  
- [ ] Which feature felt most natural or valuable?

---

## ✅ Completion Checklist

| Step | Description | Done |
|------|--------------|------|
| 1 | Fork / create project branch | ☐ |
| 2 | Enable Copilot and Chat | ☐ |
| 3 | Add `.vscode/mcp.json` (in branch) | ☐ |
| 4 | Explore Ask mode + models | ☐ |
| 5 | Generate `copilot_instructions.md` | ☐ |
| 6–9 | Work with issues & Coding Agent | ☐ |
| 10 | Assign PR to Copilot for review | ☐ |
| ✨ | Share insights | ☐ |

---

Happy hacking and exploring Copilot! 🎉
