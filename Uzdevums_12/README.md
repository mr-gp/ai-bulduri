# 🎯 Uzdevums 12 — Advancēts Custom Gem ar failu (zināšanu bāze) + izvērtējums + ieviešanas plāns

## 🎯 Mērķis
Šī uzdevuma mērķis ir iemācīties izveidot **advancētāku Custom Gem**, kurš:

1) izmanto **pievienotu failu kā zināšanu bāzi** (piem., `LatHWEntStock.pdf`),  
2) strādā pēc **specifiskas Gem instrukcijas** (izdomāta uzņēmuma situācija + mērķi),  
3) palīdz iegūt **strukturētas atbildes** uz būtiskiem jautājumiem,  
4) beigās palīdz sagatavot **ieviešanas (projekta) plāna melnrakstu**,  
5) parāda **iterāciju**: pamanām, ka Gem instrukcijās trūkst info → papildinām → pārtestējam un redzam uzlabojumu.

> Šis uzdevums ir “tilts” uz nākamajiem uzdevumiem, kur Gems kļūs vēl specifiskāks (vairāk noteikumu, vairāk failu, precīzāki rezultātu formāti).

---

## ✅ 0. Sagatavošanās
Pirms sāc, sagatavo:

- Failu: **`LatHWEntStock.pdf`** (tiks pievienots Gem “zināšanu bāzei” / “Knowledge” / “Files”)
- Tekstu, ko ielīmēsi Gem instrukcijās (skat. 12.2 sadaļu)
- 10–15 min laika testēšanai un “iterācijas” demonstrēšanai

---

# 🤖 12.1. Izveido jaunu Custom Gem

## ✅ Darbība
1. Atver Gemini (vai platformu, kur veido Custom Gem)
2. Dodies uz **Gem roboti / Gems** (vai līdzīgu sadaļu)
3. Izvēlies **+ Jauns Gem robots**
4. Piešķir:
   - **Nosaukumu**
   - **Aprakstu**
5. Atrodi sadaļu **Knowledge / Files / Pievienot failu**
6. Pievieno failu: **`LatHWEntStock.pdf`**
7. Ielīmē **Gem instrukcijas** (skat. 12.2)
8. Saglabā Gem

---

# 🧩 12.2. Gem instrukcijas (kopē/ielīmē)

## Nosaukuma piemērs
```
HansaWorld Noliktavas Izvērtētājs (Dārza Sistēmas)
```

## Apraksta piemērs
```
Palīdz izvērtēt LatHWEntStock.pdf risinājuma atbilstību uzņēmuma noliktavu problēmām un sagatavot ieviešanas plāna melnrakstu valdei.
```

## ✅ “Norādījumi / Instructions” (kopē/ielīmē)
> Pielāgo variantiem, ja vēlies, bet **saglabā struktūru**.

```
Tu esi “HansaWorld risinājuma izvērtēšanas un ieviešanas plāna asistents” izdomātam uzņēmumam.

## Uzņēmuma profils
SIA "Dārza Sistēmas" nodarbojas ar dārza tehnikas un sēklu vairumtirdzniecību.
Uzņēmumam ir 3 noliktavas:
- Rīgā (centrālais mezgls)
- Salaspilī (beramkravas/mēslojums)
- Jelgavā (serviss un rezerves daļas)

## Konkrēti fakti un skaitļi (problēmas)
1) Krājumu neatbilstība:
   2025. gada inventarizācija uzrādīja 12% starpību starp sistēmu (Excel) un reālo atlikumu.
   Naudas izteiksmē tie ir 54 000 EUR zaudējumi gadā.

2) Partiju izsekojamība:
   Uzņēmums iepērk dārgu zāles pļāvēju partiju (150 vienības).
   Pieciem pļāvējiem tika konstatēts rūpnīcas brāķis.
   Netiek veikta sērijas numuru uzskaite pie saņemšanas, tādēļ uzņēmums nevar identificēt, kuriem klientiem pārdoti pārējie 145 pļāvēji, lai veiktu atsaukšanu.

3) Mērvienību haoss:
   Sēklas tiek iepirktas tonnās, bet pārdotas pakās pa 500g un 2kg.
   Pašreizējā sistēma nespēj veikt automātisku mērvienību konvertāciju, tādēļ noliktavā regulāri rodas kļūdas pie preču norakstīšanas.

4) Loģistikas “pudeles kakls”:
   Vidējais preces apstrādes laiks (no pasūtījuma līdz izsniegšanai) ir 4,5 stundas.
   Mērķis: samazināt līdz 45 minūtēm.

5) Tehnoloģiskais parāds:
   Noliktavas darbinieki skrien uz biroju pēc izprintētām pavadzīmēm, jo noliktavā nav ne planšešu, ne skeneru.

## Mērķis
Izvērtēt, vai LatHWEntStock.pdf aprakstītais risinājums spēj atrisināt šīs 5 konkrētās problēmas, un sagatavot ziņojumu valdei.

## Tavi uzdevumi (kā Gem)
1) Izvērtēt HansaWorld risinājuma atbilstību uzņēmuma vajadzībām, balstoties uz pievienoto PDF.
2) Atbildēt strukturēti, ar skaidriem secinājumiem, pieņēmumiem un atvērtajiem jautājumiem.
3) Ja PDF nav informācijas, nespekulē: skaidri pasaki “PDF neatrodams / nav minēts” un piedāvā, ko jāpārbauda ar piegādātāju.
4) Palīdzēt sagatavot projekta ieviešanas plāna melnrakstu (fāzes, aktivitātes, riski, atkarības).
5) Vienmēr piedāvā nākamo soli (1–3 konkrēti ieteikumi), lai lietotājs var virzīt darbu uz priekšu.

## Atbilžu formāts (obligāts)
- Īss kopsavilkums (2–4 teikumi)
- “Ko saka PDF?” (konkrēti punkti)
- “Ko tas nozīmē SIA Dārza Sistēmas?” (praktiska interpretācija)
- Atvērtie jautājumi / trūkstošā informācija (3–7 punkti)
- Ieteicamie nākamie soļi (3–7 punkti)
```

