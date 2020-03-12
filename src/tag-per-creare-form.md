# Tag per creare form html

Una volta definito un form mediante l'omonimo tag sarà necessario "popolarlo" con una serie di tag annidiati al suo interno. Attraverso i singoli tag (che andremo a vedere tra poco), infatti, sarà possibile creare i vari elementi per l'interazione con l'utente come, ad esempio, caselle di testo o menu di selezione.

Passiamo adesso in rassegna i singoli tag che generano gli elementi dei form HTML:

- **`input`** - genera la maggior parte degli elementi dei form HTML, a seconda del type specificato. Gli input più utilizzati sono:
  - **`text`** - è utilizzato per creare *caselle di testo* in cui l'utente può scrivere del contenuto su "singola linea";
  - **`file`** - è utilizzato per creare *caselle di selezione di file in locale* al fine di poterli trasmettere al server remoto;
  - **`radio`** - permette di creare un gruppo di opzioni al cui interno deve essere fatta una scelta (non ammette scelte multiple);
  - **`checkbox`** - permette di creare un gruppo di opzioni al cui interno devono essere fatta delle scelte (ammette scelte multiple);
  - **`button`** - permette di creare bottoni "neutri" ai quali, cioè, può essere associata un'azione mediante Javascript;
  - **`submit`** - permette di creare bottoni di invio attraverso i quali viene, appunto inviato e processato il form;
  - **`image`** - permette di inserire immagini "attive" all'interno del modulo che fungeranno da bottoni;
  - **`reset`** - permette di creare bottoni per il reset del form (in sostanza vengono cancellate le scelte effettuate dall'utente ed il modulo torna al suo stato iniziale).
- **`select`** - crea una casella di riepilogo a scorrimento, chiamata in gergo **selectbox**;
- **`textarea`** - genera un'area di testo in cui è possibile andare a capo e viene utilizzata per permettere di inserire descrizioni, commenti o comunque testi piuttosto lunghi.