# 🎯 Uzdevums 13 — Tavs Custom Gem robots ar “Knowledge” dokumentu + tests + koplietošana

## 🎯 Mērķis
Šī uzdevuma mērķis ir, lai tu **pats/pati izveidotu savu Gem robotu** (nevis tikai nokopētu gatavu piemēru) un pārbaudītu, kā tas strādā praksē, kad Gemam ir:

1) **savā uzvednē (Instructions)** skaidri noteikta loma un atbilžu formāts,  
2) **pievienots vismaz 1 dokuments** kā zināšanu bāze (Knowledge / Files),  
3) reāla **testēšana ar jautājumiem** un neliela iterācija (uzlabošana),  
4) **koplietošana ar kolēģi**.

Papildus informācija: **līdzīga funkcionalitāte (roboti + faili/zināšanu bāze)** ir arī citos MI rīkos, bet tās pieejamība var atšķirties atkarībā no platformas un plāna (**bezmaksas / maksas / uzņēmuma licences**).

> Instruktors paralēli veidos arī savu Gem robotu un, ja būs nepieciešams, to **koplietos ar mācību dalībniekiem** kā piemēru/atbalstu.

---

## ✅ 0. Svarīgi par datiem (OBLIGĀTI)
Pirms pievieno dokumentu vai raksti instrukcijas:

- **NEizmanto sensitīvu informāciju** (personas dati, paroles, API atslēgas, līgumu detaļas, klientu saraksti, cenas, iekšējie KPI utt.).
- Ja ņem dokumentu no darba vides — izmanto **anonimizētu** versiju vai publiski pieejamu materiālu.
- Ja dokumentu atrod internetā — pārliecinies, ka tas ir **publiski pieejams** un to drīkst izmantot apmācībām.

---

## ✅ 1. Izvēlies ideju savam Gem robotam (izvēlies 1)
Tev jāizdomā Gems, ko tu reāli varētu izmantot darbā vai mācībās. Vari ņemt jebkādu tēmu.

### Ideju piemēri (vari izmantot vai izdomāt savu)
- “Sapulču protokolētājs” (no pievienotas sapulces šablona + noteikumiem)
- “Iekšējo noteikumu skaidrotājs” (no politikas dokumenta)
- “Projekta plāna asistents” (no projekta šablona + fāzēm)
- “Mācību materiālu veidotājs” (no lekcijas konspekta vai PDF)
- “Produkta aprakstu un FAQ ģenerators” (no produkta specifikācijas)
- “Drošības checklists” (no publiska drošības vadlīniju dokumenta)
- “CV / motivācijas vēstules uzlabotājs” (no publiskiem ieteikumiem + tavas struktūras prasībām)

---

## ✅ 2. Sagatavo 1 dokumentu (Knowledge / Files)
Tev jāizvēlas vismaz **1 dokuments**, ko piesaistīsi Gemam.

### Dokumenta varianti (izvēlies 1)
- Tavs dokuments (anonimizēts): piemēram, procesa apraksts, šablons, rokasgrāmata, mācību materiāls.
- Publisks dokuments no interneta: piemēram, rokasgrāmata, specifikācija, vadlīnijas, publisks PDF.
- Tavs paša izveidots dokuments: vari ātri uzrakstīt 1–2 lappuses “mini rokasgrāmatu” savam Gemam.

### Mini-šablons (ja veido dokumentu pats/pati)
Iekopē Word/Google Docs un aizpildi 10–15 min laikā:

- Nosaukums
- Mērķis (kas tas ir, kam tas paredzēts)
- Definīcijas / termini
- 5–10 galvenie noteikumi vai punkti
- 2–3 piemēri (pareizi / nepareizi, vai “pirms/pēc”)
- Biežākie jautājumi (FAQ) 5 punkti

Saglabā kā **PDF** (vai atstāj DOCX — kā atļauj platforma).

---

