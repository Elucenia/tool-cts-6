<!-- ELUCENIA technical documentation · cts-6 · it · no clinical/professional/rights approval -->

# CTS-6 (sindrome del tunnel carpale)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/cts-6)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Intorpidimento prevalentemente o esclusivamente nel territorio del nervo mediano

`dorm`

### Intorpidimento notturno

`noturna`

### Atrofia e/o debolezza della muscolatura tenar

`atrofia`

### Test di Phalen positivo

`phalen`

### Perdita della discriminazione tra due punti (\> 6 mm)

`dpp`

### Segno di Tinel positivo sul tunnel carpale

`tinel`

## Edizione del metodo

CTS-6/Graham 2006: 6 criteri ponderati del tunnel carpale; esame clinico

## Formula documentata

Somma: intorpidimento nel territorio mediano 3,5; notturno 4; atrofia/debolezza tenar 5; Phalen positivo 5; perdita discriminazione di due punti 4,5; Tinel positivo 4. Totale 0–26.

## Limiti e popolazione

Lo sviluppo Graham 2006 ha utilizzato il consenso di esperti e storie di casi che combinavano criteri clinici; la validazione descritta nell’abstract ha confrontato le probabilità del modello con i giudizi di un altro gruppo di esperti. Tale disegno non stabilisce di per sé le prestazioni rispetto all’esame elettrofisiologico in ogni popolazione clinica. Il punteggio di sei item, la sua soglia e la fascia d’età devono essere verificati nel metodo completo.

## Riferimenti

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

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

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Bassa probabilità di sindrome del tunnel carpale (inferiore a circa il 25%)

Considerare diagnosi alternative (radicolopatia cervicale, polineuropatia).


### 2

Probabilità intermedia (tra circa il 25% e l’80%)

L’elettroneuromiografia ha più valore in questo intervallo.


### 3

Probabilità intermedia (tra circa il 25% e l’80%)

L’elettroneuromiografia ha più valore in questo intervallo.


### 4

Alta probabilità di sindrome del tunnel carpale (circa l’80% o più)

In questo intervallo, l’elettromiografia modifica raramente la diagnosi clinica.

