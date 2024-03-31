**Manual de utilizare File Monitor**

Șibaev Vasile

Bun venit la File Monitor! Acest program este conceput pentru a vă ajuta să monitorizați și să gestionați fișierele dintr-un folder specificat. Mai jos este un ghid despre cum să utilizați eficient acest instrument:

### 1. Noțiuni introductive
- Asigurați-vă că aveți Python instalat pe sistemul dvs. pentru a rula acest program.
- Descărcați scriptul Python furnizat (`file_monitor.py`) și salvați-l în directorul preferat.
- Deschideți un prompt de comandă sau o fereastră de terminal.
- Navigați la directorul în care ați salvat `file_monitor.py`.

### 2. Rularea programului
- Pentru a porni File Monitor, rulați scriptul tastând `python file_monitor.py` și apăsând Enter.
- Programul vă va solicita comenzi pentru a executa diverse operații.

### 3. Comenzi disponibile
- **info <nume fișier>**: Preluați informații despre un anumit fișier. Înlocuiți `<filename>` cu numele fișierului pe care doriți să-l inspectați. Această comandă oferă detalii precum tipul fișierului, data creării, data modificării și informații suplimentare specifice tipului de fișier (de exemplu, dimensiunea imaginii, numărul de linii etc.).
   - Exemplu: `info example.txt`

- **commit**: faceți un instantaneu al stării curente a folderului monitorizat. Această acțiune înregistrează detalii despre toate fișierele din folder în acel moment.
   - Exemplu: `commit`

- **stare**: vizualizați starea curentă a folderului monitorizat, inclusiv orice modificări de la ultimul instantaneu. Această comandă afișează fișiere noi, fișiere șterse și fișiere care au fost modificate.
   - Exemplu: `status`

- **exit**: Terminați programul și ieșiți.
   - Exemplu: `ieșire`

### 4. Monitorizarea modificărilor folderului
- Monitorul de fișiere verifică în mod continuu modificările în folderul specificat.
- Detectează fișiere noi, fișiere șterse și modificări ale fișierelor existente.
- Procesul de monitorizare rulează în fundal, permițându-vă să efectuați alte operațiuni în timp ce rulează.

### 5. Detectare programată
- Programul efectuează automat monitorizarea folderelor la intervale regulate.
- La fiecare 5 secunde, programul scanează folderul pentru modificări și actualizează starea în consecință.

### 6. Commit manual
- Puteți declanșa manual un instantaneu al stării curente a folderului folosind comanda `commit`.
- Această acțiune captează toate detaliile fișierului și le salvează pentru referință.
- Instantaneul include informații despre numele fiecărui fișier și statisticile corespunzătoare.

### 7. Ieșirea din program
- Pentru a ieși din File Monitor, tastați pur și simplu `exit` și apăsați Enter.
- Asigurați-vă că salvați toate informațiile necesare înainte de a ieși.

### 8. Notă
- Acest program acceptă diferite tipuri de fișiere, inclusiv fișiere text, fișiere Python, fișiere Java și imagini.
- Oferă informații specifice, adaptate fiecărui tip de fișier atunci când se regăsesc detaliile fișierului.

### 9. Depanare
- Dacă întâmpinați probleme sau erori în timpul utilizării programului, consultați ieșirea consolei pentru mesaje de eroare.
- Asigurați-vă că calea folderului specificată este corectă și accesibilă.

Vă mulțumim pentru utilizarea File Monitor. Monitorizare fericită!
