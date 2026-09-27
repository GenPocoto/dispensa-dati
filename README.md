# Dati per FrigoDispensa

File scaricati dal tasto **Opzioni → Aggiorna codici e ricette** dell'app FrigoDispensa
(app personale per la dispensa di casa). Ogni rilascio contiene:

| File | Contenuto | Licenza |
|---|---|---|
| `manifest.json` | versioni, nomi dei file e impronte SHA-256 | — |
| `catalogo_off_it.db.gz` | circa 320.000 prodotti venduti in Italia: codice a barre, nome, marca, formato, categoria (SQLite, compresso) | ODbL 1.0 |
| `ricette.json` | ricette italiane: originali e da Wikibooks, con la fonte su ognuna | CC BY-SA 4.0 |

L'app legge sempre l'ultimo rilascio:
`https://github.com/<utente>/<repository>/releases/latest/download/manifest.json`.

Vedi [LICENZE.md](LICENZE.md) per fonti e attribuzioni.
