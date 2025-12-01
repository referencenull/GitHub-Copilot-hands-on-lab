# 🚀 GitHub Copilot Hands-On Lab - <b>Microsoft x Software Finland</b>

Tervetuloa **GitHub Copilot Hands-On Lab** -työpajaan!  
Tämä haaste johdattaa sinut Copilotin ominaisuuksien läpi — *Ask*, *Edit* ja *Plan* -tiloista aina *Copilot Coding Agent* -agenttiin saakka.  
Työskentelet omassa repossasi, kokeilet vapaasti ja näet, miten Copilot muuttaa työskentely- ja kehitystapojasi.

---

## 📋 Esivaatimukset

Ennen kuin aloitat tämän labran, varmista että sinulla on:
- [ ] GitHub-tili
      <details>
      <summary>🔹 <b>0️⃣ Luo GitHub-tili, jos sinulla ei vielä ole</b></summary>
                  Mene osoitteeseen: github.com  
                  Klikkaa oikeasta yläkulmasta: Sign up <br><br>
                  <img width="250" height="105" alt="image" src="https://github.com/user-attachments/assets/a66d7349-1eac-4ec7-a119-7860e5dc88ef" />
                  <br>
                  Täytä vaaditut tiedot ja seuraa ohjeita, ja kirjaudu sisään
      </details>

