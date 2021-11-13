---
title: 8. Equazioni lineari
linktitle: Capitolo 8 | Equazioni lineari
toc: true
type: docs
date: "2021-09-09T00:00:00+01:00"
draft: false
diagram: true
menu:
  math-02:
    parent: 
    weight: 10

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
---

> ☆ **scadenza**: 20 novembre 2021

![ex1_img](../capitolo_8.jpeg)

## obiettivi

{{% callout note %}}

- alla fine della lezione saremo - *dovremmo essere* - in grado di risolvere le seguenti equazioni lineari:

$$\small{\left(x^{2}-2 x-2\right)^{2}-(x-2) \{(x-2)^{3}-4\left[2(x+1)-(x-1)^{2}\right] \}=11(x-1)}$$

$$\small{(3 x-1)^{3}+(3 x+1)(6 x-7)=(3 x+1)(3 x-1)^{2}}$$

$$\frac{x+3}{x-3}-\frac{2 x-1}{x^{2}-6 x+9}=\left(\frac{3}{x-3}+1\right)^{2}$$
{{% /callout %}}

---

## Concetti fondamentali sulle equazioni

### 1. Le equazioni

{{% callout note %}}
**definizione**:

Un’**equazione** è un’uguaglianza tra due espressioni che contiene una o più lettere.
{{% /callout %}}

### 2. Classificazione delle equazioni

```mermaid
flowchart TD
    id1(EQUAZIONI)

    id2([lineari intere])
    id3([lineari frazionarie])
    id4([numeriche])
    id5([letterali])
    id6([intere])
    id7([frazionarie])
  id1 --- id2
  id1 --- id3
  id1 --- id4
  id1 --- id5
  id5 --- id6
  id5 --- id7
```

---

### 3. Soluzioni e dominio di un’equazione

> <font color="brown">Sostituendo un numero al posto dell’incognita in un’equazione, essa si trasformain un’uguaglianza tra due espressioni, uguaglianza che, se ha significato, può risultare vera o falsa</font>

{{% callout alert %}}
<font color="darkblue">**definizione**: **soluzioni di un'equazione**

I numeri che, sostituiti al posto dell’incognita, trasformano un’equazione in un’uguaglianza vera si dicono **soluzioni**, o **radici**, dell’equazione data</font>
{{% /callout %}}

- Risolvere un’equazione significa determinare tutte le sue soluzioni.
  - L’insieme che ha per elementi tutte le soluzioni di un’equazione è l’insieme delle soluzioni e lo indicheremo sempre con $$S= ( \text{S} \subseteq \mathbb{R})$$.
  - In altre parole, risolvere un’equazione significa determinarne l’**insieme delle soluzioni**.

{{% callout warning %}}

<font color="brown">**definizione: DOMINIO DI UN’EQUAZIONE**

Si dice **dominio** di un’equazione l’insieme dei numeri reali che, sostituiti all’incognita, trasformano l’equazione in un’uguaglianza dotata di significato e che quindi è o **vera** o **falsa.**

- Indicheremo sempre con $D$ il dominio;
- poichè le soluzioni di un’equazione devono necessariamente appartenere al dominio dell’equazione stessa, risulta:

$$S \subseteq D \subseteq \mathbb{R}$$
{{% /callout %}}

>**ESEMPIO**:
> nella seguente equazione frazionaria:
> $$\dfrac{x -1}{x -2} + x = \dfrac{1}{2}$$
>
> - non è possibile assegnare a $x$ il valore $2$ perché si annullerebbe il denominatore della frazione al primo membro.
> - Per ogni altro valore di $x$ l’equazione si trasformerà in un’uguaglianza vera o falsa.
> - Quindi il dominio dell’equazione è: $D = \mathbb{R}-\\{2\\}$

