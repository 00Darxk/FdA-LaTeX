# FdA-LaTeX

Appunti di Fondamenti di Automatica, AA 2022/2023
 Università di Roma Tre. 

<details>
  <summary>Di seguito le possibile domande dell'orale, divise in base ai macroargomenti riguardanti: 
</summary>
 <summary>Rappresentazioni Ingresso-Uscita:</summary>

 • Equazioni differenziali: lo studente dovrà dare la definizione di equazione differenziale e di problema di Cauchy. Dovrà essere mostrata la risoluzione delle equazioni lineari a coefficienti costanti di ordine pari a uno e di ordine superiore.

• Il controllo a catena aperta e il controllo a controreazione: Dovrà essere illustrato il principio su cui si basano  le due tipologie di controllori, mettendo in evidenza pregi e difetti dei due approcci.

• Regolazione e asservimento: E’ richiesto al candidato di definire le proprietà dei due sistemi di controllo

• La trasformata di Laplace: Il candidato deve definire la trasformata di Laplace di un segnale, la sua ascissa di convergenza e deve illustrare le trasformate di segnali elementari. Dovrà poi spiegare il metodo dei poli e residui per ottenere la antitrasformata di Laplace.

• Modi propri d’evoluzione di un sistema lineare e stabilità di un sistema lineare: Il candidato deve conoscere le evoluzioni canoniche (esponenziali, oscillatorie, costanti) corrispondenti alle diverse configurazioni dei poli di un sistema lineare sul piano complesso S. Per ciascuna di esse deve essere illustrata la rappresentazione con la trasformata di Laplace ed il corrispettivo andamento nel tempo. Dovranno poi essere definite le proprietà di stabilità asintotica, limite di stabilità ed instabilità.

• Risposta libera e risposta forzata: Il candidato deve sapere definire le due risposte e, dall’analisi e confronto dei modi propri di un sistema con quelli dell’ingresso, saper dedurre il tipo di uscita atteso.

• La funzione di trasferimento: Il candidato dovrà mostrare come sia possibile applicare ad una equazione differenziale, rappresentante il comportamento di un sistema dinamico, la trasformata di Laplace e come sia possibile ricavare la funzione di trasferimento come elemento di collegamento tra la trasformata dell’ingresso e quella dell’uscita.

• Risposta transitoria e permanente: Il candidato deve poter definire le due risposte e saperle distinguere dall’analisi dei modi dell’uscita. E’ richiesta la descrizione del teorema del valore finale.

• Luogo delle radici: Illustrare il luogo delle radici e mostrare come possa essere utilizzato per sintetizzare un controllore proporzionale K.

• Comportamento a regime: classificazione in tipi: Il candidato dovrà analizzare il comportamento di un sistema a regine permanente e valutare l’errore di inseguimento di un certo insieme di segnali canonici. Rimarranno definiti sia il tipo d’ingresso sia il tipo di sistema di controllo. Analizzando, poi, la posizione degli eventuali poli nell’origine presenti in catena diretta, potranno essere dedotti comportamenti statici e astatici in relazione alla presenza di disturbi nel loop di controreazione.

• Reiezione dei disturbi polinomiali: Il candidato dovrà illustrare il concetto di astatismo e mostrare il ruolo dei poli nell’origine nella reiezione di disturbi appartenenti alle classi canoniche (gradini, rampe, parabole).

• Risposta armonica e sue rappresentazioni grafiche (Nyquist, Bode): Il candidato deve mostrare analiticamente come l’uscita di un sistema lineare, al cui ingresso è applicato un segnale sinusoidale, sotto alcune ipotesi di partenza, sia ancora una sinusoide d’ampiezza e fase opportune. Si devono poi descrivere le due principali rappresentazioni grafiche della risposta stessa.

• Tracciamento del Diagramma di Bode: il candidato deve calcolare gli andamenti approssimativi dei vari termini di una funzione di trasferimento.

• Sistemi a fase non minima: Illustrare i sistemi a fase non minima e mostrare la difficoltà che essi inducono nella sintesi di sistemi di controllo ad alto guadagno.

• Sistemi con ritardo finito: Dopo avere illustrato uno o più esempi di sistemi con ritardo finito mostrare la loro rappresentazione sul diagramma di Bode e giustificare le difficoltà indotte nella stabilizzazione di sistemi a ciclo chiuso che li comprendono.

• Criterio di stabilità di Nyquist: Partendo dal Teorema dell’Indicatore Logaritmico, il candidato dovrà applicarlo al computo del numero di poli a parte reale positiva (instabili) della funzione di trasferimento a ciclo chiuso di un sistema a controreazione. Verrà a tal scopo definito il percorso di Nyquist sul quale deve viaggiare la variabile complessa s e quindi ricavato il criterio di stabilità completo e ridotto di Nyquist.

• Margini di stabilità (guadagno e fase): Partendo dall’analisi della stabilità di un sistema a controreazione, il candidato dovrà definire, prima sul diagramma di Nyquist e poi su quello di Bode, i margini di guadagno e di fase dandone, infine, un’interpretazione pratica.

