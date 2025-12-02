# 🚀 GitHub Copilot Hands-On Lab - <br><b>Microsoft x Software Finland</b>

Benvenuti al workshop **GitHub Copilot Hands-On Lab**!  
Questa sfida vi guiderà attraverso le funzionalità di Copilot — dalle modalità *Ask*, *Edit* e *Plan* fino al *Copilot Coding Agent*.  
Lavorerete nel vostro repository, sperimenterete liberamente e vedrete come Copilot trasforma il vostro modo di lavorare e sviluppare.

---

## 📋 Prerequisiti

Prima di iniziare questo laboratorio, assicuratevi di avere:
<details>
      <summary><ins>Account GitHub</ins></summary>
     🔹 <b> Create un account GitHub. Si consiglia di creare l'account con un indirizzo email personale, in modo che eventuali regole della vostra organizzazione non limitino la sperimentazione.</b>
            - Andate all'indirizzo: [github.com](https://github.com/)
            - Cliccate in alto a destra su: Sign up <br><br>
            <img width="250" height="105" alt="image" src="https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef" />
            <br>
            Compilate i dati richiesti, seguite le istruzioni e accedete
      </details>

<details>
      <summary><ins>Licenza GitHub Copilot</ins></summary>
      🔹 <b> Assicuratevi di avere l'accesso richiesto a GitHub Copilot</b>
            - Aprite il link: [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) <br> e selezionate dall'opzione centrale                               "Pro" la voce "Try for 30 days free" <br>
            <img width="507" height="420" alt="image" src="https://github.com/user-attachments/assets/d156511d-4f1b-4a2e-8be9-a9338b196099" /><br>
            - Dovrete inserire i vostri dati di pagamento (carta di credito o PayPal), ma non verrà addebitato nulla se annullate l'abbonamento dopo il laboratorio.