### Equazioni **determinate**, **impossibili**, **indeterminate.**
- Nella risoluzione di un’equazione si possono presentare i seguenti casi.
  - L’insieme delle soluzioni contiene un numero finito di elementi, cioè l’**equazione ha un numero finito di soluzioni**: diremo allora che l’equazione è **determinata.**
    - L’equazione $x^2=4$ è **determinata**, perché i numeri il cui quadrato è $4$ sono $2$ e $-2$ e quindi le soluzioni sono $2$ e $-2$:
    $$S= \\{ -2; \\, 2\\}$$
  - L’insieme delle soluzioni è vuoto $S= \\{\emptyset \\}$, cioè l’equazione **non ha soluzioni**: diremo allora che l’equazione è **impossibile.**
    - L'equazione $x=x+5$ è **impossibile** $\Rightarrow S = \emptyset$
  - L’insieme delle soluzioni contiene un numero infinito di elementi, cioè l’equazione ha **infinite soluzioni**: diremo allora che l’equazione è **indeterminata.**
    - L'equazione: $$(x + 1)^2 = x^2 + 2x + 1$$ è verificata $\forall x \in \mathbb{R}$ e quindi è **indeterminata**: $S = \mathbb{R}$.
    - L'equazione è una **identità** perché è sempre verificata nel suo dominio $D$

---

## 4. Principi di equivalenza delle equazioni

### $\star$ **primo** principio di equivalenza:

- *afferma che **sommando algebricamente** ad entrambi i membri di una equazione, uno **stesso numero** o una **stessa espressione contenente l'incognita**, otteniamo una equazione **equivalente** a quella data.*

### $\star \star$ **secondo** principio di equivalenza:

- *moltiplicando o dividendo entrambi i membri di una uguaglianza per uno **stesso numero** *diverso da zero*, o per una **stessa espressione** che non possa annullarsi, si ottiene un'equazione **equivalente** a quella data.*

<br>

> **ESEMPIO:**
>
> - _Un mattone pesa $1$ kg più mezzo mattone._
> - _Quanto pesa un mattone?_
>
> Il calcolo letterale e le equazioni ci permettono di sviluppare dei `procedimenti` in modo simbolico e di pervenire rapidamente alla soluzione.
>
> - Nel nostro caso, indicando con $x$ il peso di un mattone (espresso in kg), la situazione può essere espressa in forma simbolica dall’equazione:
>
> $$x = 1 + \dfrac{1}{2} x$$
>
> - utilizzando in modo opportuno i due *principi di equivalenza* possiamo semplificare l'equazione:
> $$x \textcolor{red}{- \dfrac{1}{2}x} = 1 + \cancel{\dfrac{1}{2} x} \textcolor{red}{- \cancel{\dfrac{1}{2}x}} \rightarrow x-\dfrac{1}{2} x=1 \quad \longrightarrow \quad \dfrac{1}{2} x=1$$
> $$\textcolor{red}{2 \\; \cdot} \dfrac{1}{2} x = \textcolor{red}{2 \\; \cdot} 1$$
> - semplificando otteniamo la soluzione:
> $$\textcolor{darkorange}{x=2}$$

---

#### 5. Equazioni equivalenti

<br>
{{% callout note %}}

<font color="darkblue">**definizione: EQUAZIONI EQUIVALENTI**

Due equazioni si dicono **equivalenti** se hanno lo stesso **insieme delle soluzioni**.</font>
{{% /callout %}}

---

![zzz](https://res.cloudinary.com/teepublic/image/private/s--TQXt20Pc--/t_Resized%20Artwork/c_fit,g_north_west,h_954,w_954/co_000000,e_outline:48/co_000000,e_outline:inner_fill:48/co_ffffff,e_outline:48/co_ffffff,e_outline:inner_fill:48/co_bbbbbb,e_outline:3:1000/c_mpad,g_center,h_1260,w_1260/b_rgb:eeeeee/c_limit,f_auto,h_630,q_90,w_630/v1588675429/production/designs/9818088_0.jpg)
