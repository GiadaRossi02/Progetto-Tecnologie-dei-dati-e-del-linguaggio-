# Analisi comparativa delle capacità linguistiche e decodificative degli LLM: Cifrari a sostituzione vs conlang
**Autore:** Giada Rossi 
**Corso:** Tecnologie dei dati e del linguaggio
**Anno Accademico:** 2025/2026  

---

## Inquadramento del progetto

Questo progetto propone uno studio empirico-sperimentale sulle prestazioni dei modelli di linguaggio di grandi dimensioni (LLM) quando posti di fronte a linguaggi non standard.

L'analisi mette a confronto due diversi sistemi di alterazione linguistica:
1. **Cifrario a Sostituzione Meccanica:** Codice deterministico basato su mappatura carattere-per-carattere.
2. **Trigedasleng:** Lingua artificiale creola a basse risorse derivata dall'inglese (dalla serie TV *The 100*).

---

## Domanda di Ricerca
> *Come si comporta un LLM di fronte a due differenti tipologie di alterazione linguistica non standard? Nello specifico, il modello gestisce meglio una codifica puramente meccanica (cifrario a sostituzione) oppure una lingua artificiale con strutture grammaticali e lessicali proprie (Trigedasleng)? Che tipo di ragionamento applica per la decodifica e la generazione? All'aumentare della complessità del testo, il modello rimane coerente o tende ad appiattirsi verso le lingue originali?*

---

## Metodologia e Architettura del Codice

L'intero progetto è stato sviluppato in ambiente cloud **Google Colab** in linguaggio **Python**, sfruttando un LLM come supporto al coding e al refactoring.

---

## Protocollo Sperimentale

Gli esperimenti di decodifica, traduzione e generazione creativa sono stati condotti secondo un rigoroso protocollo:
- **Fresh Chat:** Ogni test è stato eseguito su un'istanza pulita del modello per azzerare la memoria a breve termine e prevenire il *context bias*.
- **Zero-Shot Prompting:** Nessuna chiave di cifratura o vocabolario di supporto è stato fornito preventivamente al modello durante la fase di testing.

---

## Struttura del Repository

- `RossiGiada_Progetto.ipynb`: Notebook Google Colab contenente il codice Python utilizzato per l'elaborazione del dataset, l'estrazione delle metriche NLP e la generazione automatica dei grafici.
- `RossiGiada_Progetto.pdf`: Slide di supporto per la discussione orale del progetto.
- `README.md`: Documento di sintesi e inquadramento del progetto.