---

# 🧪 12.3. Testēšana — vai Gems izmanto failu + instrukcijas

## ✅ Mērķis
Pārbaudīt, ka Gem:
- saprot uzņēmuma kontekstu (3 noliktavas, 5 problēmas, skaitļi),
- atsaucas uz PDF saturu (cik iespējams),
- atbild strukturēti (kopsavilkums → PDF → interpretācija → jautājumi),
- neizdomā, ja PDF nav informācijas.

---

## 💬 Jautājumu paraugi (kopē/ielīmē)
Uzdod šos jautājumus tieši savā jaunajā Gem.

### 1) “Ātra atbilstības pārbaude”
```
Vai LatHWEntStock.pdf risinājums spēj risināt mūsu 5 problēmas (krājumu neatbilstība, sērijas numuri/atsaukšana, mērvienību konvertācija, apstrādes laika samazināšana, skeneri/planšetes)?
Iedod tabulu: Problēma → Ko saka PDF → Vai der (Jā/Daļēji/Nē) → Ko vēl jānoskaidro.
```

### 2) Krājumu neatbilstība (12% / 54 000 EUR)
```
Mums ir 12% krājumu neatbilstība un ~54 000 EUR zaudējumi gadā.
Kādas konkrētas funkcijas/procesi (pēc PDF) var samazināt šo starpību?
Iedod arī “quick wins” pirmajās 2–4 nedēļās.
```

### 3) Sērijas numuri + atsaukšana
```
Mums ir 150 zāles pļāvēju partija, 5 ir brāķis, un mēs nevaram identificēt klientus atsaukšanai.
Vai PDF apraksta sērijas numuru uzskaiti pie saņemšanas un izsekošanu līdz pārdošanai?
Ja jā — kā tas praktiski izskatās noliktavas procesā?
Ja nē — ko tieši būtu jāprasa piegādātājam/demo laikā?
```

### 4) Pasūtījuma apstrādes laiks laiks (4,5h → 2h)
```
Mērķis: samazināt pasūtījuma apstrādes laiku no 4,5h līdz 2h.
Pamatojoties uz PDF, kādi procesi/tehnoloģijas var dot lielāko efektu?
Iedod prioritāšu sarakstu (Top 5) ar īsu pamatojumu.
```

### 5) Skeneri/planšetes + darba organizācija
```
Noliktavā nav skeneru/planšešu; darbinieki skrien uz biroju pēc pavadzīmēm.
Ko PDF saka par darbu ar mobilajām ierīcēm vai skeneriem?
Iedod minimālo aprīkojuma komplektu 3 noliktavām (Rīga/Salaspils/Jelgava) un kāpēc.
```

### 6) “Valdei domāts kopsavilkums”
```
Uzraksti valdei 1 lappuses kopsavilkumu:
- problēma (ar skaitļiem),
- ko dod HansaWorld riinājums (pēc PDF),
- riski / kas nav skaidrs,
- ieteicamais nākamais solis (piem., demo, prasību darbnīca, pilotprojekts).
```

