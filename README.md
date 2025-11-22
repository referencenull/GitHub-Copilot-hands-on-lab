# 🚀 GitHub Copilot Hands-On Lab
# https://github.com/referencenull/GitHub-Copilot-hands-on-lab

Welcome to the **GitHub Copilot Hands-On Lab**!  
This challenge will guide you through some of the Copilot features — from *Ask* and *Edit* and *Plan* modes to *MCP-powered issues*, *Copilot Coding Agent*, and *AI PR reviews*.  
You’ll work inside your own repository, experimenting freely and discovering how Copilot transforms your workflow.

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

> ⚠️ Copilot never commits code without your consent, but keep your hackathon work isolated.
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
<summary>🔹 <b>4️⃣ Create empty repo with one issue</b></summary>

Try questions like:
- [ ]  Click your profile picture at the top right and choose  "Repositories" from the menu <br>
      <img width="490" height="187" alt="image" src="https://github.com/user-attachments/assets/e7ad7952-dcc7-4fca-ba1a-3ec94d9a65f3" /> <br>     
- [ ]  Click "New" button to create new repo. Give it a name and description (like "This is a web application to manage inventory")
- [ ] Click "Issues" from the top menu and then button "New issue"
- [ ]  Give it a title (e.g. "Create new web application") and description (e.g.  "Create a new web application where user can manage their inventory sales items. User can add new items, delete and browse them. Create also test list of items in local database.")
- [ ]  Click "Create"
 💡 **Details**The more detailed description you give the better results you will get. Think this as you would write an issue to any human developer or team member.


💡 **Be curious!** Ask follow-ups. Ask *why*. Modify prompts.  
Try *Ask*, *Explain*, *Generate*, and *Edit* modes to see how each behaves.

- [ ] Switch between models (e.g. `GPT-5`, `Claud Sonnet 4.5`, `Claud Haiku 4.5`) and compare reasoning quality.

📘 [Use Copilot Chat to understand code](https://docs.github.com/en/copilot/github-copilot-chat/understanding-your-code-with-github-copilot-chat)
</details>

---

<details>
<summary>🔹 <b>5️⃣ Generate a <code>copilot_instructions.md</code> file</b></summary>

Copilot can generate **project setup and context notes** automatically — this file helps Copilot understand your project and coding style better.

### 💡 Why we’re doing this
The `copilot_instructions.md` file acts as a **knowledge source** for Copilot.  
It summarizes:
- How the project is structured  
- How to build and run it  
- Key dependencies, conventions, and folders  

When this file exists, Copilot can use it to **reason more effectively** about your codebase — for example, it can:
- Give more accurate answers when you ask questions about the project.  
- Provide better suggestions for refactoring, debugging, and tests.  
- Maintain consistent terminology and architecture decisions in its output.

Think of it as giving Copilot a “project briefing document”.

### 🧭 Steps
- [ ] Open the **Command Palette** (`Ctrl/Cmd + Shift + P`)  
- [ ] Search for **“Copilot: Generate Project Instructions”**  
- [ ] Follow the prompts to create a new file named `copilot_instructions.md`  

Once it’s created, open the file and read what Copilot generated.  
You can edit and expand this file — Copilot will use any updates in future conversations.

📘 **Documentation:**  
[Generate project instructions with Copilot](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/add-repository-instructions)
</details>

---

## 🧩 Phase 3 – Working with Issues via MCP

**Goal:** Use Copilot’s MCP connection to explore, understand, and create issues.

<details>
<summary>🔹 <b>6️⃣ Explore and discuss issues (via MCP)</b></summary>

Now that the `github-remote` MCP server is configured:

- [ ] Use Copilot Chat to list or summarize issues in your repo.  
  Examples:
  - “List open issues in this repo.”  
  - “Summarize issue #12.”  
  - “Suggest next steps for this bug.”  
  - “How could we improve code related to this issue?”

📘 [Using GitHub Copilot in Issues](https://docs.github.com/en/copilot/how-tos/chat-with-copilot/chat-in-ide)
</details>

---

<details>
<summary>🔹 <b>7️⃣ Analyze code relevant to an issue</b></summary>

- [ ] Pick an interesting issue.  
- [ ] Ask Copilot to locate where in the code this occurs, or to explain related logic.  

Examples:
> “Show me where this issue might occur in the code.”  
> “Explain how this module works.”  
> “What might cause this behavior?”
</details>

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
