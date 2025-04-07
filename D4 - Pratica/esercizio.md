## Consegna esercizio

Partendo da un gioco con meccaniche semplici e ben definite, come gli Scacchi o il Tris, si possono modificare queste meccaniche per generare nuove dinamiche di gioco.
Descrivere poi delle dinamiche derivanti dai cambiamenti fatti.

Cambiando anche solo una singola meccanica - ad esempio aggiungendo un vincolo, una nuova azione o una regola speciale - il comportamento del gioco cambia, creando nuove strategie, ritmi e interazioni tra i giocatori.


## Svolgimento

### Meccanica modificata: nuova azione per il pedone
Il gioco di cui vorrei cambiare una meccanica, è quello degli **scacchi**. In particolare vorrei **aggiungere** come meccanica, una nuova possibile azione per i **pedoni**:
- il pedone può essere **scambiato** con uno dei propri pezzi ancora in gioco. Il turno finisce dopo lo scambio (quindi il pezzo che prende il posto del pedone non può muoversi immediatamente).

### Dinamiche derivanti
Con questa nuova meccanica i pedoni assumono un ruolo ancora più importante, sia in attacco che difesa:
- **attacco**: posizionare attentamente un pedone in una zona avanzata abbastanza sicura della scacchiera consente di *infiltrare* dei propri pezzi alle spalle di quelli avversari. **NB**: poiché il turno termina dopo lo scambio il giocatore deve prestare attenzione a dove si trovare quando effettua lo scambio. Portare il pedone troppo vicino alle pedine avversarie potrebbe significare veder mangiato immediatemente il pezzo scambiato, senza possibilità di utilizzarlo;
- **difesa**: il pedone diventa una sorta di *punto di salvataggio*: quando un pezzo inizia a ritrovarsi in una zona *pericolosa* della scacchiera può essere portato in salvo, scambiandolo col pedone in zona sicura.

### Rischi e possibili soluzioni
La nuova meccanica potrebbe rendere troppo potente il pedone che già di per sé, se portato in fondo alla scacchiera, può trasformarsi in un qualsiasi pezzo eccetto il Re. Nel caso in cui la meccanica risultasse troppo sbilanciata e forte, si potrebbe pensare di rendere lo scambio più *costoso*: il pedone non viene scambiato ma viene **eliminato** dopo lo scambio. In questa maniera scambiare un proprio pezzo ha un costo maggiore, e bisogna pensare molto bene prima di utilizzare questa mossa.