📘 **Documentazione:**
- [Iniziare con GitHub Copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
</details>


## 🎯 Obiettivi del laboratorio

Alla fine del laboratorio:
- Avrete creato un account GitHub e attivato Copilot
- Avrete creato un'applicazione funzionante senza scrivere una sola riga di codice
- Avrete utilizzato Copilot per comprendere e migliorare un programma/codice esistente

## 💬 Fase 1 – Creazione dell'ambiente per il progetto

**Obiettivo:** 1. Creare un ambiente e un luogo per il codice (**repository**), dove potete testare e sperimentare GitHub Copilot  2. Creare un'assegnazione (**issue**)

<details>
<summary>🔹 <b><ins> Create un repository vuoto e un issue</ins></b></summary>
      
- Cliccate sulla vostra immagine del profilo in alto a destra e selezionate "Repositories" <br>
        <img width="258" height="67" alt="image" src="https://github.com/user-attachments/assets/432d8e28-e96c-4ec6-8c93-10db18ddb2b5" />
         
- Cliccate sul pulsante "New" per creare un nuovo repository <br>
      <img width="191" height="94" alt="image" src="https://github.com/user-attachments/assets/6be9be56-4d73-4e80-a53e-1ec511b9be5c" /> <br>
      
- 1.Date un nome al repository <br>2.Selezionate l'opzione "Add README" su "On" <br>3.Premete "Create repository" <br>
      <img width="467" height="671" alt="image" src="https://github.com/user-attachments/assets/6c264ca6-274f-451c-acf2-1660cb6856c6" /><br>

- Create un'assegnazione/descrizione cioè un "Issue": Selezionate dal menu in alto "Issues" <br>
      <img width="513" height="62" alt="image" src="https://github.com/user-attachments/assets/5732bb4e-3f46-4351-830d-36c51f522019" /> <br>

- E poi "New issue" <br>
      <img width="256" height="46" alt="image" src="https://github.com/user-attachments/assets/c02a53f9-85c8-4ef6-9914-bc2eead556f0" />

- Date come titolo: Create a web app to manage inventory of a retail store
- Date come descrizione: <br>
      - Create an web app where user can manage an inventory. User can browse products, add and delete products and change the quantity of products. Make the app look modern and easy to use. Create also a local test database with 20 products pre populated <br>
      <img width="630" height="435" alt="image" src="https://github.com/user-attachments/assets/3c11073b-31d1-4a5f-bfff-4b4d000b40bf" />

</details>

## 🧩 Fase 2 – Mettiamo l'intelligenza artificiale al lavoro

**Obiettivo:** Assegnare l'incarico (issue) al Coding Agent

<details>
<summary>🔹 <b><ins> Assegnate l'issue al Coding Agent e lasciatelo lavorare in background</ins></b></summary>

Quando l'issue è stato creato, potete assegnarlo al Copilot Coding Agent e vedere cosa succede:

- Cliccate su "Assign to Copilot" <br>
      <img width="455" height="328" alt="image" src="https://github.com/user-attachments/assets/a19ffcb6-02c3-450c-a3fe-f62fc9860e88" /><br>
- Cliccate su "Assign"<br>
      <img width="475" height="233" alt="image" src="https://github.com/user-attachments/assets/7ff48ee8-a024-42e0-be87-fe52418ef88e" /><br>
- Cliccate sul link "WIP..." (con il titolo del vostro issue) per seguire cosa fa il Coding Agent <br>
      <img width="420" height="113" alt="image" src="https://github.com/user-attachments/assets/ded50f10-9698-4feb-81c4-5eb5a6678975" /><br>
- Il Coding Agent aggiornerà qui il suo lavoro. Esplorate in dettaglio cliccando su "View session": <br>
      <img width="383" height="134" alt="image" src="https://github.com/user-attachments/assets/0995db07-710b-41f1-a93a-2efffabaf695" /><br>
- Ora potete:<br>
      1. Osservare cosa fa il Coding Agent<br>
      2. Fornire ulteriori suggerimenti o modifiche. Scrivete qui ad esempio "Target this web app for company selling..." <- continuate la frase es. motorcycles, skateboards o qualcos'altro che volete vedere nel programma.<br>
      <img width="477" height="658" alt="image" src="https://github.com/user-attachments/assets/6717f8ce-9e50-4004-a660-9920e2fb2208" /><br>
L'intero processo può richiedere più di 10 minuti, quindi nel frattempo possiamo fare altro e tornare a controllare la situazione più tardi.
      
📘 [Informazioni su GitHub Coding Agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)

</details>

## 🧩 Fase 3 – Preparazione dell'ambiente per testare e modificare il codice

**Obiettivo:** Aprire un ambiente di sviluppo cloud-based (Codespaces), dove possiamo esplorare e modificare il codice in Visual Studio Code (VS Code)

<details>
<summary>🔹 <b><ins> Aprite il repository in Codespaces ed esplorate Copilot in VS Code</ins></b></summary>

- Tornate indietro di un passo nel browser (dalla vista del lavoro del Coding Agent)
- Cliccate su "<>Code" nel menu in alto <br>
      <img width="125" height="77" alt="image" src="https://github.com/user-attachments/assets/56b3ab92-8374-4a90-88b4-be932593f08c" /><br>

- Cliccate sul pulsante verde "Code", selezionate Codespaces e "Create Codespaces on main", attendete l'apertura dell'ambiente. <br>
      <img width="433" height="525" alt="image" src="https://github.com/user-attachments/assets/f1d5868f-beee-4321-b8ea-fc7ee971a229" />

- Quando Codespaces è stato creato e VS Code si è aperto, l'ambiente potrebbe richiedere ancora i seguenti passaggi:<br>
      1. Collegamento dell'account GitHub:<br>
      <img width="548" height="281" alt="image" src="https://github.com/user-attachments/assets/d8cca31f-f959-43f6-aa59-c04cffb494c5" /><br>
      2. Attivazione di GitHub Copilot:<br>
       <img width="330" height="168" alt="image" src="https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75" /> <br>    
      Dopodiché tutto è pronto e possiamo lavorare con Copilot nell'ambiente di sviluppo. Ci sono molti modi, il più semplice è direttamente nella finestra di chat in basso a destra (potete aumentare la dimensione del font premendo Ctrl + ):<br>
      <img width="391" height="481" alt="image" src="https://github.com/user-attachments/assets/d8957fdc-50c3-4c52-82e2-2df26457bb06" /><br>
      1. Scrivete i comandi/prompt a Copilot
      2. Selezionate la modalità Copilot: Chat, Edit, Agent
      3. Selezionate il modello di intelligenza artificiale
      4. Questo simbolo indica lo stato di Copilot (attivo/non attivo, 'sta pensando')

Ora possiamo però tornare a controllare sul portale GitHub.com se il Coding Agent ha finito. Torneremo qui tra poco

</details>

---

## 🧩 Fase 4 – Torniamo su GitHub.com per visualizzare e approvare le modifiche del Coding Agent
<details>
<summary>🔹 <b><ins>Esaminate cosa ha fatto il Coding Agent e approvate la sua pull request</ins></b></summary>

Ora il Coding Agent ha completato il suo lavoro e potete esaminare il risultato finale

- Selezionate "Pull requests" dal menu in alto <br>
      <img width="494" height="56" alt="image" src="https://github.com/user-attachments/assets/e7efabcd-9f6d-45c4-9194-c3e127d7b016" /><br>
- Cliccate per aprire la pull request <br>
      <img width="688" height="160" alt="image" src="https://github.com/user-attachments/assets/eb2846f1-e5d6-4669-b5cf-1a4b54e13dc0" /><br>
- Esaminate il codice prodotto da Copilot<br>
- Scorrete la vista verso il basso e cliccate su "Ready for review" <br>
      <img width="701" height="518" alt="image" src="https://github.com/user-attachments/assets/4d4fb966-d2a0-41ba-88c6-d598ad72ce9d" /><br>
- Poi cliccate su "Merge pull request"<br>
      <img width="701" height="482" alt="image" src="https://github.com/user-attachments/assets/5eef7210-e81c-4dda-95b4-b692af464c75" /><br>
- E infine "Confirm merge" <br>
      <img width="687" height="334" alt="image" src="https://github.com/user-attachments/assets/d069dcaa-61ad-4b1c-845d-34f3e50ed87a" /><br>

Ora il codice creato da Copilot è stato approvato nel progetto / repository e possiamo esaminarlo, eseguirlo e modificarlo. Quindi torniamo all'ambiente di sviluppo (Codespaces & VS Code).
</details>

---

## 🧮 Fase 5 – Scarichiamo le modifiche nell'ambiente di sviluppo

<details>
<summary>🔹 <b><ins> Torniamo in Codespaces per aggiornare le modifiche ed esplorare e modificare il codice</ins></b></summary>

- Scaricate le modifiche di Copilot dal menu in basso a sinistra (Synchronize Changes) <br>
      <img width="442" height="128" alt="image" src="https://github.com/user-attachments/assets/5c258cad-c81f-473c-a0b2-17e41c02e25d" /><br>
      <img width="583" height="178" alt="image" src="https://github.com/user-attachments/assets/15108c6d-9ee5-459e-b93b-21c5fd7d4e74" /><br>

- Ora potete eseguire l'applicazione creata da Copilot. Come? Chiedetelo a Copilot!
- Notate che potete accettare direttamente i comandi suggeriti da Copilot nel terminale.
- Fate modifiche al codice. Aggiungete magari un pulsante che fa esplodere coriandoli sullo schermo?
     ("Add button that will blow confetti on the screen")
Provate questi se volete:
- Aprite un file di codice, selezionate una riga di codice e chiedete a Copilot di spiegare questo codice.
- Potete anche ad esempio chiedere a Copilot di spiegare il contenuto del progetto dal punto di vista aziendale e di trasformarlo in documentazione HTML.

</details>

---

## 🧮 Fase 6 – Modificate l'applicazione ulteriormente 

<details>
<summary>🔹 <b><ins> Ora che sapete già creare un issue e assegnarlo al Copilot Coding Agent, provate a creare un nuovo issue o più issue e assegnateli all'agent. Modifichiamo di più anche in VS Code</ins></b></summary>

- Guardate la creazione dell'issue nella fase 1 e la fase 2. Inventate delle modifiche, create anche più issue e assegnateli all'agent. 
- Potete seguire l'avanzamento del lavoro dell'agent anche in VS Code selezionando dal menu a sinistra "Agent sessions"<br>
      <img width="179" height="206" alt="image" src="https://github.com/user-attachments/assets/06855fff-d387-4b2c-a168-dae6cc55629a" /><br>

- Nel frattempo, mentre gli agent lavorano, provate a fare modifiche con Copilot in VS Code. Chiedetegli di fare modifiche, come aggiungere immagini ai prodotti o qualcos'altro.

</details>

---

## 🧠 Condividete le vostre osservazioni & discussione

- Qual è la differenza tra Coding Agent e Copilot Agent mode?
- Cosa vi ha sorpreso di più nel funzionamento di Copilot?  
- Quale funzionalità vi è sembrata più naturale o utile?
- Potrebbe essere utile anche per chi non è programmatore?

---

## ✅ Checklist

| Fase | Descrizione | Fatto |
|------|-------|------|
| 1 | Creazione dell'ambiente per il progetto| ☐ |
| 2 | Mettiamo l'intelligenza artificiale al lavoro | ☐ |
| 3 | Preparazione dell'ambiente per testare e modificare il codice | ☐ |
| 4 | Torniamo su GitHub.com per visualizzare e approvare le modifiche del Coding Agent | ☐ |
| 5 | Modificate l'applicazione con Copilot in VS Code | ☐ |
| 6 | Modificate l'applicazione ulteriormente | ☐ |
| 🧠 | Condividete le vostre osservazioni | ☐ |

---

Buona sperimentazione e buona esplorazione di Copilot! 🎉
