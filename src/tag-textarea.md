# Tag **`<textarea>`**

Continuaimo a costruire il form in html utilizzando il tag **textarea** che permette di creare un’area nella quale inserire del testo, specificando l’attributo **name**, il numero di righe con l’attributo **rows** e il numero di colonne con l’attributo **cols**. In pratica rows e cols non sono altro che la larghezza e l’altezza di una textarea.

Un esempio di form in html:

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
<textarea name="messaggio" rows="5" cols="50" placeholder="inserisci un messaggio"></textarea></p>
<p>
<input name="invia" type="submit">
</p>
</form>
```

![textarea in html](https://www.codingcreativo.it/wp-content/uploads/2019/03/textarea_html-1.jpg)