# POLITICA DE CONFIDENȚIALITATE — Vezi că Trage

**Ultima actualizare: 9 iulie 2026**

*Acest document este versiunea consolidată, finală, a politicii de confidențialitate — combină structura clară și practică a documentului scurt deja publicat (`docs/privacy/index.html`) cu rigoarea legală a documentului generat Termly (`PRIVACY_POLICY_draft_RO.md`), plus câteva completări inspirate din politicile altor două aplicații românești de pescuit din App Store (notificare în caz de breșă de securitate, angajament de răspuns în 30 de zile). Niciunul dintre fișierele anterioare nu a fost șters — acesta e un al treilea document, cel recomandat pentru folosire finală.*

---

## 1. Cine este responsabil de datele tale

Operator de date: **Opriș Ioan-Andrei**, persoană fizică, dezvoltator independent al aplicației **Vezi că Trage** (nu există un SRL/PFA — aplicația e publicată pe App Store/Google Play pe numele meu, ca persoană fizică).

Pentru orice întrebare sau solicitare legată de datele tale, poți scrie oricând la:

📧 **administrator@vezicatrage.click**

Sau prin poștă la: Opriș Ioan-Andrei, 103C Drumul Fermei, bl. 4, ap. 17, Popești-Leordeni, Județul Ilfov 077160, România.

---

## 2. Ce este "Vezi că Trage"

Vezi că Trage este o aplicație mobilă (iOS și Android) pentru pescarii amatori din România. Permite utilizatorilor să își creeze un cont, să vadă cotele apei în timp real (Dunăre) și prognoza meteo pentru locații populare de pescuit, să înregistreze și să navigheze pe trasee GPS de pescuit, să posteze alerte despre condițiile locale (de ex. inundații, obstacole) și să partajeze postări, poze și comentarii cu alți pescari într-un feed de comunitate. Aplicația poate afișa și bannere promoționale interne de la branduri din domeniul pescuitului.

---

## 3. Ce date colectăm și de ce

| Categorie de date | De ce o colectăm |
|---|---|
| Nume, prenume, adresă de email, parolă | Creare și gestionare cont, autentificare (prin serviciul Clerk) |
| Fotografie de profil și fotografii atașate postărilor din Comunitate | Personalizarea profilului tău și a postărilor publicate în secțiunea Comunitate |
| Locație GPS (inclusiv geolocalizare precisă) | Afișarea hărții, înregistrarea și navigarea traseelor tale de pescuit, informații despre cotele Dunării și vremea din zona ta |
| Conținut generat de tine | Postări, comentarii, like-uri, trasee salvate, jurnal personal de pescuit — funcționalitatea de bază a aplicației |
| Identificator de utilizator și jetoane de autentificare | Menținerea sesiunii tale conectate și securizarea contului (nu conțin parola ta în clar) |
| Date de profil de la Google/Apple, dacă alegi autentificare socială | Facilitarea înregistrării/autentificării rapide |
| Date automate ale dispozitivului (model, sistem de operare, IP, informații despre erori/crash) | Securitate, depanare, diagnosticare, analiză internă |

Aplicația **nu** colectează date financiare, **nu vinde** datele tale către niciun terț și **nu afișează reclame** din partea unor rețele de publicitate terțe (bannerul promoțional din aplicație e conținut propriu, gestionat direct de noi, nu servit de o rețea de ads).

---

## 4. Temeiul legal al prelucrării

- **Executarea contractului** — prelucrăm datele de cont și de locație pentru că sunt necesare ca aplicația să funcționeze (hartă, trasee, cote, vreme).
- **Interes legitim** — pentru moderarea conținutului din Comunitate (raportare, blocare, ascundere automată a conținutului raportat), pentru prevenirea fraudei, și pentru a trimite utilizatorilor informații despre oferte/promoții.
- **Consimțământ** — la crearea contului, ți se cere acceptarea explicită a Regulilor Comunității; poți retrage oricând consimțământul ștergându-ți contul sau contactându-ne.
- **Obligații legale** — atunci când suntem obligați prin lege (de exemplu, cooperare cu o autoritate).

---

## 5. Cui transmitem datele (subprocesatori)

| Furnizor | Rol |
|---|---|
| **Clerk** | Autentificare și gestionarea contului (email/parolă, Google, Apple) |
| **Supabase** | Bază de date și stocarea fotografiilor încărcate în aplicație |
| **Sentry** | Monitorizarea erorilor și performanței aplicației |
| **Google Maps Platform** | Afișarea hărților și a traseelor |
| **Open-Meteo** | Date meteo publice — primește doar coordonate GPS anonime, fără date personale |

Avem contracte (acorduri de procesare a datelor) cu acești furnizori, concepute să îi împiedice să folosească datele tale în alte scopuri decât cele pentru care le oferim acces.

Serverele acestor furnizori pot fi situate în afara Spațiului Economic European (de exemplu, în Statele Unite). În aceste cazuri ne bazăm pe garanțiile prevăzute de GDPR — Clauzele Contractuale Standard ale Comisiei Europene — pentru a proteja transferul datelor tale. Aceste clauze pot fi puse la dispoziție la cerere.

