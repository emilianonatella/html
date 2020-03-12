# Il tag **`<form>`**

Per la creazione di un form utilizziamo l'omonimo tag **form**, come nell'esempio che segue:

```html,editable
<form method="" action="" target="">
...
</form>
```

Scopo di questo tag è di fare da **contenitore** ad una serie di tag (che vedremo tra poco) che costituiranno gli specifici controlli del modulo.

I principali attributi del **tag form**, come visto nell'esempio, sono i seguenti:

- **method** - specifica il metodo di invio dei dati ed accetta i valori **get** o **post**;
- **action** - specifica lo script che riceverà, controllerà ed elaborerà i dati.
- **target** - specifica se il frutto dell'elaborazione (effettuata dallo script indicato in *action*) verrà mostrata nella stessa finestra oppure in un altra.