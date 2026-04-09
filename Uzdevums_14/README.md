# 🎯 Uzdevums 14 — MI + programmēšana: no “skatīties un saprast” līdz prototipam

## 🎯 Ievads (kāpēc mēs to darām)
Šī uzdevuma mērķis **nav** kļūt par programmētāju.

Mērķis ir:
- gūt priekšstatu, **kā programmēšanas process ar MI** var izskatīties praksē,
- saprast, kā MI var palīdzēt **ātri uztaisīt strādājošu prototipu** (pat ja tu neesi programmētājs),
- iemācīties **iterēt**: uztaisām sākuma versiju → pārbaudām → palūdzam MI uzlabojumu → pārbaudām atkal.

Šajā uzdevumā tev būs blakus fails `calc.html` (vienkāršs kalkulators), ko varēsi atvērt un testēt.

---

## ✅ 0. Sagatavošanās
Tev vajadzēs:
- datoru ar pārlūkprogrammu (Chrome / Edge / Firefox)
- piekļuvi failiem no šīs mapes (kur ir arī `calc.html`)
- MI čatu (ChatGPT/Gemini/Copilot Chat vai citu)

> Drošības piezīme: neveido prototipus ar sensitīviem datiem (paroles, klientu dati, API atslēgas u. tml.). Šeit mums to nevajag.

---

# 🧩 14.1. Atver un apskati `calc.html`

## Kas tas ir?
`calc.html` ir **vienkārša programmiņa**, kas darbojas pārlūkā (HTML + CSS + JavaScript) un ir izveidota ar **mākslīgā intelekta palīdzību**.

## ✅ Darbība
1. Atrodi failu `calc.html` (tas būs blakus šim markdown).
2. Atver to pārlūkā (parasti pietiek ar dubultklikšķi).
3. Pamēģini parēķināt:
   - `7+5`
   - `9*9`
   - `10/4`
4. Pārliecinies:
   - Vai pogas strādā?
   - Vai rezultāts parādās korekti?
   - Vai “C” notīra ievadi?

## ✅ Ko tieši šeit iemācīties
- Pārlūks var palaist vienkāršas programmas bez instalēšanas.
- MI var palīdzēt uzģenerēt sākuma versiju, ko tu **vari testēt un uzlabot**.

---

# 🤖 14.2. Izveido pats/pati savu vienkāršu kalkulatoru (no nulles)

## Mērķis
Izveidot **savu kalkulatoru**, kas darbojas pārlūkā.

## ✅ Darbība
1. Izveido jaunu failu, piemēram: `mans_kalkulators.html`
2. Atver MI čatu un iedod **vienkāršu uzvedni** (skat. zemāk).
3. Iekopē MI ģenerēto kodu savā `mans_kalkulators.html`.
4. Atver to pārlūkā un notestē.

### ✅ Vienkārša uzvedne (kopē/ielīmē)
```
Uzģenerē vienkāršu kalkulatoru vienā HTML failā (HTML+CSS+JS), kas darbojas pārlūkā.
Vajag pogas 0-9, +, -, *, /, C un =.
Lūdzu iedod pilnu koda saturu vienā blokā, lai varu iekopēt failā mans_kalkulators.html.
```

## ✅ Pārbaude (mini-checklist)
- [ ] Mans kalkulators atveras pārlūkā
- [ ] Var ievadīt skaitļus ar pogām
- [ ] `+ - * /` strādā
- [ ] `C` notīra
- [ ] `=` izrēķina

---

# 🔁 14.3. Iterācija: paplašini kalkulatoru ar papildus funkcijām

## Ideja
Tu jau esi uztaisījis strādājošu sākuma versiju. Tagad “kā MI projektā” — turpini to pašu sarunu un uzlabo.

### Papildus funkciju piemēri (izvēlies 1–3)
- atmiņa: `M+`, `M-`, `MR`, `MC`
- kvadrātsakne: `√`
- procenti: `%`
- pakāpe: `x²` vai `xʸ`
- trigonometriskās funkcijas: `sin`, `cos`, `tan`

## ✅ Darbība
1. Atgriezies tajā pašā MI sarunā, kur ģenerēji kalkulatoru.
2. Iedod uzdevumu paplašināt funkcijas.
3. Iekopē izmaiņas savā failā.
4. Testē.
5. Ja kaut kas nestrādā — iedod MI kļūdu aprakstu un prasi labojumu.

