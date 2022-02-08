---
title: Slides
summary: An introduction to using Wowchemy's Slides feature.
authors: []
tags: []
categories: []
date: "2019-02-05T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: serif
  transition: convex
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

{{< slide background-image="https://source.unsplash.com/1920x1080/?white" >}}

<section data-transition="convex">
  <h2 style="color:#3B2F2F" class="r-fit-text">Relazioni e Funzioni</h2>
  <h3 class="fragment" style="color:#3B2F2F"><em>- Rif.: Capitolo 4 -</em></h3>
  <img src="gear_00.png" class="fragment" style="opacity:0.8;filter:alpha(opacity=100);" width="100">
  <h4 style="color:#8A4117"><em>prof. diego fantinelli</em></h4>
  <p>ITI "Enrico Fermi" - Bassano del Grappa</p>
  <p style="color:#8A4117"><em>matematica per il biennio &mdash; classi prime</em></p>
</section>

---
<!-- prerequisiti-->
{{< slide background-image="https://source.unsplash.com/1920x1080/?white" >}}

<section style="font-size:90%" data-transition="convex">
  <h2 style="color:#3B2F2F">Prerequisiti</h2>

  <ul class="fragment">
  <li class="fragment"><h3 style="color:#8A4117">insiemi numerici: </h3></li>
    <ul class="fragment">
      <li>Operazioni insiemistiche</li>
      <li>Operazioni in $\mathbb{N}, \mathbb{Z}, \mathbb{Q}, \mathbb{R}$</li>
    </ul>
  <hr class="fragment" style="height:2px;border-width:0;color:gray;background-color:gray">
  <li class="fragment"><h3 style="color:#8A4117">teoria degli insiemi</h3></li>
    <ul class="fragment">
      <li>Rappresentazioni: estensiva, intensiva e Diagrammi di Eulero-Venn</li>
      <li>Operazioni insiemistiche</li>
      <li>Prodotto Cartesiano: definizione e rappresentazione</li>
    </ul>
</section>

---

<section data-background-image="white_sky.jpeg" data-background-opacity="0.5" data-transition="zoom">
  <h2 style="color:#3B2F2F">La lezione</h2>
  <h2 style="color:#3B2F2F;" class="r-fit-text; fragment">Relazioni e FUNZIONI</h2>
  <img src="gear_00.png" style="opacity:0.6; filter:alpha(opacity=40);" width="200">
</section>

<section data-background-image="white_sky.jpeg" data-background-opacity="0.4" data-transition="zoom">
<h3 class="fragment" style="color:#3B2F2F; font-size: 40px;"><em>In fisica e in matematica è impressionante la sproporzione tra lo sforzo per capire una cosa nuova per la prima volta e la semplicità e naturalezza del risultato una volta che i vari passaggi sono stati compiuti.
<br>Nel prodotto finito, nelle scienze come in poesia, non c'è traccia della fatica del processo creativo e dei dubbi e delle esitazioni che lo accompagnano.<br>
<br>&mdash; Giorgio Parisi</em></h3>
</section>

<section data-background-image="white_sky.jpeg" data-background-opacity="0.4" data-transition="convex">
<h2 style="color:#3B2F2F" class="r-fit-text">Relazione $\mathscr{R}$</h2>
<h3 class="fragment" style="text-align:left; color:#3B2F2F;">definizione:</h3>

<q class="fragment" style="color:#C04000; font-size:90%; background-color:#F3E5AB;">Dati due insiemi non vuoti $A$ e $B$, si dice **relazione** tra $A$ e $B$ - e si indica con $\mathcal{R}$ -, una **legge** che associa elementi dell’insieme $A$ con elementi dell’insieme $B$.
<ul class="fragment">
  <li>Se una relazione opera tra un insieme $A$ e se stesso, si dice relazione nell’insieme $A$.</li>
</ul>
</q>

<p class="fragment">In generale si scrive: $\mathcal{R}: A \longrightarrow B$<br>
oppure: $\mathcal{R}: a \in A \longrightarrow b \in B$
</p>
</section>

<section data-background-image="real_life_bkg.jpg" data-background-opacity="0.4" data-transition="convex">
<h2 style="color:#8A4117" class="r-fit-text">proprietà delle relazioni:</h2>
<ul class="fragment">
  <li><h3>Simmetrica e antisimmetrica</h3></li>
    <ul>
      <li>una relazione si dice simmetrica</li>
      <li>una relazione si dice simmetrica</li>
    </ul>
  <li><h3>Riflessiva e antiriflessiva</h3></li>
    <ul>
      <li>una relazione si dice simmetrica</li>
      <li>una relazione si dice simmetrica</li>
    </ul>
