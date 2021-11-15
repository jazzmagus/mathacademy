---
title: 2. Numeri razionali e numeri reali
linktitle: Capitolo 2 numeri Razionali e numeri Reali
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  math-01:
    parent: 
    weight: 

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 20
---

{{< toc >}}
<!-- {{< toc hide_on="xl" >}} -->

> ☆ **scadenza**: 30 novembre 2021

![ex2_img](../einstein_banner.jpeg)

## Capitolo 2 - Numeri razionali e numeri reali

> *“If I were not a physicist, I would probably be a musician. I often think in music. I live my daydreams in music. I see my life in terms of music.”*
― Albert Einstein*
>
> ― Albert **Einstein**

---

## Frazioni

- Una frazione rappresenta il risultato di una divisione tra numeri interi.

> **esempio**:
> ![cake](../cake-1.png)
> Supponiamo di dover dividere $2$ torte tra $6$ bambini.
>
> - Sappiamo che negli insiemi $\mathbb{N}$ e $\mathbb{Z}$ la divisione $2:6$ non si può eseguire, però possiamo tagliare ciascuna delle $2$ torte in $6$ fette uguali.
> - Risulteranno $12$ fette che si potranno dividere tra i $6$ bambini, ciascuno dei quali avrà $2$ fette.
>
> - I numeri naturali e gli interi relativi **non permettono di esprimere questa semplice soluzione del nostro problema**.
> - In situazioni come questa si deve ricorrere alle frazioni o, per essere più precisi, ai **numeri razionali**.
> - In questo modo potremodire che a ogni bambino spetteranno $\dfrac{2}{6}$ di torta, cioè $\dfrac{1}{3}$ di torta.

---

### 1. Il concetto di frazione

{{% callout alert %}}
**definizione**:
una frazione è un'espressione del tipo $\dfrac{a}{b}$

$$\dfrac{a}{b} = \dfrac{\textit{numeratore}}{\textit{denominatore}}$$

- $a, b$ sono i termini della frazione $\dfrac{a}{b}$
- con $a \in \mathbb{Z}, \\; b \in \mathbb{Z}, \\; b \neq 0$
{{% /callout %}}

{{% callout warning %}}
se $b=0 \Rightarrow$ il numero razionale $\dfrac{a}{b}$ **non esiste** in $\mathbb{Q}$

{{% /callout %}}

I numeri $a$ e $b$ si chiamano **termini** della frazione; precisamente:

- il numero $a$, che si trova al di sopra della linea di frazione, si chiama **numeratore**; 
- il numero $b$, al di sotto della linea di frazione, si chiama **denominatore**
  - Le *frazioni apparenti* sono casi particolari di frazioni improprie.

#### 2. frazioni apparenti

- Se il **numeratore** è **multiplo** del **denominatore**, la frazione rappresenta il risultato di una divisione che si può eseguire nell’insieme dei **numeri interi**, $\mathbb{Z}$

- Tali frazioni si dicono perciò **apparenti**.
particolare, se il denominatore è uguale a $1$, *si usa scrivere il solo numeratore*.

#### frazioni proprie e improprie

- Se il numeratore di una frazione è **minore** del denominatore si dice che la frazione è **propria**; 
- se invece il numeratore è **maggiore o uguale** al denominatore si parla di frazione **impropria**.

---

### 2. Frazioni equivalenti

{{% callout note %}}
**definizione**: due frazioni $\dfrac{a}{b}$ e $\dfrac{c}{d}$ si dicono **equivalenti** se:

$$a \cdot d = b \cdot c$$

cioè se il prodotto tra il *numeratore* della prima frazione e il *denominatore* della seconda è uguale al prodotto tra il *denominatore* della prima e il *numeratore* della seconda

- I due prodotti che si devono confrontare per stabilire se due frazioni sono equivalenti sono detti anche **prodotti in croce**

- ad esempio: le frazioni $\dfrac{4}{5}$ e $\dfrac{24}{30}$ sono equivalenti, infatti:

$$a \cdot d = b \cdot c \Rightarrow 4 \cdot 30 = 24 \cdot 5 = 120$$
{{% /callout %}}

---

#### SEGNO DI UNA FRAZIONE

---

### 3. Proprietà invariantiva

{{% callout note %}}

**proprietà invariantiva delle frazioni**

