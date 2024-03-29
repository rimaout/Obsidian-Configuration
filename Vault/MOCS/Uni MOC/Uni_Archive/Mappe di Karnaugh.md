---
Created: 2023-10-23
Type: Uni Note
Class:
  - "[[Progettazione Sistemi Digitali (class)]]"
Academic Year: 2023/2024
Related:
  - "[[Algebra Booleana]]"
  - "[[Tabelle di verità, Maxtermini e Mintermini]]"
Completed: true
---
---
## Index
1. [[#Definizione]]
2. [[#Come creare mappa di Karnaugh]]
3. [[#Semplificazione]]
4. [[#Esempi]]


---
## Definizione
- Metodo semplificativo per funzioni logiche 
- Garantisce la massima semplificazione (secondo la Massini), Non garantisce la massima semplificazione (secondo il Simonetta)
- Consigliato usare massimo 4 variabili

---
## Come creare mappa di Karnaugh
1. **Struttura della mappa**
![[IMG_0C9357783BF9-1.jpeg|1000]]

2. **Tabella di verità-->Mappa K:**
![[IMG_5F2A185DC9A7-1.jpeg|700]]

---
## Semplificazione

***Quando si raccoglie si deve:***
1. Creare gruppi composti da $2^n$ elementi
2. Creare gruppi più grandi possibili 
3. Fare il minor numero di gruppi
4. Quando è possibile non fare overlapping 

***Froma Pos:***
Raccogliendo per 0 si trovano i [[Tabelle di verità, Maxtermini e Mintermini#Max-termine (0)|maxtermini]] che verranno uniti da or (risultato forma *pos*)
![[IMG_41CF323F2323-1.jpeg]]

***Forma Sop:***
Raccogliendo per 1 si trovano i [[Tabelle di verità, Maxtermini e Mintermini#Min-termine (1)|mintermine]] che verranno uniti da and (risultato forma *sop*)
![[IMG_A1F23F894B21-1.jpeg|800]]

---
## Esempi
![[IMG_D25867EC0D16-1.jpeg]]

---