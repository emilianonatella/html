# Attributi del tag `<form>`

I principali attributi del **tag form**, come visto nell'esempio, sono i seguenti:

- **method** - specifica il metodo di invio dei dati ed accetta i valori **get** o **post**;

- **action** - specifica lo script che riceverà, controllerà ed elaborerà i dati.

- **target** - specifica se il frutto dell'elaborazione (effettuata dallo script indicato in *action*) verrà mostrata nella stessa finestra oppure in un altra.


---  
#### Attributo `action` del tag form

L’attributo **action** serve a specificare l’azione che il browser deve effettuare quando il form viene "eseguito", ovvero quando si fa clic sul pulsante invia.

L’attributo action può avere come valore:

* un **URL** 

* un **indirizzo mail** 

  Può anche essere non specificato e lasciato vuoto, significa che di default imposta come URL la pagina stessa

  
Per intenderci l’**URL** (Universal Resource Locator) è una stringa di caratteri che identifica in maniera univoca una pagina all’interno della rete. 

Ad esempio, un URL può avere una forma del tipo:

https://www.w3schools.com/html/html_forms.asp

Dove **https** è il **protocollo**, in questo caso è https ma potrebbe anche essere diverso;

**www.w3schools.com** convenzionalmente è il nome di **dominio**, più precisamente definito Authority.

**/html/** è il path ovvero il cammino per raggiungere la pagina.

```html
<form action=”URL_personalizzata“>…</form> 
```



Oppure si può indicare un indirizzo mail usando **mailto,** come da esempio:

```html
<form action="mailto:nomecognome@gmail.com">  
```


---
#### Attributo `method` del tag form in html

L’attributo **method** determina il modo in cui i dati vengono mandati al server e può assumere due valori:

**get** – valore di default che passa i parametri che saranno visibili in alto nell’url della barra degli indirizzi.

**post** – invia i dati in modo che non possono essere tracciati nella barra degli indirizzi del browser.

Quindi ad esempio volendo scegliere il metodo post dovrei specificare come di seguito:

```html
<form action=”URL_personalizzata” method=”post”>…</form> 
```


---
#### Attributo `name` del tag form in html

L’attributo **name** è il nome che si vuole assegnare al form, ad esempio:

```html
<form name=”invio_dati” action=”URL_personalizzata” method=”post”>…</form>
```



---
#### Attributo `enctype` del tag form html

L’attributo **enctype** indica il tipo di codifica da utilizzare. 

Questo attributo di default è impostato su questo valore: “application/x-www-form-urlencoded”, che sta ad indicare che tutti i caratteri vengono codificati e i caratteri speciali vengono convertiti. Quindi se vogliamo trasmettere solo dati questo attributo può essere omesso.

Nel momento in cui invece dobbiamo trasmettere un file, come ad esempio un’**immagine** allora dobbiamo modificarlo nel valore: “**multipart/form-data**“.

```html
<form method="URL_personalizzata" method="post" enctype="multipart/form-data">
...
</form> 
```

C’è anche un altro valore da poter inserire: “text/plain”, il quale indica che i caratteri non devono essere codificati ma è usato molto più raramente.


