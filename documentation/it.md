<!-- ELUCENIA technical documentation · escala-lanss · it · no clinical/professional/rights approval -->

# Scala del dolore LANSS

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-lanss)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Il dolore sembra una sensazione strana e spiacevole nella pelle (punture, formicolio, scosse elettriche)?

`a1`

### Il dolore rende la pelle della zona dolorosa diversa dal normale (chiazzata, arrossata o rosata)?

`a2`

### Il dolore rende la pelle insolitamente sensibile al tatto (fastidio con uno sfioramento leggero o con indumenti stretti)?

`a3`

### Il dolore compare improvvisamente, a crisi, senza motivo apparente a riposo (scosse elettriche, fitte)?

`a4`

### Il dolore dà la sensazione che la temperatura della pelle sia cambiata (calore, bruciore)?

`a5`

### Esame: allodinia (dolore o fastidio sfiorando con cotone la zona dolorosa rispetto a una zona normale)

`b6`

### Esame: soglia alterata alla puntura (la puntura con un ago 23G è percepita diversamente nella zona dolorosa: più o meno intensa)

`b7`

## Edizione del metodo

LANSS/Bennett 2001: 5 sintomi+2 segni, totale 0–24, soglia ≥12; portoghese brasiliano Schestatsky 2011

## Formula documentata

Parte A (questionario): item da 5, 5, 3, 2 e 1 punto. Parte B (esame sensitivo): allodinia 5; soglia alla puntura alterata 3. Totale 0 a 24; soglia ≥12.

## Limiti e popolazione

La LANSS combina sintomi con segni ottenuti mediante esame sensitivo per indagare la predominanza di un meccanismo neuropatico nel dolore cronico. Gli item dell’esame non devono essere trattati come semplice autovalutazione. La validazione brasiliana citata non certifica l’implementazione né nuove traduzioni.

## Riferimenti

- [Bennett M. The LANSS Pain Scale: the Leeds assessment of neuropathic symptoms and signs. Pain, 2001.](https://doi.org/10.1016/S0304-3959(00)00482-6)

- [Schestatsky P et al. Brazilian Portuguese validation of the Leeds Assessment of Neuropathic Symptoms and Signs for patients with chronic pain. Pain Med, 2011.](https://doi.org/10.1111/j.1526-4637.2011.01221.x)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
