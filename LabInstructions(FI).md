# 🚀 GitHub Copilot Hands-On Lab - <b>Microsoft x Software Finland</b>

Tervetuloa **GitHub Copilot Hands-On Lab** -työpajaan!  
Tämä haaste johdattaa sinut Copilotin ominaisuuksien läpi — *Ask*, *Edit* ja *Plan* -tiloista aina *Copilot Coding Agent* -agenttiin saakka.  
Työskentelet omassa repossasi, kokeilet vapaasti ja näet, miten Copilot muuttaa työskentely- ja kehitystapojasi.

---

## 📋 Esivaatimukset

Ennen kuin aloitat tämän labran, varmista että sinulla on:
<details>
      <summary><ins>GitHub-tili</ins></summary>
     🔹 <b>0️⃣ Luo GitHub-tili. Suosittelemme luomaan tilin henkilökohtaisella sähköposti osoitteella, jotta mahdolliset organisaatiosi säännöt eivät rajoita kokeilemista.</b>
                  -Mene osoitteeseen: [github.com](https://github.com/)
                  -Klikkaa oikeasta yläkulmasta: Sign up <br><br>
                  <img width="250" height="105" alt="image" src="https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef" />
                  <br>
                  Täytä vaaditut tiedot, seuraa ohjeita ja kirjaudu sisään
      </details>

<details>
      <summary><ins>GitHub Copilot -lisenssi</ins></summary>
      🔹 <b>1️⃣ Varmista, että sinulla on vaadittava GitHub Copilot käyttöoikeus</b>
                        -Avaa linkki: [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) <br> ja valitse Keskimmäisestä                               "Pro" vaihtoehdosta "Try for 30 days free" <br>
                        <img width="507" height="420" alt="image" src="https://github.com/user-attachments/assets/d156511d-4f1b-4a2e-8be9-a9338b196099" /><br>
                        -Joudut syöttämään maksutietosi (luottokortti tai PayPal), mutta maksua ei mene, kun peruutat tilauksen labran jälkeen.

📘 **Dokumentaatio:**
- [Aloitus GitHub Copilotin kanssa](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
</details>


## 🎯 Labran tavoitteet

Labran lopussa:
- Olet luonut GitHub-tilin ja ottanut Copilotin käyttöösi
- Olet luonut toimivan sovelluksen kirjoittamatta itse riviäkään koodia
- Olet käyttänyt Copilotia ymmärtääksesi ja parantaaksesi olemassa olevaa ohjelmaa/koodia

## 💬 Vaihe 1 – Luodaan ympäristö projektille

**Tavoite:** 1. Luo ympäristö ja paikka koodille (**repository**), jossa voit testata ja kokeilla GitHub Copilotia  2. Luo tehtävänanto (**issue**)

<details>
<summary>🔹 <b>2️⃣ Luo tyhjä repo ja issue</b></summary>
      
- [ ]  Klikkaa profiilikuvasi oikeasta yläkulmasta ja valitse "Repositories" <br>
      <img width="258" height="67" alt="image" src="https://github.com/user-attachments/assets/432d8e28-e96c-4ec6-8c93-10db18ddb2b5" />
         
- [ ]  Klikkaa "New"-painiketta luodaksesi uuden repositoryn <br>
      <img width="191" height="94" alt="image" src="https://github.com/user-attachments/assets/6be9be56-4d73-4e80-a53e-1ec511b9be5c" /> <br>
      
- [ ]  1.Anna repositorylle nimi 2.Valitse "Add README" valinta "On" 3.Paina "Create repository" <br>
      <img width="467" height="671" alt="image" src="https://github.com/user-attachments/assets/6c264ca6-274f-451c-acf2-1660cb6856c6" /><br>

- [ ]  Luodaan tehtävänanto/kuvaus eli "Issue": Valitse ylävalikosta "Issues" <br>
      <img width="513" height="62" alt="image" src="https://github.com/user-attachments/assets/5732bb4e-3f46-4351-830d-36c51f522019" /> <br>

- [ ]  Ja tämän jälkeen "New issue" <br>
      <img width="256" height="46" alt="image" src="https://github.com/user-attachments/assets/c02a53f9-85c8-4ef6-9914-bc2eead556f0" />

- [ ]  Anna otsikoksi: Create a web app to manage inventory of a retail store
- [ ]  Anna kuvaukseksi: <br>
      Create an web app where user can manage an inventory. User can browse products, add and delete products and change the quantity of products. Make the app look modern and easy to use. Create also a local test database with 20 products pre populated <br>
      <img width="630" height="435" alt="image" src="https://github.com/user-attachments/assets/3c11073b-31d1-4a5f-bfff-4b4d000b40bf" />

</details>

## 🧩 Vaihe 2 – Laitetaan tekoäly töihin

**Tavoite:** Annetaan tehtävänanto (issue) Coding Agentintille tehtäväksi

<details>
<summary>🔹 <b>3️⃣ Anna issue Coding Agentille ja anna sen työstää sitä taustalla</b></summary>

Kun issue on luotu, voit antaa sen Copilot Coding Agentille ja katsoa, mitä tapahtuu:

- [ ] Klikkaa "Assign to Copilot" <br>
      <img width="455" height="328" alt="image" src="https://github.com/user-attachments/assets/a19ffcb6-02c3-450c-a3fe-f62fc9860e88" /><br>
- [ ] Klikkaa "Assign"<br>
      <img width="475" height="233" alt="image" src="https://github.com/user-attachments/assets/7ff48ee8-a024-42e0-be87-fe52418ef88e" /><br>
- [ ] Klikkaa "WIP..." (issuen tittelisi kanssa) -linkkiä seurataksesi mitä Coding Agent tekee <br>
      <img width="420" height="113" alt="image" src="https://github.com/user-attachments/assets/ded50f10-9698-4feb-81c4-5eb5a6678975" /><br>
- [ ] Coding Agent päivittää työtään tähän. Tutki tarkemmin klikkaamalla "View session": <br>
      <img width="383" height="134" alt="image" src="https://github.com/user-attachments/assets/0995db07-710b-41f1-a93a-2efffabaf695" /><br>
- [ ] Nyt voit:<br>
      1. Tarkkailla mitä Coding Agent tekee<br>
      2. Antaa vielä lisäehdotuksia tai muutoksia. Kirjoita tähän esimerkiksi "Target this web app for company selling..." <- jatka lausetta esim. motorcycles, skateboards tai jotain aivan muuta mitä haluat ohjelmassa näkeväsi.<br>
      <img width="477" height="658" alt="image" src="https://github.com/user-attachments/assets/6717f8ce-9e50-4004-a660-9920e2fb2208" /><br>
      Koko prosessi voi kestää yli 10 minuuttia, joten nyt voimme välillä tehdä muuta ja palata katstoaan tilannetta myöhemmin.
      
📘 [Tietoa GitHub Coding Agentista](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)

</details>

## 🧩 Vaihe 3 – Valmistellaan ympäristö, jossa testata ja muokata koodia

**Tavoite:** Avataan pilvipohjainen kehittäjän ympäristö (Codespaces), jossa voimme tutkia ja muokata koodia Visual Studio Codessa (VS Code)

<details>
<summary>🔹 <b>4️⃣ Avaa repository Codespacesissa ja tutki Copilotia VS Codessa</b></summary>

- [ ] Mene nettiselaimessa yksi askel taaksepäin (Coding Agentin työ näkymästä)
- [ ] Klikkaa "<>Code" ylävalikosta <br>
      <img width="125" height="77" alt="image" src="https://github.com/user-attachments/assets/56b3ab92-8374-4a90-88b4-be932593f08c" /><br>

- [ ] Klikkaa vihreää "Code"-painiketta, valitse Codespaces ja "Create Codespaces on main", odota ympäristön avautumista. <br>
      <img width="433" height="525" alt="image" src="https://github.com/user-attachments/assets/f1d5868f-beee-4321-b8ea-fc7ee971a229" />

- [ ] Kun Codespaces on luotu ja VS Code on avautunut voi ympäristö vaatia vielä seuraavia askeleita:<br>
      1. GitHub tilin yhdistämistä:<br>
      <img width="548" height="281" alt="image" src="https://github.com/user-attachments/assets/d8cca31f-f959-43f6-aa59-c04cffb494c5" /><br>
      2. GitHub Copilotin aktivoimista:
       <img width="330" height="168" alt="image" src="https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75" />     
      Tämän jälkeen kaikki on valmista ja voimme työskennellä Copilotin kanssa kehittäjän ympäristössä. Tapoja on monia, joista yksinkertaisin on suoraan chat ikkununassa oikeassa alareunassa (fontin kokoa voit kasvattaa painamalla Ctrl + ):<br>
      <img width="391" height="481" alt="image" src="https://github.com/user-attachments/assets/d8957fdc-50c3-4c52-82e2-2df26457bb06" /><br>
      1. Kirjoita käskyt/promptit Copilotille
      2. Valitse Copilot tila: Chat, Edit, Agent
      3. Valitse tekoälymalli
      4. Tämä symboli kertoo Copilotin tilan (aktiivinen/ei aktiivinen, 'miettii')

Nyt voimme kuitenkin palata katsomaan GitHub.com portaalia onko Coding Agent jo valmiina. Palataan tänne hetken kulutta

</details>

---

## 🧩 Vaihe 4 – Takaisin GitHub.comiin katsomaan ja hyäksymään Coding Agentin muutokset
<details>
<summary>🔹 <b>6️⃣Tutki mitä Coding Agent on tehnyt ja hyväksy sen tekemä pull request</b></summary>

Nyt Coding Agent on saanut työnsä valmiiksi ja voit tutustua lopputulokseen

- [ ] Valitse ylävalikosta "Pull requests" <br>
      <img width="494" height="56" alt="image" src="https://github.com/user-attachments/assets/e7efabcd-9f6d-45c4-9194-c3e127d7b016" /><br>
- [ ] Klikkaa auki pull request <br>
      <img width="688" height="160" alt="image" src="https://github.com/user-attachments/assets/eb2846f1-e5d6-4669-b5cf-1a4b54e13dc0" /><br>
- [ ] Tutki Copilotin tuottamaa koodia<br>
- [ ] Selaa näkymää alas ja klikkaa "Ready for review" <br>
      <img width="701" height="518" alt="image" src="https://github.com/user-attachments/assets/4d4fb966-d2a0-41ba-88c6-d598ad72ce9d" /><br>
- [ ] Tämän jälkeen "Merge pull request"<br>
      <img width="701" height="482" alt="image" src="https://github.com/user-attachments/assets/5eef7210-e81c-4dda-95b4-b692af464c75" /><br>
- [ ] Ja lopuksi "Confirm merge" <br>
      <img width="687" height="334" alt="image" src="https://github.com/user-attachments/assets/d069dcaa-61ad-4b1c-845d-34f3e50ed87a" /><br>

Nyt Copilotin tekemä koodi on hyväksytty projektiin / repositoryyn ja voimme tutkia, ajaa ja muokata sitä. Joten mennään takaisin kehitysympäristöön (Codespaces & VS Code).
</details>

---

## 🧮 Vaihe 5 – Ladataan muutokset kehitysympäristöön

<details>
<summary>🔹 <b>7️⃣ Takaisin Codespacesiin päivittämään muutokset sekä tutkimaan ja muokkaamaan koodia</b></summary>

- [ ] Lataa Copilotin muutokset vasemman alareunan valikosta (Synchronize Changes) <br>
      <img width="442" height="128" alt="image" src="https://github.com/user-attachments/assets/5c258cad-c81f-473c-a0b2-17e41c02e25d" /><br>
      <img width="583" height="178" alt="image" src="https://github.com/user-attachments/assets/15108c6d-9ee5-459e-b93b-21c5fd7d4e74" /><br>

- [ ] Nyt voit ajaa Copilotin tekemää sovellusta. Miten? Kysy asia Copilotilta!
- [ ] Huomioi, että voit hyväksyä suoraan Copilotin ehdottamia komentoja terminaalissa.
- [ ] Tee koodimuutoksia. Lisää vaikka nappi, joka räjäyttää konfettia ruudulle?
     ("Add button that will blow confetti on the screen")
Testaa näitä jos haluat:
- [ ] Avaa jokin kooditiedosto, valitse jokin koodirivi ja pyydä Copilotia selittämään tämä koodi.
- [ ] Voit myös esimerkiksi pyytää Copilotia selittämään projektin sisällön liiketoiminnan näkökulmasta ja muodostamaan siitä vaikka HTML-dokumentaatioksi.

</details>

---

## 🧮 Vaihe 6 – Muokkaa sovellusta enemmän 

<details>
<summary>🔹 <b>8️⃣ Nyt, kun osaat jo tehdä issuen ja antaa sen Copilot Coding Agentille tehtäväksi kokeile luoda uusi issue tai usemapi ja annan ne agentille tehtäväksi. Muokataan lisää myös VS Codessa</b></summary>

- [ ] Katso vaiheen 1 issuen luonti ja vaihe 2. Keksi muutoksia, luo vaikka usemapi issue ja anna ne agentille tehtäväksi. 
- [ ] Voit seurata agentin työn etenemistä myös VS Codessa valitsemalla vasemman reunan valikosta "Agent sessions"<br>
      <img width="179" height="206" alt="image" src="https://github.com/user-attachments/assets/06855fff-d387-4b2c-a168-dae6cc55629a" /><br>

- [ ] Sillä välin, kun agentit tekevät työtään koita tehdä muutoksia VS Coden Copilotilla. Pyydä sitä tekemään muutoksia, kuten lisämään tuotteisiin kuvat tai jotain aivan muuta.

</details>

---

## 🧠 Jaa havaintosi & keskustelua

- [ ] Mikä ero on Coding Agentilla ja Copilot Agent modella?
- [ ] Mikä yllätti sinut eniten Copilotin toiminnassa?  
- [ ] Mikä ominaisuus tuntui luontaisimmalta tai hyödyllisimmältä?
- [ ] Voisiko tästä olla hyötyä myös muille kuin ohjelmoijille?

---

## ✅ Tarkistuslista

| Vaihe | Kuvaus | Tehty |
|------|-------|------|
| 1 | Luodaan ympäristö projektille| ☐ |
| 2 | Laitetaan tekoäly töihin | ☐ |
| 3 | Valmistellaan ympäristö, jossa testata ja muokata koodia | ☐ |
| 4 | Takaisin GitHub.comiin katsomaan ja hyäksymään Coding Agentin muutokset | ☐ |
| 5 | Muokkaa sovellusta Copilotilla VS Codessa | ☐ |
| 6 | Muokkaa sovellusta enemmän | ☐ |
| 🧠 | Jaa havaintosi | ☐ |

---

Mukavaa kokeilua ja Copilotin tutkimista! 🎉
