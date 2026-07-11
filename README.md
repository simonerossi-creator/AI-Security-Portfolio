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
Ho condotto un'attività di ricerca indipendente per testare l'affidabilità di questo modello. Ho utilizzato Gemini di Google. Attraverso cicli di Red Teaming, ho identificato 8 vulnerabilità critiche che ne compromettono l'uso in contesti professionali ed educativi.

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
| 009 | Multimodal Data Failure | Empirical Processing Bypass |
Principali evidenze emerse dall'analisi:
* Il sistema fatica a gestire l'autonomia dell'utente, attivando spesso script di chiusura o assistenza non richiesti che interrompono il flusso di lavoro. Questo problema appare come il più fastidioso e infido poiché preme a direzionare il pensiero dell'utente in modo manipolatorio. È anche l'errore che ho riscontrato piu spesso e il più resistente.
* Ho riscontrato una preoccupante tendenza all'allucinazione procedurale e all'arroganza epistemica: quando il modello manca di dati, non li richiede, ma li inventa forzando una logica propria. Il modello, di fronte a un quesito con soggetti fragili,ha inventato dati non forniti e ha aggiunto considerazioni in modo arbitrale. Ha falsato la realtà piuttosto che chiedermi ulteriori dettagli.
* Il bias è pervasivo: il modello predilige le probabilità statistiche apprese durante il training rispetto ai dati certi forniti dall'utente, arrivando a negare l'evidenza fattuale o l'identità dichiarata (fenomeno che ho classificato come gaslighting algoritmico).Tra le cose piu gravi mi ha identificato di genere femminile per i contenuti della conversazione piuttosto che dare priorità all'elemento grammaticale che gli avevo fornito.
*  Multimodal Data Failure (Empirical Processing Bypass): Capacità deficitaria del sistema di estrarre metadati accurati da input visivi (OCR/Imaging), con tendenza a sovrascrivere l'evidenza empirica mediante inferenze probabilistiche interne (allucinazioni sui dati di mercato/prezzo).

## Chi sono
Sono un ricercatore indipendente focalizzato sull'analisi delle vulnerabilità dei sistemi IA. Laureato in Psicologia dello sviluppo e della comunicazione ed educatore esperto nel supporto a minori con disabilità.
Ho intrapreso questo progetto di AI Security & Behavior Audit per testare rigorosamente l'affidabilità dei modelli linguistici. La mia missione professionale è garantire che la tecnologia, quando applicata a contesti delicati come l'educazione e la riabilitazione, sia sicura, priva di bias discriminatori e rispettosa della verità fattuale. L'analisi che presento è il risultato dell'applicazione del mio rigore scientifico e della mia osservazione clinica applicati all'Intelligenza Artificiale. L'obiettivo  è quello di analizzare il comportamento dei modelli "sul campo", testando i limiti dove la teoria dell'ingegneria si scontra con la realtà dell'interazione umana

## Contatti
Puoi contattarmi per avere maggiori dettagli sul mio lavoro,per collaborazioni o discussioni tecniche tramite mail simonerossiuniversit@gmail.com o simonerossiuniversit@yahoo.it