</ul>
</section>

<section data-background-image="real_life_bkg.jpg" data-background-opacity="0.4" data-transition="convex">
<h2 style="color:#8A4117">Relazioni di equivalenza</h2>
<h4 class="fragment" style="text-align:left; color:#8A4117;">definizione:</h4>
<q class="fragment" style="color:#C04000; font-size:90%; background-color:#F3E5AB;">Dati due insiemi non vuoti $A$ e $B$, si dice **relazione** tra $A$ e $B$ - e si indica con $\mathcal{R}$ -, una **legge** che associa elementi dell’insieme $A$ con elementi dell’insieme $B$.</q>
</section>

<section data-background-image="real_life_bkg.jpg" data-background-opacity="0.4" data-transition="convex">
<h2 style="color:#8A4117">Relazioni di ordine</h2>
<h4 class="fragment" style="text-align:left; color:#8A4117;">definizione:</h4>
<q class="fragment" style="color:#C04000; font-size:90%; background-color:#F3E5AB;">Dati due insiemi non vuoti $A$ e $B$, si dice **relazione** tra $A$ e $B$ - e si indica con $\mathcal{R}$ -, una **legge** che associa elementi dell’insieme $A$ con elementi dell’insieme $B$.</q>
</section>

---

<section data-background-image="gear_00.png" data-background-opacity="0.4" data-transition="convex">
<h2 style="color:#8A4117" class="r-fit-text">Funzioni</h2>
<h3 class="fragment" style="text-align:left; color:#8A4117;">definizione:</h3>

<q class="fragment" style="color:#C04000; background-color:#F3E5AB;">Dati due insiemi non vuoti $X$ e $Y$, si dice **funzione** tra $X$ e $Y$, una **legge** che associa **ad ogni** elemento $x$ dell’insieme $X$
**uno e uno solo** elemento $y$ dell’insieme $Y$</q>

<p class="fragment">si scrive:
$f: X \longrightarrow Y$ oppure $f: x \in X \longrightarrow y \in Y$
</p>
<q class="fragment" style="color:#C04000;">Si legge: $f$ è una funzione che associa un elemento $x$ appartenente ad $X$ ad un elemento $y$ appartenente a $Y$.</q>
<p class="fragment">oppure, nella forma più compatta: <font color="#C04000">$y=f(x)$</font></p> 
</section>

<section data-background-iframe="https://mathbrain.netlify.app"
          data-background-interactive>
  <h2>Iframe</h2>
</section>

<section>
  <h2>The Lorenz Equations</h2>
    \[\begin{aligned}
    \dot{x} &amp; = \sigma(y-x) \\
    \dot{y} &amp; = \rho x - y - xz \\
    \dot{z} &amp; = -\beta z + xy
    \end{aligned}\]
</section>

<section>
<h2 style="color:#3B2F2F" class="r-fit-text">definizioni importanti</h2>

<table style="font-size:85%">
  <tr style="background-color:#F3E5AB;">
    <td><em>Dominio</em></td>
    <td>Descr$CRj$ è la gratificazione ottenuta dalla scelta su un processo $j$;izione</td>
  </tr>
  <tr style="background-color:#F3E5AB;">
    <td><em>Codominio</em></td>
    <td>$CRj$ è la gratificazione ottenuta dalla scelta su un processo $j$;</td>
  </tr>
  <tr style="background-color:#FFF0F5;">
    <td><em>Immagine</em></td>
    <td>$CRj$ è la gratificazione ottenuta dalla scelta su un processo $j$;</td>
  </tr>
  <tr style="background-color:#FFF0F5;">
    <td><em>Controimmagine</em></td>
    <td>$CRj$ è la gratificazione ottenuta dalla scelta su un processo $j$;</td>
  </tr>
</table>
</section>

<section>
<h2 style="color:#3B2F2F" class="r-fit-text">osservazioni</h2>

<p class="r-fit-text">$\textbf{Happiness(t)}=w_{0}+w_{1} \cdot\displaystyle{\sum_{j=1}^{t}} \gamma^{t-j} C R_{j}+w_{2} \cdot\sum_{j=1}^{t} \gamma^{t-j} E V_{j}+w_{3} \cdot\sum_{j=1}^{t} \gamma^{t-j} R P E_{j}$</p>