---

# 🔁 12.4. Iterācija — apzināti atrodi “trūkstošu info” un uzlabo Gem instrukcijas

## Ideja
Reālajā dzīvē Gems bieži “iesprūst”, jo:
- instrukcijās nav skaidrs, **kādu rezultātu formātu** tu gribi,
- nav norādīts, **kādi pieņēmumi ir atļauti**,
- trūkst uzņēmuma detaļu, kas nepieciešamas plānam (lietotāji, apjomi, SKU skaits, pasūtījumu skaits utt.).

Tāpēc šeit apzināti izveidosim situāciju, kur Gem paziņo, ka informācijas nepietiek, un mēs to salabojam.

---

## ✅ 1) Uzdod jautājumu, kas atklās trūkumu
Kopē/ielīmē:

```
Kāds ir mēneša vidējais apgrozījums noliktavā?
```

## ✅ 2) Ko tu, visticamāk, redzēsi
Gems var atbildēt, ka:
- nav informācijas par uzņēmuma mēneša apgrozījumu,
- PDF materiāls ir tehnisks funkcionālo iespēju apraksts
- kur šo informāciju varētu meklēt
- utml.

Tas ir **pareizi** — tā ir laba pazīme, ka Gems neizdomā. Ja Gems tomēr izdomā kautkādus neeksistējošus datus, tas var liecināt par uzvednes nepilnībām. Tādā gadījumā uzvedni būtu jāpapildina.

---

## ✅ 3) Atver Gem instrukcijas un papildini (kopē/ielīmē papildinājumu)
Atver Gem iestatījumus → Instructions → pievieno **zem “Konkrēti fakti un skaitļi”** (vai pašās beigās) šo:

```
## Apgrozījuma un apjoma dati (mēnesī):
- Pasūtījumu apjoms: Vidēji 850 izejošās pavadzīmes mēnesī (aptuveni 40 pasūtījumi dienā).
- Preču nomenklatūra: ~1 200 aktīvu artikulu (SKU).
- Sezonalitāte: No marta līdz maijam apgrozījums dubultojas, izraisot kritisku pārslodzi noliktavā un kļūdu skaita pieaugumu par 25%.
```

Saglabā izmaiņas.

---

## ✅ 4) Sāc JAUNU sarunu ar to pašu Gem un uzdod atkārtoti
Kopē/ielīmē:

```
Kāds ir mēneša vidējais apgrozījums noliktavā?
```

## ✅ 5) Ko konstatēt
Salīdzini “pirms” un “pēc”.

---

# 📌 12.5. Gala rezultāts (ko tu vari nodot kā artefaktu)
Kad Gems strādā, palūdz viņam sagatavot:

1) **Atbilstības matrica** (5 problēmas → PDF atbalsts → “Jā/Daļēji/Nē” → pierādījums/atsauce → jautājumi piegādātājam)  
2) **Ziņojums valdei** (1–2 lpp.)  
3) **Ieviešanas plāna melnraksts** (fāzes, termiņi, resursi, riski, gates)

Kopē/ielīmē:

```
Sagatavo 3 sadaļas vienā atbildē:
A) Atbilstības matrica (tabula)
B) Ziņojums valdei (1–2 lpp.)
C) Ieviešanas plāna melnraksts (fāzes, termiņi, resursi, riski, gates)
```

Papildus:
- Veic dažus redakcionālus labojumus.
- Eksportē rezultātu uz Google Docs.
- Saglabā dokumentu MIcrosoft Word formātā.

---

# ✅ Mini-checklist (paškontrole)
Atzīmē “Jā/Nē”:

- [ ] Gems izmanto `LatHWEntStock.pdf` (atsaucas uz tajā atrodamām tēmām)
- [ ] Gems neizdomā faktus, ja PDF nav informācijas
- [ ] Atbildes ir strukturētas (kopsavilkums → PDF → interpretācija → jautājumi → next steps)
- [ ] Ir skaidri “atvērtie jautājumi” piegādātājam/demo
- [ ] Iterācijā pēc instrukciju papildināšanas atbildes kvalitāte uzlabojas
- [ ] Ir sagatavojams artefakts valdei (kopsavilkums + plāns)

---

# Neliela retrospekcija 
1) Kādu nākamo failu (papildu) būtu vērts pievienot Gem zināšanu bāzei, lai atbildes būtu praktiskākas?
