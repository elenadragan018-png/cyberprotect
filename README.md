# 🔒 Cyber Protect — Securitate cibernetică avansată (clasa a X-a)

**Resursă educațională digitală deschisă (RED)**
Autor: prof. Drăgan Elena
Versiune: **v1.1** · iunie 2026
Licență: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ro)

---

## 📖 Ce este Cyber Protect?

Cyber Protect este o resursă educațională digitală deschisă, concepută pentru elevii de **clasa a X-a** care studiază disciplina Informatică sau TIC. Resursa aprofundează conceptele de securitate cibernetică introduse anterior (în resursa-pereche „Cyber Start" pentru clasa a IX-a) și extinde aria spre teme contemporane critice:

- 🔍 **OSINT** — investigația din surse deschise
- 👣 **Amprenta digitală** — audit și control
- 🎭 **Deepfake** — recunoaștere și verificare
- 📰 **Dezinformarea** — fact-checking și SIFT
- 🔐 **Securitatea avansată a conturilor** — passkeys, FIDO2
- 🎯 **Ingineria socială avansată** — spear phishing, BEC, vishing
- 🪪 **Managementul identității digitale** — SSO, separarea identităților
- 📱 **Securitatea pe dispozitive mobile** — permisiuni, spyware
- 🏆 **Evaluare sumativă** + certificat de participare PDF

Resursa este aliniată cu cadrul DigComp 2.2 și cu programa de Informatică / TIC pentru clasa a X-a.

---

## 🚀 Cum se folosește

Resursa este un **fișier HTML autonom** care funcționează direct în browser, fără server și fără instalare.

### Pentru elev
1. Descarcă fișierul `index.html`.
2. Deschide-l într-un browser modern (Chrome 90+, Firefox 90+, Edge 90+, Safari 14+).
3. Navighează între lecții din meniul principal sau din butoanele „Anterioară / Următoarea".
4. La final, parcurge evaluarea sumativă (L10) și, la promovare (prag 70%), generează certificatul PDF.

### Pentru profesor
- Poate fi folosită ca **opțional / Curriculum la Decizia Școlii (CDȘ)** cu titlul „Securitate cibernetică avansată", 1 oră/săptămână, semestrial sau anual.
- Poate fi folosită complementar la TIC din trunchiul comun pentru aprofundarea capitolelor „Societate digitală", „Comunicare și colaborare digitală", „Evaluarea critică a informației".
- Studiile de caz din secțiunea „Despre" (Bellingcat/MH17, Neptun Deep, Arup, Pegasus) pot fi folosite ca activități introductive sau ca temă de sinteză.

---

## 🆕 Noutăți v1.1 (iunie 2026)

Această versiune introduce 6 îmbunătățiri majore față de v1.0:

### 1. Lecția 1 (OSINT) — distincție explicită OSINT defensiv vs. stalking
S-a adăugat un nou avertisment în chenar roșu care explică diferența între un investigator etic și un stalker pe trei criterii (scopul, sursa, consimțământul și impactul). Regula practică:

> OSINT-ul în scop educațional și defensiv trebuie utilizat doar asupra informațiilor public-accesibile, cu respectarea legislației privind viața privată (GDPR, Codul penal român — art. 226, art. 208) și a demnității persoanei vizate.

### 2. Lecția 3 (Deepfake) — Activitatea 3: Detector practic
S-a adăugat o activitate interactivă: elevul vede 3 portrete (1 real, 2 generate de AI) și trebuie să identifice pe cel real. Fiecare opțiune oferă feedback explicativ cu lista indicatorilor vizibili (asimetria urechilor, reflexiile diferite ale ochilor, structura dinților, text borfait, mâini cu degete în plus etc.).

### 3. Lecția 6 (Passkeys) — comparație vizuală pe 3 coloane
S-a adăugat o comparație vizuală clară între cele trei niveluri:

| Parolă (slab) | Parolă + 2FA (mai sigur) | Passkey FIDO2 (rezistent la phishing) |
| --- | --- | --- |
| Poate fi furată | Adaugă un al doilea factor | Rezistent la phishing prin construcție |
| Reutilizabilă pe alte conturi | SMS vulnerabil la SIM swap | Legat criptografic de domeniu |
| Phishabilă | Cod TOTP phishabil pe site fals | Pe site fals, pur și simplu nu răspunde |

S-a adăugat și o notă explicativă scurtă despre ce înseamnă FIDO2 (Fast IDentity Online, generația 2).

### 4. Lecția 8 (Identitate digitală) — Digital footprint timeline
S-a adăugat o secțiune nouă (5) cu o linie temporală vizuală pe 4 etape de vârstă:

- **12 ani** — primul cont pe rețea socială
- **14 ani** — postare impulsivă, regretată
- **18 ani** — aplicația la facultate
- **23 ani** — primul interviu de angajare

Fiecare nod descrie cum se acumulează amprenta digitală. Secțiunea include și un exercițiu de proiecție de 5 minute (4 propoziții completate de elev).

### 5. Certificat PDF — Nivel: Avansat · Clasa: a X-a
S-au adăugat două „badge"-uri vizibile pe certificat (și în previzualizarea on-screen) care marchează nivelul resursei și clasa, pentru un aspect mai oficial.

### 6. Secțiunea „Despre" — Impact educațional estimat
S-a adăugat o secțiune nouă cu 5 direcții măsurabile de transformare cognitivă și comportamentală vizate de resursă:

1. Dezvoltarea gândirii critice asupra surselor digitale
2. Recunoașterea dezinformării și a conținutului sintetic
3. Protecția identității digitale pe termen lung
4. Utilizarea responsabilă și etică a tehnologiilor AI
5. Creșterea rezilienței la ingineria socială avansată

Plus indicatori de evaluare a impactului (rata de promovare L10, distribuția mențiunilor, capacitatea elevului de a aplica metodologia OSINT și SIFT pe un caz real).

---

## 🛠️ Cerințe tehnice

- **Browser modern**: Chrome 90+, Firefox 90+, Edge 90+, Safari 14+
- **Conexiune Internet la prima încărcare** — pentru fonturi Google (Sora, Manrope, JetBrains Mono) și biblioteca jsPDF din CDN
- **Funcționare offline** după prima vizită (resursele se cachează)
- **JavaScript activat** (pentru activități interactive și generarea PDF-ului)

### Date stocate local
Resursa folosește `localStorage` pentru a reține:
- Progresul lecțiilor vizitate
- Numele introdus pentru certificat
- Scorul la evaluarea sumativă
- Preferința de temă (light/dark)

Nu se trimit date către niciun server al autorului. Singurele cereri externe sunt către `fonts.googleapis.com` și `cdnjs.cloudflare.com`.

---

## 📚 Structura cursului

| # | Titlu | Competență specifică |
| --- | --- | --- |
| L1 | OSINT — investigație din surse deschise | CS 1.1 |
| L2 | Amprenta digitală — audit și control | CS 1.2 |
| L3 | Deepfake — recunoaștere și verificare | CS 2.1 |
| L4 | Dezinformare — fact-checking | CS 2.2 |
| L5 | Recapitulare intermediară | — |
| L6 | Securitatea avansată a conturilor | CS 3.1 |
| L7 | Inginerie socială avansată | CS 3.2 |
| L8 | Managementul identității digitale | CS 4.1 |
| L9 | Securitate pe dispozitive mobile | CS 4.2 |
| L10 | Evaluare sumativă + Certificat | Toate (CS 1.1 — CS 4.2) |

---

## 📄 Despre certificatul de participare

Certificatul PDF generat la finalul evaluării sumative (prag de promovare: **7/10**, adică 70%) este un document de tip **„attestation de parcours"** — confirmă parcurgerea resursei și atingerea pragului de promovare. **Nu reprezintă un act de studii recunoscut oficial** și nu se substituie evaluării realizate de cadrul didactic.

Mențiuni posibile pe certificat:
- **7–8 / 10** → ✅ Promovat
- **9 / 10** → ⭐ Mențiune
- **10 / 10** → 🏆 Excelență

Toate certificatele poartă: Nivel: Avansat · Clasa: a X-a.

---

## ⚖️ Licență

Acest material este licențiat sub **[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ro)**.

**Aceasta înseamnă că ai voie să**:
- Distribui — copiezi și redistribui materialul în orice format
- Adapezi — refaci, transformi și construiești pe baza materialului

**În următoarele condiții**:
- **Atribuire** — trebuie să dai credit autorului (prof. Drăgan Elena), să indici licența și să marchezi modificările făcute
- **Necomercial** — nu poți folosi materialul în scopuri comerciale
- **Distribuie-în-condiții-identice** — dacă remixezi, transformi sau construiești, trebuie să distribui sub aceeași licență

---

## 📬 Feedback și sugestii

Resursa este într-o etapă activă de dezvoltare. Pentru semnalări de erori, sugestii sau colaborare didactică, contactați autorul prin canalele indicate în secțiunea „Despre" a aplicației.

---

*🔒 Cyber Protect v1.1 · © 2026 prof. Drăgan Elena · CC BY-NC-SA 4.0*
