# Plugin Checkup – archivio di compatibilità

`compat.json` contiene le dichiarazioni dei produttori di plugin e DAW sulla compatibilità con le versioni di macOS.
L'app Plugin Checkup lo scarica a ogni checkup per dire se è il momento giusto per aggiornare macOS.

Stati: `ok`, `update` (serve almeno la versione `min`), `issue` (problemi noti), `wait` (il produttore sta testando o consiglia di aspettare), `no` (non supportato), `unknown` (nessuna dichiarazione).
Ogni voce riporta la fonte (`source`) e la data dell'ultimo controllo (`checked`).

Le informazioni vengono dalle dichiarazioni pubbliche dei produttori: verifica sempre sul sito del produttore prima di aggiornare.
