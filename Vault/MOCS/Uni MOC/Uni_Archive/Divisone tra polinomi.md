Status: #Complete
Academic Year: 2022-2023
Class: [[Matematica 0 (class)]]
Created: Jul 22, 2023
Type: #Uni/Notes 

---
# Indice
1. [[#Definizione]]
2. [[#Divisione tra Polinomi (1 variabile)]]
3. [[#Divisione polinomi con più variabili]]

---
# Definizione
Nella divisione tra numeri interi:$$
\begin{align}
& \textcolor{orange}{7}\ :\ \textcolor{green}{2}\ fa\ \ \textcolor{red}{3}\ \ con \ \ resto \ \ \textcolor{violet}{1}    \\
\\ 
&Dove:\ \  \textcolor{orange}{Dividendo}, \ \ \textcolor{green}{Divisore}, \ \ \textcolor{red}{Quoziente}, \ \ \textcolor{violet}{Resto}  \\ \\

& Quindi: \ \  \textcolor{orange}{7}\ =\ \textcolor{green}{2} \cdot \textcolor{red}{3} + \textcolor{violet}{1} \\
\end{align}
$$
Nella divisione tra polinomi: 
$$\begin{align}
& \text{Svolgere la divisione tra il polinomio \textcolor{orange}{A(x)} e il polinomio \textcolor{green}{B(x)} (di grado <= del precedente)} \\ 
& \text{significa trovare i polinomi \textcolor{red}{Q(x)} e \textcolor{violet}{R(x)}}  \\ \\

& \textcolor{orange}{A(x)} = \textcolor{green}{B(x)} \cdot \textcolor{red}{Q(x)}+\textcolor{violet}{R(x)}
\end{align}$$

Si può dimostrare che:
$$
\begin{align}
& - \text{Il grado di \textcolor{orange}{A(x)} è la differenza tra il grado di \textcolor{orange}{A(x)} e quello di \textcolor{green}{B(x)}}  \\
& -  \text{Il grado di \textcolor{violet}{R(x)} è minore del grado di \textcolor{green}{B(x)}}
\end{align}
$$

**Consiglio:** é possible trovar il resto di una divisione polinomiale senza svolgere la divisione attraverso il [[Teorema del resto]]

---
# Divisione tra Polinomi  (1 variabile)
**Steps:**
1. Ordiniamo i polinomi dal grado massimo al grado minimo
2. Si prende il monomio di grado massimo del dividendo e lo si divide per il monomio di grado massimo del divisore, il *risulto* di scrive sotto al divisore
3. Si prende il *monomio appena ottenuto* e lo si moltiplica termine a termine per il tutti i monomi del divisore, e il risultato di questa operazione lo si scrive cambiato di segno sotto al dividendo
4. Si somma il polinomio appena ottenuto con il dividendo soprastante
5. Si ripetono i passaggi 2, 3 e 4 finche il grado del ultimo polinomio sotto al dividendo sarà inferiore del grado del divisore 
6. Il polinomio sotto al divisore sarà il quoziente
7. L'ultimo polinomio (o monomio) sottostante al divedendo sarà il resto

**Esempio:**
![[polinomialdicimage.jpeg]]

---
# Divisione polinomi con più variabili
**Steps:**
0. Scegliere variabile di riferimento e ordinare i polinomi secondo quella variabile
- poi uguale al metodo per [[#Divisione tra Polinomi (1 variabile)]]

**Esempio:**![[divisionepl2image.jpeg]]