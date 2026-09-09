# Un mare di dati o una connessione umana?
### Analisi computazionale e Context Awareness tra l’Odissea di Omero e la reinterpretazione di Christopher Nolan.

<a href="VISENTIN_TDL.pdf" target="_blank">📊 Clicca qui per visualizzare le Slide di Presentazione a schermo intero</a>



## 📌 Identità del Progetto
* **Esame:** Tecnologie dei dati e del linguaggio
* **Modello NLP Utilizzato:** SpaCy (`en_core_web_lg` - Word Embeddings a 300 dimensioni)
* **Ambiente di Sviluppo:** Google Colab

---

## 📝 Abstract della Ricerca
Questo progetto di ricerca si propone di misurare quantitativamente e semanticamente la distanza tra il poema classico dell'Odissea di Omero e la sceneggiatura cinematografica del film Odyssey di Christopher Nolan. Sfruttando le metodologie del Natural Language Processing (NLP) e il modello linguistico avanzato basato su embeddings di SpaCy, l'analisi ha superato i limiti letterali del Text Mining statistico. L'algoritmo ha registrato un indice di somiglianza semantica globale straordinariamente elevato (0.9728), dimostrando che la macchina è in grado di decodificare l'analogia concettuale tra il viaggio mitologico marino e l'epopea psicologica moderna. Successivamente, l'esperimento ha testato la Context Awareness del sistema integrando dati di contesto esterni. Sottoponendo alla macchina la filmografia del regista, il sistema ha isolato una correlazione massima con Inception (0.9096), riconoscendo matematicamente il nucleo psicologico del Nostos (l'ossessione del ritorno a casa). Infine, l'analisi della critica specializzata e del dibattito culturale ha rivelato la capacità del modello di mappare la polarizzazione delle opinioni umane, premiando la recensione strutturale di Script Magazine (0.9349) e isolando la divergenza concettuale della critica accademica. In conclusione, la ricerca dimostra che un sistema di Intelligenza Artificiale, se opportunamente guidato dall'iniezione di dati di contesto, non si limita a decifrare la superficie testuale, ma è in grado di comprendere l'identità autoriale e le connessioni semantiche profonde che legano il mito classico alla cultura contemporanea.

---

## 📊 Sintesi dei Risultati Decimali (Cosine Similarity)

| Testo A | Testo B / Contesto | Punteggio (0.0 a 1.0) | Significato Critico |
| :--- | :--- | :--- | :--- |
| **Omero: Odyssey** | **Nolan: Screenplay** | **0.9728** | Invarianza semantica profonda del mito |
| Nolan: Screenplay | *Inception* (Filmografia) | **0.9096** | Core psicologico comune (Il Ritorno a Casa) |
| Nolan: Screenplay | *Interstellar* (Filmografia) | **0.8866** | Macro-ambientazione e relatività del tempo |
| Nolan: Screenplay | *Tenet* (Filmografia) | **0.8541** | Complessità strutturale e concetto di destino |
| Nolan: Screenplay | *Script Magazine* (Critica) | **0.9349** | Massima aderenza alla struttura della sceneggiatura |
| Nolan: Screenplay | *The Times* (Critica) | **0.8996** | Condivisione dello spazio semantico epico |
| Nolan: Screenplay | *Emily Wilson* (Critica) | **0.8874** | Isolamento matematico della divergenza filologica |