### ✅ Uzvednes piemērs (kopē/ielīmē, pielāgo)
```
Paplašini manu kalkulatoru mans_kalkulators.html ar funkcijām:
- √ (kvadrātsakne)
- M+, M-, MR, MC (atmiņa)
Lūdzu saglabā vienkāršu dizainu un iedod pilnu atjaunināto HTML faila kodu.
Piezīme: pēc katras darbības rezultātam jāparādās displejā un nedrīkst salūzt parastās + - * / darbības.
```

## ✅ Pārbaude (mini-checklist)
- [ ] Ja ievadu `9` un nospiežu `√`, redzu `3`
- [ ] Atmiņa strādā (M+, MR, MC)
- [ ] Parastās darbības nav salūzušas
- [ ] Neparādās “Kļūda” normālās situācijās

---

# 🧪 14.4. Eksperiments: izdomā savu programmiņu un pamēģini uztaisīt prototipu

## Mērķis
Eksperimentālā kārtā pamēģināt ar MI uztaisīt **kaut ko sev interesējošu**, piemēram:
- mini spēli (klikšķini pareizo pogu, “guess the number”, “snake” vienkāršota versija)
- Tetris (vienkāršots)
- dambrete (vienkāršota, sākumā bez pilniem noteikumiem)
- “to-do” saraksts
- taimeris / Pomodoro
- viktorīna (quiz)

> Svarīgi: mērķis ir prototips, nevis perfekta spēle.

## ✅ Darbība
1. Izvēlies ideju (1 teikumā).
2. Definē minimālo versiju (MVP): ko tai obligāti jāprot.
3. Palūdz MI uzģenerēt pirmo versiju vienā HTML failā.
4. Atver pārlūkā un testē.
5. Izdari 1 iterāciju: uzlabojums (UI, noteikums, skaņa, punkti, laiks utt.).

### ✅ Uzvednes šablons (kopē/ielīmē)
```
Izveido vienkāršu pārlūkā darbināmu programmi��u vienā HTML failā (HTML+CSS+JS).

Ideja: [TAVA IDEJA].
MVP prasības:
- [prasība 1]
- [prasība 2]
- [prasība 3]

Lūdzu iedod pilnu koda saturu vienā blokā, lai varu iekopēt failā prototips.html.
Saglabā vienkāršu dizainu un paskaidro, kā to palaist pārlūkā.
```

### Piemērs (ja gribi ātri sākt)
```
Izveido vienkāršu pārlūkā darbināmu spēli vienā HTML failā.

Ideja: "Guess the number" (uzmini skaitli).
MVP prasības:
- ģenerē noslēpuma skaitli 1..100
- lietotājs ievada minējumu un saņem norādi "par lielu/par mazu"
- skaita mēģinājumus un ļauj sākt no jauna

Lūdzu iedod pilnu koda saturu vienā blokā, lai varu iekopēt failā prototips.html.
```

---

# 📌 Gala rezultāts (ko vajag, lai uzdevums skaitītos izpildīts)
Tev jābūt:

1) Apskatītam un notestētam `calc.html` (īss secinājums: kas strādā / kas interesants)  
2) Izveidotam savam failam `mans_kalkulators.html` (vienkāršā versija)  
3) Uzlabotam `mans_kalkulators.html` ar papildus funkcijām (iterācija)  
4) Izveidotam prototipam `prototips.html` (kāda cita ideja)  

---

# ✅ Mini-checklist (paškontrole)
- [ ] Es atvēru `calc.html` un pamēģināju parēķināt
- [ ] Es izveidoju savu vienkāršu kalkulatoru pārlūkā
- [ ] Es paplašināju kalkulatoru ar vismaz 1 jaunu funkciju (iterācija)
- [ ] Es izveidoju vēl vienu prototipu (spēle / rīks / kaut kas cits)
- [ ] Es visu notestēju pārlūkā un pārliecinājos, ka strādā

---

# Neliela retrospekcija
1) Kas bija lielākais ieguvums: ātrums, ideju ģenerēšana, vai tas, ka vari iterēt bez dziļām programmēšanas zināšanām?  
2) Kādu nākamo “mini projektu” tu gribētu uztaisīt ar MI (1 teikumā)?
