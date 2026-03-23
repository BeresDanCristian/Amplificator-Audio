# Proiectare Amplificator Audio - CAD 

Acest depozit conține documentația și etapele de proiectare pentru un **amplificator audio de putere**, realizat în cadrul disciplinei Proiectare Asistată de Calculator (CAD) la facultatea ETTI, UTCN.

## ⚙️ Specificații Tehnice
Proiectul vizează implementarea unui sistem audio complet, având următoarele blocuri funcționale:

* **Filtrare Semnal:** * Filtru Trece-Sus (HPF) pentru eliminarea componentei continue.
    * Filtru Trece-Jos (LPF) pentru limitarea benzii de frecvență utile.
* **Etaj de Amplificare în Tensiune:** Asigură câștigul necesar pentru atacul etajului final.
* **Etaj de Putere (Final):** Implementat cu tranzistoare de putere (TIP41) pentru acționarea unei sarcini de 4Ω.
* **Alimentare:** Diferențială, de $\pm18V$.

## 🛠️ Metodologie de Proiectare
1.  **Schema Electrică:** Realizată în mediul **OrCAD**.
2.  **Breviar de Calcul:** Dimensionarea riguroasă a componentelor passive ($R, C$) și alegerea punctelor de funcționare pentru tranzistoare.
3.  **Analiză și Simulare:**
    * **Analiza în Frecvență (AC Sweep):** Verificarea benzii audio.
    * **Analiza Transient:** Observarea formei de undă la ieșire și verificarea distorsiunilor.
    * **Analiza Termică:** Testarea comportamentului circuitului la variații de temperatură (între -100°C și +200°C).

## 📈 Rezultate Cheie
* **Sarcina:** Optimizat pentru difuzor de 4Ω.
* **Stabilitate:** Funcționare stabilă în gama de temperatură standard, cu identificarea limitelor de funcționare la temperaturi extreme (peste 100°C).
* **Componente:** Utilizarea componentelor discrete (TIP41, rezistoare de precizie, condensatori electrolitici).

---
**Autor:** Bereş Dan-Cristian  
**Grupa:** 2122  
**Coordonatori:** prof. ing. Steţco Elena Mirela, prof. ing. Ovidiu Aurel Pop  
**Instituție:** Universitatea Tehnică din Cluj-Napoca