• Funzione di sensibilità ed applicazione ai sistemi a controreazione: Dopo avere definito la funzione di sensibilità si calcolano la sensibilità diretta e quella complementare per illustrare il ruolo del guadagno di anello nella reiezione dei disturbi e la riproduzione dei segnali di riferimento.

• Specifiche ad anello chiuso ed aperto per un sistema di controllo: Il candidato deve illustrare le specifiche progettuali che più frequentemente vengono usate nella sintesi dei sistemi di controllo a controreazione, sia che esse vengano fornite nel tempo (sovraelongazione, tempo di salita, tempo di assestamento, …), sia che esse vengano fornite in frequenza (banda passante, modulo alla risonanza, …). In particolare devono essere individuati i legami globali tra queste grandezze ed il loro effetto sui margini di stabilità e sulla pulsazione d’attraversamento.

• Carta di Nichols: Il candidato deve illustrare la relazione analitica e grafica tra la funzione di trasferimento d’anello e quella a ciclo chiuso. Dovranno poi essere individuate sulla carta di Nichols le principali grandezze caratteristiche del comportamento del sistema di controllo.

• Controllori ad alto guadagno.

• Il regolatore standard PID

• Proprietà linearizzante della controreazione: Il candidato deve mostrare come una caratteristica statica non lineare sia modificata da una controreazione ad elevato guadagno. Il discorso è ovviamente estensibile al caso dei controllori ad alto guadagno di sistemi, questa volta, dinamici (per esempio il pendolo)

• Errore di riproduzione di una sinusoide e specifiche in frequenza.

• Reiezione di disturbi sinusoidali e specifiche in frequenza.

• Principio del modello interno.

• Stabilità dei sistemi non lineari e linearizzazione intorno a un punto di equilibrio.

  <summary>Sistemi a Segnali Campionati:</summary>


• Struttura di un sistema di controllo a segnali campionati: lo studente dovrà disegnare tutti i componenti di un sistema di controllo realistico a segnali campionati: il microprocessore, i convertitori A/D e D/A, il filtro anti-aliasing per finire con il processo e il trasduttore dell'uscita.

• Teorema del campionamento (spettro di un segnale campionato, ricostruttore di Shannon): Dovrà essere introdotto il concetto di segnale campionato rappresentato come sequenza di impulsi e quindi, dopo averne ricavato la trasformata di Fourier, il candidato dovrà mostrare come sia possibile, sotto opportune ipotesi, ricostruire il segnale di continuo di partenza tramite il ricostruttore ideale di Shannon. Dovranno essere messe in evidenza tutte le problematiche collegate a tale ricostruttore e quali difficoltà si incontrano nel momento in cui si pensi di utilizzare l’organo di tenuta di ordine zero al suo posto. Dovrà essere illustrato il problema dell’aliasing e come possa essere evitato in un sistema di controllo a segnali campionati.

• Organo di Tenuta: Il candidato dovrà ricavare la funzione di trasferimento dell’organo di tenuta e la sua approssimazione a basse frequenze evidenziando le problematiche associate al suo uso in un sistema di controllo a segnali campionati.

• Trasformata Z: Dovrà essere fornita la definizione di trasformata Z per una sequenza di campioni e come essa possa essere proficuamente utilizzata nell’analisi di un sistema di controllo a segnali campionati.

• Trasformazione esatta da F(s) ad F(z): Il candidato dovrà mostrare come sia possibile ricavare la funzione di trasferimento discreta di un sistema campionato partendo dalla sua rappresentazione ingresso-uscita. Dovrà essere illustrato il metodo della decomposizione in poli e residui.

• Mapping dal piano S al piano Z: Data la trasformazione esatta tra s e z, il candidato dovrà mostrare la corrispondenza tra il semipiano sinistro del piano S con il domino definito sul piano Z contenuto all’interno della circonferenza unitaria.

• Modi propri d’evoluzione di un sistema discreto: Il candidato dovrà analizzare i modi propri di un sistema discreto, facendo riferimento alle loro evoluzioni in funzione della posizione dei poli sul piano Z.

• Trasformazioni approssimate dal piano S al piano Z: Dovranno essere illustrate le tecniche approssimate per trasformare una funzione di trasferimento continua in una discreta, ricavandone le opportune espressioni come approssimazione dell’integrale e mostrandone i limiti di utilizzo in funzione delle loro proprietà di mappatura del semipiano sinistro del piano S sul piano Z.

• Metodologie di sintesi di sistemi di controllo a segnali campionati: Il candidato dovrà illustrare le due principali metodologie  di sintesi dei regolatori discreti, ovvero, quella che fa riferimento discretizzazione di controllori sintetizzati nel continuo, e quella che, a partire dalla discretizzazione del processo da controllare, si muove su tecniche di sintesi  proprie dei sistemi discreti.

• Scelta del tempo di campionamento: Il candidato dovrà illustrare come la scelta del tempo di campionamento non sia soltanto legata al soddisfacimento del teorema di Shannon, ma anche a problematiche che riguardano, tra le altre cose, il passo di quantizzazione e la lunghezza di parola del processore utilizzato.

• Sintesi diretta della risposta piatta: Il candidato dovrà spiegare come sia possibile ottenere una risposta a ciclo chiuso pari a z^(-n) e in quali condizioni

</details>