- Moltiplicando o dividendo entrambi i termini di una frazione per uno stesso numero diverso da zero, si ottiene una frazione equivalente alla frazione data:

$$\dfrac{a}{b} = \dfrac{a \cdot c}{b \cdot c} = \dfrac{a : c}{b : c}$$

con $a, b, c \in \mathbb{Z}, \qquad$ e con $b, c \neq 0$

{{% /callout %}}

---

### 4. Riduzione ai minimi termini e semplificazione

{{% callout note %}}

definizione: **frazione ridotta ai minimi termini**

- Una frazione si dice ridotta ai **minimi termini** o **irriducibile** se il **MCD** dei valori assoluti dei suoi termini è $1$

<font color="brown">*In generale, per ridurre una frazione ai minimi termini si dividono sia il numeratore sia il denominatore per il **MCD** dei loro valori assoluti.*</font>

{{% /callout %}}

- Di solito quando si semplifica una frazione si conviene di dividere i suoi termini per il loro MCD, in modo che la frazione equivalente che si ottiene sia ridotta ai minimi termini

$$$$

---

### 5. Riduzione al minimo comune denominatore

{{% callout warning %}}

- Per ridurre due o più frazioni al minimo comune denominatore, si procede così:

1. si riducono le frazioni ai minimi termini, se possibile;
2. si calcola il **mcm** dei denominatori delle frazioni ridotte: esso è il minimo comune denominatore;
3. si moltiplica il numeratore di ciascuna frazione ridotta per il quoziente tra il minimo comune denominatore e il corrispondente denominatore; si ottiene così il numeratore di ciascuna nuova frazione.

- Il denominatore sarà il minimo comune denominatore prima trovato.
{{% /callout %}}

> **esempio:**
>
> - Ridurre al **minimo comune denominatore** le seguenti frazioni:
>
> $$\dfrac{7}{15}, \dfrac{6}{20}, \dfrac{12}{18}$$

---

<br>

## L’insieme  dei  numeri  razionali

### 6. L’insieme  dei  numeri  razionali

<br>

{{% callout note %}}
Si definisce **numero razionale** l'insieme di tutte le frazioni equivalenti a una data frazione.
{{% /callout %}}

> Data una frazione, esistono infinite altre frazioni **equivalenti**
> 
> Ad esempio:
> $$\dfrac{2}{3} = \dfrac{4}{6} = \dfrac{6}{9} = \dfrac{8}{10} = \dfrac{10}{15} = \dots$$

#### Segno di un numero razionale

>Due frazioni equivalenti hanno lo stesso segno.
>
>- Quindi le frazioni, tutte equivalenti tra loro, il cui insieme costituisce un numero razionale, sono o tutte positive o tutte negative o tutte nulle. 
>   - Nel primo caso diremo che il numero razionale è positivo, 
>   - nel secondo caso diremo che è negativo; 
>   - nel terzo caso diremo che l’insieme delle frazioni nulle è il numero razionale $0$.
>
>Si possono estendere ai numeri razionali alcune definizioni già introdotte sui numeri interi.
>
> - Ad esempio, due numeri razionali si dicono **concordi** se hanno lo stesso segno, **discordi** se hanno segni diversi.

#### Opposto e valore assoluto di un numero razionale

<br>

{{% callout note %}}
DEFINIZIONE: **OPPOSTO DI UN NUMERO RAZIONALE**

- Si dice **opposto** di un numero razionale $a$, e si indica con $-a$, il numero razionale che si ottiene cambiando il segno di $a$

{{% /callout %}}

<br>

{{% callout note %}}
DEFINIZIONE: **VALORE ASSOLUTO DI UN NUMERO RAZIONALE**

- Si dice valore assoluto o *modulo* di un numero razionale $a$, e si indica con $|a|$, il numero $a$ stesso se $a$ è **positivo** o **nullo**, il suo opposto $-a$ se $a$ è **negativo.**
- In simboli:

$$
|a| = \begin{cases}
  a \qquad \quad \text{se} \\; a \ge 0\\\\
  -a \qquad \\, \text{se} \\, a < 0
\end{cases}
$$

{{% /callout %}}

---

## operazioni  con  i  numeri  razionali

## potenze in $\mathbb{Q}$

## Frazioni  e  numeri  decimali

## Proporzioni

## percentuali

## L’insieme  dei  numeri  reali $\mathbb{R}$

## Calcolo  approssimato
