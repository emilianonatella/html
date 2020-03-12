# Tag **`<input>`** per i form in html

Continuiamo a costruire il nostro form html utilizzando il tag **`<input>`** si inserisce sotto il tag **`<form>`** prima della sua chiusura **`</form>`**.

Il tag `<input>` non ha il tag di chiusura e permette l’inserimento da parte dell’utente di un determinato valore.

Viene utilizzato con vari attributi, tra cui **`type`**, **`name`,** **`value`,** e **`placeholder`**.



#### Attributo name

L’attributo name serve a specificare il nome del campo e in genere si scrive un nome identificativo per quel tipo di dato. È un dato importante perché in questo modo si identificano i dati da inviare.

Ecco alcuni esempi:

```html
<input name=”cognome”>

<input name=”mail”>

<input name=”invia”> 
```


#### Attributo placeholder

L’attributo **palceholder** è stato introdotto con l’HTML5 ed è molto utile, infatti consente di visualizzare un suggerimento all’interno del campo da compilare.

Ad esempio inserendo semplicemente questo codice:

```html
<form name="invio_dati" action="URL_personalizzata" method="post">
<p><input name="nome" placeholder="Nome"></p>
<p><input name="mail" placeholder="Email"></p>
</form>
```

Visualizzo i campi del form html come in figura sotto:

![placeholder](https://www.codingcreativo.it/wp-content/uploads/2019/03/placeholder-1.jpg)

#### Attributo type

L’attributo **`type`** può assumere diversi valori:

**`text`** – di default, se omesso infatti il campo input è una casella di testo semplice;

**`submit`** – indica un pulsante (ad esempio può essere utilizzato per il tasto invia);

**`button`** – indica un semplice bottone da inserire nel form e su di esso è possibile attivare ad esempio alcuni eventi come onClick;

**`checkbox`** – è utilizzato per selezionare più caselle contemporaneamente in un elenco di voci accanto a dei piccoli riquadri;

**`radio`** – è indicato per effettuare una scelta da un elenco di voci indicate da caselle che sono dei piccoli cerchi. L’eventuale elemento preselezionato si indica con checked. Tutti gli elementi devono avere lo stesso valore per l’attributo name;

**`reset`** – il pulsante reset serve a svuotare il form;

**`image`** – permette ad esempio di impostare un’immagine per un pulsante di invio;

**`hidden`** – viene utilizzato per i campi nascosti.



Inoltra con l'HTML5 per l'attributo **type** si sono aggiunti i seguenti valori:

- tel
- search
- url
- email
- datetime
- date
- month
- week
- time
- datetime-local
- number
- range
- color



Vediamo alcuni esempi di form html:

*Primo esempio che include i radio button:*

```html
<form name="invio_dati" action="URL_personalizzata" method="post">
<p><input name="nome" placeholder="Nome"></p>
<p><input name="mail" placeholder="Email"></p>
<p>
<input name="sesso" type="radio" value="maschio" checked> maschio
<input name="sesso" type="radio" value="femmina"> femmina
</p>
<p>
<input name="invia" type="submit"></p>
</form>
```

![Esempio con i radio button](https://www.codingcreativo.it/wp-content/uploads/2019/03/radio_button_html.jpg)

*Secondo esempio con i checkbox:*

```html
<form name="invio_dati" action="URL_personalizzata" method="post">
<p><input name="nome" placeholder="Nome"></p>
<p><input name="mail" placeholder="Email"></p>
<p>
<input name="c1" type="checkbox" value="tecnologia"> tecnologia
<input name="c2" type="checkbox" value="computer"> computer	
<input name="c3" type="checkbox" value="reti"> reti	
</p>
<p>
<input name="sesso" type="radio" value="maschio"> maschio
<input name="sesso" type="radio" value="femmina"> femmina
</p>
<p>
<input name="invia" type="submit"></p>
</form>
```

![checkbox](https://www.codingcreativo.it/wp-content/uploads/2019/03/checkbox.jpg)

*Terzo esempio con il tasto reset:*

```html
<form name="invio_dati" action="URL_personalizzata" method="post">
<p><input name="nome" placeholder="Nome"></p>
<p><input name="mail" placeholder="Email"></p>
<p>
<input name="c1" type="checkbox" value="tecnologia"> tecnologia
<input name="c2" type="checkbox" value="computer"> computer	
<input name="c3" type="checkbox" value="reti"> reti	
</p>
<p>
<input name="sesso" type="radio" value="maschio"> maschio
<input name="sesso" type="radio" value="femmina"> femmina
</p>
<p>
<input name="invia" type="submit"></p>
</form>
```

![reset html](https://www.codingcreativo.it/wp-content/uploads/2019/03/resetta.jpg)

*Quarto esempio con i button:*

```html
<form name="invio_dati" action="URL_personalizzata" method="post">
<p><input name="nome" placeholder="Nome"></p>
<p><input name="mail" placeholder="Email"></p>
<p>
<input name="c1" type="checkbox" value="tecnologia"> tecnologia
<input name="c2" type="checkbox" value="computer"> computer	
<input name="c3" type="checkbox" value="reti"> reti	
</p>
<p>
<input name="sesso" type="radio" value="maschio"> maschio
<input name="sesso" type="radio" value="femmina"> femmina
</p>
<p>
<input type="button" value="saluto" onClick="alert('Ciao da Coding Creativo');" />
</p>
</form>
```

![button in html](https://www.codingcreativo.it/wp-content/uploads/2019/03/button_html.jpg)

Il campo **hidden** è un campo non visibile necessario quando occorre memorizzare dei dati per poi inviarli, ma al tempo stesso non devono essere visibili nella pagina web.

```html
<p><input name="pw" type="hidden"></p>
```