# redux-mob-programmeringsuppgifter-onsdag-19-2-
# 🧑‍💻 Mobbprogrammering – Redux Toolkit & Global State

## 🕘 Tid & Upplägg för Passet
- **09.00 – 10.00**: Uppstart i helklass (genomgång av instruktion och syfte).
- **10.00 – 12.00**: **Mobbprogrammering i projektgrupper** – ni löser en eller flera koduppgifter tillsammans.
- **12.00 – 13.00**: Lunch.
- **13.00 – 13.45**: Diskussion och redovisning i helklass – varje grupp presenterar sitt arbete.
- **13.45 – 15.00**: Eget arbete och handledning.

---

## ✅ Syfte med Övningen
- Fördjupa förståelsen för **Redux Toolkit** och global state.
- Träna på **grupplösning av kodproblem** och gemensam problemlösning.
- Öva på **att förklara kod för andra** och reflektera över grupparbetets process.

---

## 🧑‍🤝‍🧑 Vad är Mobbprogrammering?
- **Hela gruppen** kodar tillsammans vid **en dator**.
- **En person skriver koden (driver)** medan resten av gruppen **aktivt diskuterar och ger förslag**.
- **Byt driver varje 10–15 minuter** så att alla får prova på att koda.
- **Alla är aktiva** – det är viktigt att ni pratar med varandra hela tiden.
- **Fokus:** Lär av varandra, ifrågasätt lösningar och förklara varför ni gör olika val.

---

## 🛠️ Förberedelser (innan 10.00)
1. **Bestäm vem som börjar vara driver**.
2. **Kloning av starterkod:**  
   Vi använder npgon av dessa denna färdiga mallar:  
   **Med TypeScript** [Redux Toolkit Starter Template](https://github.com/reduxjs/redux-templates/tree/master/packages/vite-template-redux)
   **Med JavaScript:** [Redux essentials-counter-example](https://github.com/reduxjs/redux-essentials-counter-example) 
4. **Öppna projektet i VS Code och kör igång dev-servern.**

## 💻 Uppgifter att välja mellan
Varje grupp väljer **minst 1 av dessa uppgifter** att lösa tillsammans.  
Hinner ni fler, välj gärna en till!

---

### 🟣 Uppgift 1: Counter med extra funktioner
Utgå från starterkoden och bygg ut counter-funktionen med:

- En **"dubbla" knapp** som multiplicerar värdet med 2.
- En **"spara värde" knapp** som sparar aktuellt värde i en separat del av state (exempelvis `savedCount`).
- Visa `savedCount` under räknaren.

**Fokus:** Lära er förstå `slice` och actions.  
**Diskutera:** Hur kan state delas upp smart?

---

### 🟢 Uppgift 2: Enkel TODO-app med Redux Toolkit
Skapa en ny **todoSlice** med:

- `todos: []` i initial state.
- Action för att **lägga till en TODO** (med text och id).
- Action för att **ta bort en TODO**.

Bygg en enkel komponent där ni kan **lägga till och ta bort TODOs**.

**Fokus:** Skapa ny slice, actions och reducers.  
**Diskutera:** Hur strukturerar ni `store` med flera slices?

---

### 🔵 Uppgift 3: Tema-växlare (Light/Dark Mode)
Skapa en slice med state:  
`{ theme: 'light' }`

- Lägg till action för att **växla mellan `'light'` och `'dark'`**.
- Använd `theme`-state för att **ändra bakgrundsfärg på hela sidan**.

**Fokus:** State som styr UI.  
**Diskutera:** När är global state motiverat vs. lokalt state?

---

## 🎙️ Efter Lunch – Redovisning och Diskussion
Varje grupp redovisar kort (**ca 5 min**):

- **Vad ni valde att göra.**
- **Hur ni löste det.**
- **Vilka problem ni stötte på.**

---

## 📝 Tips under Passet
- **Använd gärna Redux DevTools** för att se state-förändringar.
- Behöver ni kolla dokumentation:
  - [Redux Toolkit](https://redux-toolkit.js.org/)
  - [React Docs](https://react.dev/)
- **Fråga läraren** om ni kör fast!

---

## 📦 När ni är klara:
- **Ladda gärna upp er kod på GitHub** om ni vill spara den.
- **Reflektera över hur det var att arbeta i mobbprogrammering:**
  - **Vad var bra?**
  - **Vad var svårt?**