**Nu partajăm datele tale personale cu terți în scopuri de marketing sau publicitate**, și nu le vindem niciodată.

---

## 6. Autentificare prin rețele sociale

Dacă alegi să te înregistrezi/autentifici folosind Google sau Apple, primim de la aceștia anumite informații de profil de bază (nume, email, poză de profil). Nu controlăm și nu răspundem pentru modul în care Google sau Apple procesează datele tale în afara acestui schimb — consultă politicile lor de confidențialitate pentru detalii.

---

## 7. Cât timp păstrăm datele

Păstrăm datele tale cât timp ai un cont activ. Poți să-ți ștergi contul direct din aplicație (Contul meu → Șterge contul definitiv) — la ștergere, toate datele tale (postări, comentarii, like-uri, trasee, jurnal, fotografii, rapoarte, blocări) sunt eliminate din baza de date, ireversibil, cu excepția informațiilor pe care legea ne obligă să le păstrăm mai departe (de exemplu, pentru prevenirea fraudei sau obligații fiscale/contabile).

---

## 8. Securitatea datelor

Datele sunt transmise criptat (HTTPS/TLS). Accesul la baza de date este restricționat prin politici de tip Row-Level Security, astfel încât fiecare utilizator poate accesa doar propriile date (sau date publice, în cazul conținutului din Comunitate).

Am implementat măsuri tehnice și organizatorice rezonabile pentru a proteja informațiile tale împotriva accesului neautorizat, modificării sau divulgării. Totuși, nicio transmisie electronică sau metodă de stocare nu poate fi garantată 100% sigură. Dacă are loc vreodată o breșă de securitate care afectează datele tale personale, te vom notifica — pe tine și, dacă legea o cere, autoritatea competentă — în conformitate cu cerințele legale aplicabile (GDPR).

---

## 9. Minori

Aplicația nu este destinată copiilor. Vârsta minimă de utilizare este **16 ani** — aceasta este vârsta de consimțământ digital stabilită de GDPR pentru România. Dacă ai sub 16 ani, ai nevoie de acordul unui părinte sau tutore pentru a folosi aplicația.

Dacă aflăm că un minor sub 16 ani și-a creat un cont fără acordul părinților, vom dezactiva contul și vom șterge datele colectate. Dacă știi despre un astfel de caz, te rugăm să ne contactezi la administrator@vezicatrage.click.

---

## 10. Drepturile tale

Conform GDPR, ai dreptul la:

- **Acces** — să afli ce date deținem despre tine;
- **Rectificare** — să corectezi date incorecte (poți edita profilul direct din aplicație);
- **Ștergere** — disponibilă imediat, din aplicație (Contul meu → Șterge contul definitiv);
- **Portabilitate** — să primești o copie a datelor tale într-un format structurat;
- **Opoziție/restricționare** — să te opui sau să limitezi anumite prelucrări;
- **Retragerea consimțământului** — în orice moment, fără să afecteze legalitatea prelucrării anterioare;
- **Plângere** — la Autoritatea Națională de Supraveghere a Prelucrării Datelor cu Caracter Personal (ANSPDCP), [www.dataprotection.ro](https://www.dataprotection.ro), dacă consideri că drepturile tale au fost încălcate.

Pentru acces, rectificare, portabilitate sau opoziție, scrie-ne la administrator@vezicatrage.click — **răspundem în maximum 30 de zile**.

**Renunțarea la comunicări de marketing:** poți dezactiva notificările push din setările telefonului sau poți închide bannerele promoționale din aplicație oricând.

---

## 11. Link-uri externe

Aplicația poate afișa link-uri către site-uri externe (de exemplu, link-urile din bannerele promoționale). Această politică nu acoperă practicile de confidențialitate ale acelor site-uri — te încurajăm să le consulți propriile politici înainte de a le folosi.

---

## 12. Modificări ale acestei politici

Putem actualiza această politică din când în când. Orice modificare semnificativă va fi comunicată prin aplicație sau prin actualizarea datei de mai sus. Continuarea folosirii aplicației după o astfel de modificare înseamnă că ești de acord cu versiunea actualizată.

---

## 13. Contact

📧 **administrator@vezicatrage.click**

Opriș Ioan-Andrei
103C Drumul Fermei, bl. 4, ap. 17
Popești-Leordeni, Județul Ilfov 077160, România

---

*Notă internă (nu face parte din politica publicată): comparativ cu politicile altor două aplicații românești de pescuit analizate (Bluvi, Fir Întins), acest document adaugă mențiunea autorității naționale ANSPDCP (pe care niciuna dintre ele nu o are), clauza de notificare în caz de breșă de securitate (inspirată din Bluvi) și angajamentul de răspuns în 30 de zile (inspirat din Fir Întins) — plus rigoarea legală GDPR completă din varianta Termly inițială.*