- [ ] GitHub Copilot -lisenssi
      <details>
      <summary>🔹 <b>1️⃣ Varmista, että sinulla on GitHub Copilot käyttöoikeus</b></summary>
                        Avaa linkki: [GitHub Copilot · Plans & pricing](https://github.com/features/copilot/plans?ref_product=copilot) <br> ja valitse Keskimmäisestä "Pro"                         vaihtoehdosta "Try for 30 days free" <br>
                        Joudut syöttämään maksutietosi (luottokortti tai PayPal), mutta maksua ei mene, kun peruutat tilauksen labran jälkeen.

📘 **Dokumentaatio:**
- [Aloitus GitHub Copilotin kanssa](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
</details>


## 🎯 Labran tavoitteet

Labran lopussa:
- Olet luonut GitHub-tilin ja ottanut Copilotin käyttöösi
- Olet luonut toimivan sovelluksen kirjoittamatta riviäkään koodia itse
- Olet käyttänyt Copilotia ymmärtääksesi ja parantaaksesi olemassa olevaa koodia

## 💬 Vaihe 1 – Kopioi ja luo repository (koti koodille)

**Tavoite:** Kopioi/luo repository, jossa voit testata ja kokeilla GitHub Copilotia

<details>
<summary>🔹 <b>2️⃣ Luo tyhjä repo ja issue</b></summary>

Kokeile kysymyksiä:
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

- [ ]  Anna otsikoksi: <b>Create a web app to manage inventory of a retail store</b>
- [ ]  Anna kuvaukseksi: <br>
      <b>Create an web app where user can manage an inventory. User can browse products, add and delete new products and change the quantity of products.
- Make the app look modern and easy to use.
- Create also a local test database with 20 products pre populated </b><br>
      <img width="630" height="435" alt="image" src="https://github.com/user-attachments/assets/3c11073b-31d1-4a5f-bfff-4b4d000b40bf" />

</details>

## 🧩 Vaihe 2 – Laitetaan tekoäly töihin

**Tavoite:** Annetaan Coding Agentin hoitaa työt.

<details>
<summary>🔹 <b>3️⃣ Anna issue Coding Agentille ja anna sen työstää sitä taustalla</b></summary>

Kun issue on luotu, voit antaa sen Copilot Coding Agentille ja katsoa, mitä tapahtuu:

- [ ] Klikkaa "Assign to Copilot" <br>
      <img width="486" height="265" alt="image" src="https://github.com/user-attachments/assets/db85f0a1-eb39-4d05-ab2a-7e72e5fd73a1" />
      
- [ ] Halutessasi: Kirjoita lisäohje "Optional prompt" -kenttään
- [ ] Klikkaa "Assign"

Seuraa Coding Agentin etenemistä:
- [ ] Klikkaa "WIP..." (issuen tittelisi kanssa) -linkkiä <br>
      <img width="94" height="89" alt="image" src="https://github.com/user-attachments/assets/e18fa4c6-ee0c-45a6-a374-2c20c0a3e413" />

- [ ] Coding Agent päivittää työnsä tähän, syvenny klikkaamalla "View session": <br>
      <img width="314" height="118" alt="image" src="https://github.com/user-attachments/assets/dafceb61-2153-4373-acc8-3e1dc206fe1f" />

- [ ] Tutki, mitä Coding Agent tekee.
      Koko prosessi voi kestää yli 10 minuuttia, joten voit tehdä muuta ja palata myöhemmin.
      
📘 [Tietoa GitHub Coding Agentista](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)

</details>

## 🧩 Vaihe 3 – Repo Codespacesiin

**Tavoite:** Käytä Copilotia Visual Studio Codessa GitHubin pilvipohjaisessa Codespaces-ympäristössä.

<details>
<summary>🔹 <b>4️⃣ Avaa repo Codespacesissa ja tutki Copilotia VS Codessa</b></summary>

- [ ] Klikkaa "<>Code" ylävalikosta  
- [ ] Klikkaa vihreää "Code"-painiketta, valitse Codespaces ja "Create Codespaces on main", odota ympäristön avautumista. Codespaces on sinulle automaattisesti luotu pilvikehitysympäristö.
- [ ] Kun VS Code on avattu, GitHub Copilot on lähes valmis ja löytyy ruudun oikeasta reunasta, mutta sinun tulee vielä yksi asetus aktivoida oikeasta alakulmasta.
       <img width="330" height="168" alt="image" src="https://github.com/user-attachments/assets/764d62d5-f0e9-4cb0-b6b2-113f63bdbf75" />
       
Nyt kaikki on valmista:
- [ ] Generoi ohjetiedosto Copilotille klikkaamalla "Generate agent insctructions" <br>
      <img width="236" height="200" alt="image" src="https://github.com/user-attachments/assets/15ee7203-c44a-4a0e-84fb-9bbf31a96bc1" /> <br>
      
- [ ] Seuraa Copilotin toimintaa ja hyväksy sen ehdotukset, kun sitä tarvitaan (esim. komennot konsoliin). Se voi myös kysyä lisätietoja sinulta.
- [ ] Kun Copilot on valmis, hyväksy code-klikkaamalla vihreää "Keep"-painiketta
- [ ] Tutki copilot-instructions.md-tiedostoa. Täällä voit määritellä yleiset ohjeet Copilotille esim. koodausstandardit, kehitystyökalut, prosessit jne.

</details>
<details>
<summary>🔹 <b>5️⃣ Tutki Copilotin eri tiloja</b></summary>

- [ ] Copilot tarjoaa useita tapoja työskennellä: Ask, Edit ja Agent.
      
Kyselytila (Ask Mode)

Ask-tila on suunniteltu nopeisiin, kontekstuaalisiin vastauksiin ohjelmointikysymyksiin. Voit korostaa koodia, kirjoittaa kysymyksen ja saada selityksiä, ehdotuksia tai koodiesimerkkejä ilman, että k[...]

Muokkaustila (Edit Mode)

Edit-tilassa voit tehdä tarkkoja koodimuutoksia kuvailemalla toivotut muutokset luonnollisella kielellä. Copilot generoi muokkaukset, joita voi hyväksyä tai hylätä.

Agent-tila (Agent Mode)

Agent-tila on näistä tehokkain ja itsenäisin. Sen avulla Copilot voi toteuttaa laajoja tehtäviä kuten ominaisuuksien rakentamista, bugien korjausta tai kokonaisen sovellusosion luomista.

</details>

---

## 🧩 Vaihe 4 – Takaisin GitHub.comiin ja Coding Agentiin
<details>
<summary>🔹 <b>6️⃣Tutki mitä Coding Agent on tehnyt ja hyväksy sen tekemä pull request</b></summary>

Nyt Coding Agent on saanut työnsä valmiiksi ja voit tutustua lopputulokseen

- [ ] Mene "Pull requests" ylävalikkoon, ja avaa näkyvä pull request  
- [ ] Tutki Copilotin tuottamaa koodia, selaa alas ja klikkaa "Ready for review" ja sitten "Merge pull request" kun se on vihreänä ja lopuksi "Confirm merge" 

Nyt Copilotin tekemä koodi on siirtynyt omaan koodipohjaasi
</details>

---

<details>
<summary>🔹 <b>7️⃣ Takaisin Codespacesiin tutkimaan ja muokkaamaan koodia</b></summary>

- [ ] Vasemman reunan valikosta avaa "Source control" ja päivitä Copilotin tekemät muutokset <br>
      <img width="357" height="274" alt="image" src="https://github.com/user-attachments/assets/d3ffa87c-c1ae-4f16-ae30-86b233b385ef" /> <br>

- [ ] Nyt voit ajaa Copilotin tekemää sovellusta. Miten? Kysy asia Copilotilta! Voit käyttää suoraan sen ehdottamia komentoja konsolissa.
- [ ] Tee koodimuutoksia. Lisää vaikka nappi, joka räjäyttää konfettia ruudulle? Hyväksy koodiehdotukset klikkaamalla vihreää "Keep".
     ("Add button that will blow confetti on the screen")
- [ ] Avaa jokin kooditiedosto, valitse jokin koodirivi ja pyydä Copilotia selittämään koodia.
- [ ] Voit myös pyytää Copilotia selittämään projektin sisällön liiketoiminnan näkökulmasta, vaikka HTML-dokumentaatioksi.

</details>

---

## 🧮 Vaihe 5 – Muokkaa sovellusta Copilot Agentilla VS Codessa

<details>
<summary>🔹 <b>8️⃣ Muokkaa sovellusta luomalla uusi issue ja anna se Coding Agentiin taustatyöhön</b></summary>

- [ ] VS Coden vasemman valikon GitHub-kuvakkeesta paina "+" luodaksesi uuden issuen  <br>
      <img width="252" height="166" alt="image" src="https://github.com/user-attachments/assets/128bcfca-44c4-49ed-99b9-a8f620fa6311" /> <br>
      Muuta otsikoksi "Lisää kuvia" <br>
      Kuvaus esim. "Lisää tuotteisiin kuvia. Lisää myös testikuvia tietokantaan" <br>
      Luo issue painamalla check-merkkiä <br>
      <img width="186" height="60" alt="image" src="https://github.com/user-attachments/assets/4c0bee8c-1688-4246-995a-19a5ba2f2e8b" /> <br>

- [ ] Avaa uusi issue ja anna se Copilotin työstettäväksi. Seuraa sen etenemistä.
- [ ] Seuraa projektin etenemistä esim. vasemman valikon "Agent sessions" -kohdasta
- [ ] Kuten aiemmin, näet etenemisen myös GitHub.comissa pull requestien kautta.
- [ ] Voit jälleen pyytää Copilotia selittämään koodia klikkaamalla koodirivejä.

</details>
---

## 🧠 Vapaaehtoinen 1 – Kokeile uudestaan luoda uusi repo ja ratkaisun. Panosta kuvauksiin repoon, README:hen ja issueihin.

---

## 🧠 Vapaaehtoinen 2 – Jaa havaintosi

- [ ] Mikä yllätti sinut eniten Copilotin toiminnassa?  
- [ ] Tuottivatko eri mallit selvästi erilaisia tuloksia?  
- [ ] Mikä ominaisuus tuntui luontaisimmalta tai hyödyllisimmältä?

---

## ✅ Tarkistuslista

| Vaihe | Kuvaus | Tehty |
|------|-------|------|
| 1 | Luo repo ja issue| ☐ |
| 2 | Anna issue coding agentille | ☐ |
| 3 | Avaa koodi Codespacesissa | ☐ |
| 4 | Hyväksy Coding Agentin muutokset (mergaa pull request) | ☐ |
| 5 | Muokkaa sovellusta Copilotilla VS Codessa | ☐ |
| Vapaaehtoinen 1| Kokeile kaikki uudestaan | ☐ |
| ✨ | Jaa havaintosi | ☐ |

---

Mukavaa kokeilua ja Copilotin tutkimista! 🎉
