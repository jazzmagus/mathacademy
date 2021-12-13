---
theme: "serif"
transition: "convex"
highlightTheme: "monokai"
logoImg: "miur.png"
slideNumber: false
title: "Concorso Ordinario 2021"
---

<!-- .slide: data-background="https://source.unsplash.com/1920x1080/?white" data-background-color="#ffffff" -->

# Concorso STEM 2021

### candidato: Diego Fantinelli

<br>

#### data: 12 dicembre 2021

---

### *All human wisdom is summed up in two words; wait and hope.*
-- *Alexandre Dumas*

---

<!-- .slide: data-background-video="ooo.mp4" data-background-color="#000000" -->

> **references**: 
> - [[00 Maths Index]]
> - [[calcolo differenziale]]
> - [sarah schott on youtube](https://youtu.be/hMZNh_r6SqQ)

<!-- <iframe width="100%" height="200" src="https://www.youtube.com/embed/hMZNh_r6SqQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

---

# equazioni differenziali
> Alla fine di questa lezione ci saremo fatti un'idea di massima di cosa sia una **equazione differenziale** e che cosa sia una **soluzione** di una equazine differenziale.

--

<!-- .slide transition:= "zoom" -->

### introduzione

> Consideriamo il seguente problema:
> - ovviamente non si tratta di un'equazione differenziale, bensì di un'equazione algebrica. 
> - Si voglia verificare se $(1,3)$ è una soluzione di: $2y + x = y + 4$
> - chiaramente, sostituendo si ottiene: 
>$$\begin{cases}
2(3)+(1)=7\\
(3)+4=7
\end{cases}$$

---

## Capitolo 2

> pertanto la risposta alla domanda iniziale è **affermativa**.
>
> Allo stesso modo possiamo verificare se $(1,3)$ è una soluzione di quest'altra equazione: $y^2 + x = y + 8$
>
> - chiaramente, sostituendo si ottiene: 
>$$\begin{cases}
(3)^2+(1)=10\\
(3)+8=11
\end{cases}$$

--

## sotterraneo due

---

> pertanto la risposta alla domanda iniziale è **negativa**.

- Vogliamo arrivare alla definizione di **equazione differenziale** attraverso degli esempi, o meglio, sulle soluzioni; vedremo infatti che le soluzioni di una equazione differenziale non si presentano come una coppia di **coordinate**.

---

> Sia la funzione $y=-\dfrac{1}{x}$ una soluzione della seguente equazione: $$\dfrac{dx}{dy}=y^2$$
>
> - cercando di dare una rapida interpretazione potremmo dire che la soluzione dell'equazione è una funzione la quale, elevata al quadrato, è uguale alla derivata della funzione stessa, rispetto alla variabile $x$.
>
> procediamo come abbiamo fatto in precedenza, sostituendo la soluzione data all'interno dell'equazione e verifichiamo se l'uguaglianza è verificata.