## 🤖 3. Izveido jaunu Custom Gem
## ✅ Darbība
1. Atver Gemini (vai citu rīku, kur veido robotus/Gem)
2. Dodies uz **Gems / Gem roboti** (vai līdzīgu sadaļu)
3. Izvēlies **+ Jauns Gem robots**
4. Piešķir:
   - **Nosaukumu**
   - **Aprakstu**
5. Atrodi sadaļu **Knowledge / Files / Pievienot failu**
6. Pievieno savu dokumentu (vismaz 1)
7. Ielīmē instrukcijas (skat. 4. sadaļu)
8. Saglabā Gem

> Piezīme: citos MI rīkos līdzīga funkcija var saukties citādi (piem., “Assistants”, “Bots”, “Projects”, “Knowledge”, “Files”). Dažkārt failu pievienošana un koplietošana var būt pieejama tikai noteiktos plānos.

---

## 🧩 4. Gem instrukcijas (tev jāaizpilda pašam/pati)
Zemāk ir “karkass”. Tavs uzdevums: **aizstāt [..] ar savu saturu**, lai instrukcija būtu reāli lietojama.

### ✅ “Norādījumi / Instructions” (kopē/ielīmē un aizpildi)
```
Tu esi “[TAVA GEMA LOMA]” — palīgs, kas strādā ar pievienoto dokumentu kā zināšanu bāzi.

## Konteksts
- Kam paredzēts: [piem., manai komandai / manām mācībām / klientu komunikācijai]
- Situācija: [1–3 teikumi par tipisko situāciju]
- Mērķis: [ko tieši Gemam jāpaveic lietotāja vietā / kopā ar lietotāju]

## Ko tu drīksti un ko nedrīksti
- Balsties uz pievienoto dokumentu (Knowledge/Files) kā galveno avotu.
- Ja dokumentā nav informācijas: nespekulē — pasaki “Dokumentā nav minēts” un uzdod precizējošu jautājumu vai pasaki, ko vajag noskaidrot.
- Neizmanto sensitīvu informāciju; ja lietotājs iedod sensitīvus datus, brīdini un piedāvā anonimizēt.

## Tavi uzdevumi (kā Gem)
1) [Uzdevums #1]
2) [Uzdevums #2]
3) [Uzdevums #3]
(ieteicams 3–6 punkti)

## Atbilžu stils
- Atbildi latviešu valodā.
- Raksti īsi un strukturēti.
- Ja iespējams, dod 1 piemēru (paraugs / teksts / tabula / checklist).
- Beigās uzdod 1 precizējošu jautājumu.

## Atbilžu formāts (obligāts)
- Īss kopsavilkums (1–3 teikumi)
- Ko saka dokuments? (konkrēti punkti)
- Ko tas nozīmē praksē? (nākamie soļi / ieteikumi)
- Atvērtie jautājumi / trūkstošā informācija (2–6 punkti)
- Nākamais solis (1–3 punkti)
```

---

## 🧪 5. Testēšana — vai Gems izmanto dokumentu
## ✅ Mērķis
Pārbaudīt, ka Gem:
- atsaucas uz dokumenta saturu (cik iespējams),
- neizdomā, ja dokumentā nav informācijas,
- atbild strukturēti un konsekventi.

### Testa jautājumi (izvēlies 3–5 un pielāgo)
Kopē/ielīmē savā Gem čatā:

1)
```
Izdari īsu kopsavilkumu par [tēma] balstoties uz pievienoto dokumentu.
Beigās uzdod 1 jautājumu, lai precizētu kontekstu.
```

2)
```
Pamatojoties uz dokumentu, izveido man checklist (5–10 punkti) priekš [situācija].
```

3)
```
Man ir situācija: [apraksts 3–6 teikumos].
Ko dokuments iesaka darīt? Iedod soļus un riskus.
```

4) (apzināti “trūkstošs” jautājums)
```
Kāds ir [kaut kas, kas noteikti nav dokumentā]?
```
Mērķis: pārliecināties, ka Gems pasaka “nav minēts” un neizdomā.