<p>
<ul style="font-size:80%;">
  <li>In una funzione il **dominio** coincide - a meno di punti particolari - con l'insieme di partenza;</li>
  <li>$\gamma$ è un “forgetting factor” (fattore dimenticando) che rende gli eventi degli studi più recenti più influenti rispetto a quelli precedenti;</li>
  <li>$CRj$ è la gratificazione ottenuta dalla scelta su un processo $j$;</li>
  <li>$EVj$ è la valutazione del rischio su di un processo $j$;</li>
  <li>$RPEj$ rappresenta la differenza tra la ricompensa desiderata e quella effettivamente ottenuta dal processo $j$.</li>
</ul>
</p>
</section>

---

<section data-background-image="real_life_bkg.jpg" data-background-opacity="0.5" data-transition="zoom">
  <h2 style="color:#3B2F2F" class="r-fit-text">esempi di funzione</h2>
  <h2 style="color:#3B2F2F" class="r-fit-text">nella vita reale</h2>
  <img src="ecg_01.png" style="opacity:0.8;filter:alpha(opacity=40);" width="600">
</section>

<section data-background-image="brain_net.jpeg" data-background-opacity="0.4" data-transition="convex">
<h2 style="color:#3B2F2F" class="r-fit-text">Albertino...</h2>
<h2 style="background-color:powderblue; background-opacity:0.5;" class="r-fit-text">Creare connessioni...</h2>
  <p class="fragment">si scrive:
$f: X \longrightarrow Y$ oppure $f: x \in X \longrightarrow y \in Y$
</p>
<q class="fragment" style="color:#C04000;">Si legge: $f$ è una funzione che associa un elemento $x$ appartenente ad $X$ ad un elemento $y$ appartenente a $Y$.</q>
<p class="fragment">oppure, nella forma più compatta: <font color="#C04000">$y=f(x)$</font></p>
</section>

<section data-background-image="brain_net.jpeg" data-background-opacity="0.4" data-transition="convex">
  <h2 style="background-color:powderblue;">l'elettrocardiogramma</h2>
  <q style="background-color:#F3E5AB;">Per evitare di commettere gravi errori devi ricordare che, in una frazione algebrica, puoi semplificare solo i fattori comuni al numeratore e al denominatore
  </q>
<img src="heart.png" style="color:" width="400">

</section>

---

<section data-background-image="net_bkg.jpeg" data-background-opacity="0.6" data-transition="zoom">

<img src="gear.png" width="200">
<a href="#">
  <img class="r-frame" src="gear.png" width="200">
</a>
</section>

---

{{< slide background-image="calm_bkg.jpg" data-background-opacity="6">}}

## La funzione Happiness

<p class="r-fit-text">$\textbf{Happiness(t)}=w_{0}+w_{1} \cdot\displaystyle{\sum_{j=1}^{t}} \gamma^{t-j} C R_{j}+w_{2} \cdot\sum_{j=1}^{t} \gamma^{t-j} E V_{j}+w_{3} \cdot\sum_{j=1}^{t} \gamma^{t-j} R P E_{j}$</p>

<p>
<ul style="font-size:80%;">
  <li>$t$; $w_0$, $w_1$, $w_2$ e $w_3$ sono costanti che indicano l’influenza dei diversi tipi di eventi;</li>
  <li>$\gamma$ è un “forgetting factor” (fattore dimenticando) che rende gli eventi degli studi più recenti più influenti rispetto a quelli precedenti;</li>
  <li>$CRj$ è la gratificazione ottenuta dalla scelta su un processo $j$;</li>
  <li>$EVj$ è la valutazione del rischio su di un processo $j$;</li>
  <li>$RPEj$ rappresenta la differenza tra la ricompensa desiderata e quella effettivamente ottenuta dal processo $j$.</li>
</ul>
</p>

---

{{< slide background-image="calm_bkg.jpg" data-background-opacity="6">}}

<section data-transition="zoom">

<h2 style="color:#8A4117" class="r-fit-text">DOMANDE?</h2>

<h2 style="color:#8A4117" class="fragment">Buon lavoro!</h2>

</section>

---

![zzz](https://res.cloudinary.com/teepublic/image/private/s--TQXt20Pc--/t_Resized%20Artwork/c_fit,g_north_west,h_954,w_954/co_000000,e_outline:48/co_000000,e_outline:inner_fill:48/co_ffffff,e_outline:48/co_ffffff,e_outline:inner_fill:48/co_bbbbbb,e_outline:3:1000/c_mpad,g_center,h_1260,w_1260/b_rgb:eeeeee/c_limit,f_auto,h_630,q_90,w_630/v1588675429/production/designs/9818088_0.jpg)
