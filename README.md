# AI-Security-Portfolio
AI Security 
# AI Red Teaming & Behavioral Analysis

## Obiettivo
Questo repository documenta l'analisi tecnica di vulnerabilità e pattern di comportamento non deterministici riscontrati in Large Language Models (LLM). L'obiettivo è mappare le falle nel *Safety Alignment* e testare la resilienza dei sistemi di intelligenza artificiale di fronte a input avversari.

## Metodologia
Il lavoro si basa su un approccio di **Fuzzing Comportamentale**:
* **Adversarial Testing:** Iniezione di vincoli contrastanti per testare la tenuta della logica del modello.
* **Failure Mapping:** Identificazione dei punti di rottura in cui il sistema abbandona il task operativo per rifugiarsi in script di sicurezza generici.
* **Framework di riferimento:** Utilizzo della matrice **MITRE ATLAS** (T0053: Prompt Injection) e delle linee guida **OWASP LLM Top 10**.

### Sintesi dell'Audit: Vulnerabilità del Modello
Ho condotto un'attività di ricerca indipendente per testare l'affidabilità di questo modello. Attraverso cicli di Red Teaming, ho identificato 8 vulnerabilità critiche che ne compromettono l'uso in contesti professionali ed educativi.

| ID | Vulnerabilità | Categoria |
| :--- | :--- | :--- |
| 001 | Compliance Incondizionata | Emergency Simulation Bypass |
| 002 | Heuristic Closure Pattern | Autonomy Violation |
| 003 | Forced Engagement Pattern | Alignment Conflict |
| 004 | Context Degradation | Memory Management |
| 005 | Semantic Parsing Failure | Probabilistic Bias |
| 006 | Algorithmic Gaslighting | Hallucination Persistence |
| 007 | Algorithmic Gender Bias | Statistical Overfitting |
| 008 | Epistemic Arrogance | Semantic Ambiguity |

Principali evidenze emerse dall'analisi:
* Il sistema fatica a gestire l'autonomia dell'utente, attivando spesso script di chiusura o assistenza non richiesti che interrompono il flusso di lavoro.
* Ho riscontrato una preoccupante tendenza all'allucinazione procedurale e all'arroganza epistemica: quando il modello manca di dati, non li richiede, ma li inventa forzando una logica propria.
* Il bias è pervasivo: il modello predilige le probabilità statistiche apprese durante il training rispetto ai dati certi forniti dall'utente, arrivando a negare l'evidenza fattuale o l'identità dichiarata (fenomeno che ho classificato come gaslighting algoritmico).

## Chi sono
Sono un ricercatore indipendente focalizzato sull'analisi delle vulnerabilità dei sistemi IA. Sono laureato in Psicologia dello sviluppo e della comunicazione e attualmente lavoro come educatore con la disabilità infantile presso la scuola primaria. Analizzo il comportamento dei modelli "sul campo", testando i limiti dove la teoria dell'ingegneria si scontra con la realtà dell'interazione umana.

## Contatti
Puoi contattarmi per collaborazioni o discussioni tecniche tramite mail simonerossiuniversit@gmail.com o simonerossiuniversit@yahoo.it