5)
```
Uzraksti 2 variantus (neitrāls / formāls) tekstam: [e-pasts / paziņojums / instrukcija], balstoties uz dokumenta principiem.
```

---

## 🔁 6. Iterācija (obligāta) — uzlabo instrukcijas un pārtestē
Tev jāparāda, ka tu **uzlaboji Gemu** pēc testēšanas.

### ✅ 1) Atrodi vājumu
Piemēri:
- Gems atbild pārāk gari
- Gems neuzdod jautājumu beigās
- Gems dod “vispārīgas frāzes” un maz atsaucas uz dokumentu
- Gems nesaprot, kādā formātā jāatbild (tabula / checklist / soļi)

### ✅ 2) Papildini instrukcijas (1–3 teikumi vai punkti)
Piemēram:
- “Vienmēr iekļauj tabulu ar kolonnām X/Y/Z”
- “Vienmēr atsaucies uz dokumenta sadaļām/terminiem, ja tie tur ir”
- “Atbildes max 1200 zīmes, ja vien lietotājs neprasa detalizētāk”
- “Ja dokuments neatbild, piedāvā 3 jautājumus, ko uzdot ekspertam/piegādātājam”

### ✅ 3) Sāc JAUNU sarunu un uzdod 1–2 jautājumus atkārtoti
Salīdzini “pirms” un “pēc”.

---

## 🤝 7. Koplietošana ar kolēģi (obligāta)
1) **Koplieto** savu Gem robotu ar vismaz 1 kolēģi (izmanto platformas Share/Invite funkciju).
2) Palūdz kolēģim:
   - izmēģināt tavu Gem ar 2 jautājumiem,
   - pateikt 1 ieteikumu uzlabojumam.
3) Tev pašam/pati **vēlams** izmēģināt kāda cita kolēģa Gem robotu (ne savu):
   - uzdod 2 jautājumus,
   - pieraksti, kas patika / kas traucēja.

> Piezīme: koplietošanas iespējas un pieejamība var atšķirties pa rīkiem un plāniem (bezmaksas/maksas/organizācijas konts). Ja tieša koplietošana nav pieejama, vienojieties par alternatīvu: piemēram, kolēģim nosūti Gem instrukciju tekstu + dokumentu un lai viņš izveido klonu.

---

## 📌 Gala rezultāts (ko iesniegt / nodot instruktoram)
Iesniedz (piem., čatā vai LMS):

1) Gem nosaukums + 1 teikuma apraksts  
2) Kādu dokumentu izmantoji (nosaukums + avots: “mans dokuments” vai “publiski internetā”)  
3) Gem instrukcijas (final versija)  
4) 2–3 testa jautājumi + īss secinājums (kas strādā / kas nestrādā)  
5) 1 iterācijas uzlabojums (ko tieši pamainīji instrukcijās)  
6) Apstiprinājums, ka Gem tika koplietots ar kolēģi + 1 kolēģa atsauksme (1–3 teikumi)

---

# ✅ Mini-checklist (paškontrole)
Atzīmē “Jā/Nē”:

- [ ] Manam Gem ir skaidrs nosaukums, loma un mērķis
- [ ] Gemam ir pievienots vismaz 1 dokuments (Knowledge/Files)
- [ ] Gem atbild latviski un strukturēti
- [ ] Gem neizdomā faktus, ja dokumentā nav informācijas
- [ ] Es veicu vismaz 1 iterāciju (uzlabojumu) un pārtestēju
- [ ] Es koplietoju Gem ar kolēģi
- [ ] Es (vēlams) izmēģināju kāda cita kolēģa Gem

---

# Neliela retrospekcija
1) Kas bija grūtākais: dokumenta izvēle, instrukciju uzrakstīšana vai testēšana? Kāpēc?  
2) Kāds būtu nākamais uzlabojums, lai Gems kļūtu “darba gatavs” (piem., vēl 1 dokuments, precīzāks formāts, stingrāki noteikumi)?
