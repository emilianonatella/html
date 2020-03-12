# Tag **`<select>`** e **`<option>`**



Il tag **`select`** si inserisce all’interno del form e consente di effettuare una scelta da un elenco di voci specificate dal tag **`option`**.



#### Tag select

Il tag **select** in genere ha l’**attributo name**, come da esempio:

```html
<select name=""> </select>
```

#### Tag option

Il tag **option** si inserisce all’interno del tag select e ha in genere l’**attributo name** che specifica il nome**,** l’**attributo value** che specifica il valore che deve essere inviato e l’**attributo selected** che specifica la voce preselezionata.

```html
<form name="invio_dati" action="URL_personalizzata" method="post">
<p><input name="nome" placeholder="Nome"></p>
<p><input name="mail" placeholder="Email"></p>
<p>
<input name="sesso" type="radio" value="maschio"> maschio
<input name="sesso" type="radio" value="femmina"> femmina
</p>
<select name="regione"> 
     <option value="1" selected>Abruzzo</option>
     <option value="2">Basilicata</option>
     <option value="2">Calabria</option>
     <option value="3">Campania</option>
     <option value="4">Emilia-Romagna</option>
     <option value="5">Friuli-Venezia Giulia</option>
     <option value="6">Lazio</option>
     <option value="7">Liguria</option>
     <option value="8">Lombardia</option>
     <option value="9">Marche</option>
     <option value="10">Molise</option>
     <option value="11">Piemonte</option>
     <option value="12">Puglia</option>
     <option value="13">Sardegna</option>
     <option value="14">Sicilia</option>
     <option value="15">Toscana</option>
     <option value="16">Trentino-Alto Adige</option>
     <option value="17">Umbria</option>
     <option value="18">Valle d'Aosta</option>
     <option value="19">Veneto</option>
</select>
<p>
<textarea name="messaggio" rows="5" cols="50" placeholder="inserisci un messaggio"></textarea></p>
<p>
<input name="invia" type="submit">
</p>
</form>
```

![select option](https://www.codingcreativo.it/wp-content/uploads/2019/03/select_option.jpg)

