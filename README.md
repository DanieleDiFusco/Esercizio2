# Vetrina Prodotti

Questo progetto mostra una vetrina di prodotti caricati dinamicamente da un file JSON, con un design moderno e responsive.

## File presenti

- **index.html**  
  Pagina principale del sito. Visualizza i prodotti leggendo i dati da `prodotti.json` tramite JavaScript e fetch.

- **prodotti.json**  
  File contenente la lista dei prodotti in formato JSON.

## Come usare

1. **Scarica entrambi i file** nella stessa cartella.
2. **Avvia un server locale** nella cartella dove si trovano i file.  
   Puoi usare, ad esempio, Python:
   ```
   python -m http.server
   ```
   oppure l'estensione **Live Server** di VS Code.
3. **Apri il browser** e vai su `http://localhost:8000/index.html` (o l'indirizzo indicato dal server).

> ⚠️ **Nota:**  
> Se apri `index.html` con doppio click (percorso `file://...`), il caricamento dei prodotti non funzionerà a causa delle restrizioni di sicurezza dei browser.  
> Usa sempre un server locale per vedere la vetrina funzionare correttamente.

## Personalizzazione

- Puoi modificare `prodotti.json` per aggiungere, rimuovere o cambiare i prodotti mostrati nella vetrina.
- Puoi personalizzare lo stile modificando il CSS all'interno di `index.html`.

---

**Autore:**  
Daniele
