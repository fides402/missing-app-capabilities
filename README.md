# missing-app-capabilities

File pubblico delle capacità usato da **MISSING APP**: `capabilities.json`.
L'app lo scarica da sola (all'apertura, quando ci si torna e ogni 3 ore). Viene aggiornato da Claude Code quando compaiono nuove infrastrutture o abilità.

Formato: `{ version, generated, basis, capabilities: [ { id, cluster, name, status, desc, evidence, in, out, limits } ] }`
- `status`: dimostrata | probabile | ipotizzata
- `in` / `out`: testo, audio, midi, voce, pagina_web, file, ui, dati, any

Indirizzo per l'app: `https://raw.githubusercontent.com/fides402/missing-app-capabilities/main/capabilities.json`
