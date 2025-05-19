# HTML5 dla poczatkujacych

# HTML5 dla poczatkujacych

## How HTML and Browser Works

**(HyperText Markup Language) – hipertekstowy język znaczników**


Silniki wyświetlania stron internetowych

* [http://pl.wikipedia.org/wiki/Gecko Gecko (Mozilla Firefox)]
* [http://pl.wikipedia.org/wiki/WebKit WebKit (Google Chrome, Safari)] 
* [http://pl.wikipedia.org/wiki/Presto_%28silnik_przegl%C4%85darki%29 Presto (Opera)]
* [http://pl.wikipedia.org/wiki/Trident_%28silnik_przegl%C4%85darki%29 Trident (Internet Explorer)]

## Editor for HTML
* Edytorem do kodu HTML oraz CSS moze być każdy edytor tekstowy.
* Dobrze jeżeli edytor koloruje nam kod strony łatwiej i szybciej będziemy wtedy tworzyć stronę.
* Edytory Kodu HTML posiadają uzupełnianie kodu które bardzo przyspiesza proces pisania stron.
* Edytory kodu mają dodatkowe progamy, w których wpisujemy tylko wartości a resztę kodu wypełnia automat.

## Co wykonmamy?
**Stworzymy stronę WWW**

[[File:000-index.jpg |300px]]

[[File:002-proceswinifikacji.jpg |300px]]

[[File:003-podzialwin.jpg |300px]]

[[File:004-historia.jpg |300px]]

[[File:005-glowniproducenci.jpg |300px]]

[[File:006-ciekawostki.jpg |300px]]

[[File:007-linki.jpg |300px]]

[[File:008-kontakt.jpg |300px]]

[[File:009-av.jpg |300px]]

## HTML Document Structure
<pre>
  <!DOCTYPE HTML>
  <html>
   <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Tytuł dokumentu pojawia się na pasku przeglądarki</title>
   </head>
   <body>
    <!-- Tresc strony -->
   </body>
  </html>
</pre>

### HTML Tag (P)
**Paragraf - (Akapit).** Służy do zaznaczania akapitów.
<pre><p>Tekst ...</p></pre>

### HTML Tag (H1,...,H6)
**Hedline - (Nagłówek).** Zaznaczamy tytuł rozdziału, podrozdzialu poziomu od 1 do 6.
<pre>
 <h1>Tytuł</h1>
 <h2>Rozdział</h2>
 <h3>Podrozdział</h3>
 ...
 <h6>... </h6>
</pre>
<br />

### HTML Tag (I, B, EM, STRONG)
**Italic (pochylony).**

**Bold (pogrubiony).** 

**Emfasis (wyróznienie pochylenie).**

**Strong (mocne wyróznienie tekstu pogrubienie).**

<pre>
 <i>tekst pochylony</i>
 <b>tekst pogrubiony</b>
 <em>tekst wyrózniony</em>
 <strong>tekst mocno wyrózniony</strong>
</pre>

<i>tekst pochylony</i>

<b>tekst pogrubiony</b>

<em>tekst wyrózniony</em>

<strong>tekst mocno wyrózniony</strong>
<br />

### HTML Tag (BLOCKUOTE, Q)
**Blockquote (Wcięcie).**

**Q (Cytat).** 
<pre>
</pre>

### HTML Tag (OL, LI)
**Ordered List (Lista numerowana).**

<pre>
 <ol>
   <li>numeracja nadrzedna</li>
    <ol>
     <li>numeracja podrzedna</li>
     <li>numeracja podrzedna</li>
    </ol>
   <li>numeracja nadrzedna</li>
  </ol>
</pre>

<ol>
   <li>numeracja nadrzedna</li>
    <ol>
     <li>numeracja podrzedna</li>
     <li>numeracja podrzedna</li>
    </ol>
   <li>numeracja nadrzedna</li>
  </ol>
<br />

### HTML Tag (UL, LI)
**Unorder List (Lista punktowana).**

<pre>
<ul>
 <li>nadrzedny</li>
   <ul>
    <li>podrzedny</li>
   </ul>
 <li>nadrzedny</li>
   <ul>
    <li>podrzedny</li>	
   </ul>
</ul>
</pre>

<ul>
 <li>nadrzedny</li>
   <ul>
    <li>podrzedny</li>
   </ul>
 <li>nadrzedny</li>
   <ul>
    <li>podrzedny</li>	
   </ul>
</ul>
<br />

### HTML Tag (DL, DT, DD)
**Definition List (Lista Definicji).**

**Definition Terms (Hasło Definicji).**

**Describe Definition (Opis Definicji).**

<pre>
<dl>
 <dt>hasło 1</dt> 
  <dd>opis1...</dd>
 <dt>haslo 2</dt>
  <dd>opis2...</dd>
</dl>
</pre>

<dl>
 <dt>hasło 1
  <dd>opis1...
 <dt>haslo 2
  <dd>opis2...
</dl>
<br />

### HTML Tag (BR and non-breaking space)
**Brake Line (wstawianie wolnej lini entera).**

**Non Breake space (spacja nie rozdzielajaca).**

<pre>
 <h1>Tytuł rozdziału</h1> 
 <p>tekst <br /> rozdziału</p>
 <br />
 <h1>Tytuł rozdzialu</h1>
 <p>tekst rozdzialu i&nbps;nowego rozdzialu</p>
</pre>
<br />

### HTML Tag (SUP, SUB)
**Subscript (index dolny).**

**Superscript (index górny).**

<pre>
 <p>100m<sup>2</sup> 
  <br/>
   10<sup>o</sup>C  
  <br/>
   H<sub>2</sub>O 
 </p>
</pre>

 <p>100m<sup>2</sup> 
  <br/>
   10<sup>o</sup>C  
  <br/>
   H<sub>2</sub>O 
 </p>
<br />

### HTML Tag (IMG, FIGURE, FIGCAPTION)
**Image (Obrazek).**

**Figure (rysunek, rysunki).**

**Figcaption (Podpis rysunku).**

<pre>
<figure>
  <img src="/obrazek.jpg" alt="Opis obrazka">
  <figcaption>Pospis pod obrazkiem</figcaption>
</figure>
</pre>

### HTML Tag (A)
**Anchor (Kotwica).** 

* ścieżka całkowita (absolute) 
* ścieżka względna (relative)
* skrót miejscowy
* skrót zewnętrzny
* skrót e-maiowy

<pre>
 <a href="http://www.nobleprog.pl" target="_blank">Copyright © www.NobleProg.pl</a>

 <a href="obrazki/obrazek.jpg">skrót do obrazka</a>
 
 <a href="#skrot001">skrot1</a> 
 <a name="skrot001"/>
 
 <a href="mailto:imie.nazwisko@serwer.pl">imie.nazwisko@serwer.pl</a> 

</pre>


### HTML Tag (TABLE, TH, TR, TD)
**Table (Tabelka).**

**Table Header (Nagłówek tabelki).**

**Table Row (Wiersz tabelki).**

**Table Data (Komórka tabelki).**

<pre>
<table border="1"  cellpadding="3" cellspacing="5" summary="streszczeine zawartosci tabeli">
 <caption>tabelka opisujaca łączenie komorek wierszy i kolumn.</caption>
  <tr>
   <th rowspan="2">Naglówek kolumny 1</th>
   <th colspan="2">Naglówek kolumny 2</th>
  </tr>
  <tr>
   <th>Naglówek kolumny 2</th>
   <th rowspan="2">Naglówek kolumny 3</th>
  </tr>
  <tr>
   <td>dane</td>
   <td>dane</td>
  </tr>
  <tr>
   <td>dane1</td>
   <td>dane1</td>
   <td>dane1</td>
  </tr>
  <tr>
   <td>dane2</td>
   <td>dane2</td>
   <td>dane2</td>
  </tr>
</table>
</pre>

<table border="1" summary="streszczeine zawartosci tabeli">
  <caption>tabelka opisujaca łączenie komorek wierszy i kolumn.</caption>

 <tr>
  <th rowspan="2">Naglówek kolumny 1</th>
  <th colspan="2">Naglówek kolumny 2</th>
 </tr>

 <tr>
  <th>Naglówek kolumny 2</th>
  <th rowspan="2">Naglówek kolumny 3</th>
 </tr>

 <tr>
  <td>dane</td>
  <td>dane</td>
 </tr>

 <tr>
  <td>dane1</td>
  <td>dane1</td>
  <td>dane1</td>
 </tr>

 <tr>
  <td>dane2</td>
  <td>dane2</td>
  <td>dane2</td>
 </tr>

</table>
<br />

### HTML Tag (DIV, HEADER, NAV, FOOTER)
**Div (Ramka, sekcja dowolna).**

**Header (sekcja nagłówka).**

**Navigation (sekcja nawigacyjna).**

**Footer (sekcja stopki).**


<pre>
<body>
 <header>
  <!-- hasla strony -->
 </header>

 <nav>
  <!-- nawigacja -->
 </nav>

 <div>
  <!-- teksty -->
 </div>

 <footer>
  <a href="http://www.nobleprog.pl" target="_blank">Copyright © www.NobleProg.pl</a>
  <time datetime="2011-12-01">2011</time>r.
 </footer>

</body>
</pre>

### HTML Tag (AUDIO)

<pre>
<audio id="audio" controls>
 <source src="audio/audio.mp3" type="audio/mp3" />
 <source src="audio/audio.ogg" type="audio/ogg" />
 <source src="audio/audio.wmv" type="audio/wmv" />
 Twoja przegladakra nie obsługuje audio.
</audio>
</pre>


### HTML Tag (VIDEO)
<pre>
<video width="480" height="234" controls preload="false">
 <source src="../videos/video.mp4" type="video/mp4" />
 <source src="../videos/video.webm" type="video/webm" />
 Twoja przegladakra nie obsługuje wideo.
</video>
</pre>

### HTML Tag (FORM, INPUT, TEXTAREA)
**Form (Formularz).**

**Input (wprowadzanie danych).**

**Textarea (wprowadzanie wielowierszowe).**


<pre>
<form name="form1" method="post" action="">

 <input name="email" type="text" id="email" accesskey="e" size="50"  required placeholder="twoj@email.pl" />

 <input type="text" size="50" list="employee" required placeholder="Wybierz dział..." value="Handlowiec" />

 <datalist id="employee">
  <option value="Zamowienia"/>
  <option value="Księgowość"/>
  <option value="Handlowiec"/>
 </datalist>

 <input name="title" type="text" id="title" size="50" placeholder="Tytuł wiadomości..." />

 <textarea name="text" cols="60" rows="15" id="text" placeholder="Treść wiadomości..."></textarea>

 <input type="date" min="2010-01-03" max="2011-12-30" value="2011-11-15"/>

 <input type="submit" name="submit" id="submit" value="wyslij">
</form>
</pre>

## CSS Document Structure
**(Cascade Style Sheet) - Kaskadowe akrusze stylów**

<pre>
/** Komentarze w programowaniu CSS **/


/* selektor elementów */
   selektor { cecha: wartosc }

   /* przyklad */
      p {color: red;}


/* selektor class, klasy */
   selektor.klasa { cecha: wartosc }

   /* przyklad */
      .kolor_czerwony {color: red;}
      a.kolor_czerwony {color: red;}
      /* w kodzie HTML umieszczany przypis do elementu <a class="kolor_czerwony">


/* selektor ID, identyfikatora */
   selektor#identyfikator { cecha: wartosc }

   /* przyklad */
      #naroznik_lewy {background:url(../obrazki/naroznik_lewy.jpg);}
      td#naroznik_lewy {background:url(../obrazki/naroznik_lewy.jpg);}
      /* w kodzie HTML umieszczany przypis do elementu <td id="naroznik_lewy"></td>


/* selektor pseudoelementow, pseudo klasy */
   selektor:pseudoklasa { cecha: wartosc }

   /* przyklad */
      a:hover { color: red; }
      p:first-letter {color: red;}

</pre>

### CSS Link to css File

**Html File**

<pre>
<link href="css/glowny.css" rel="stylesheet" type="text/css" />

</pre>

### CSS Tag (*, BODY)

<pre>
* {
   margin: 0px;
}

body {
   background-image: url(../obrazki/wino_kielich.png);
   background-repeat: no-repeat;
}

</pre>

### CSS (@import, @font-face, font-family)

<pre>
/** Podłączamy czcionkę **/
@import url('../fonts/carto/carto.css');
@import url('../fonts/theano/theano.css');

* {
   font-family: TheanoOldStyleRegular, CartoGothicStdBook, Verdana, Geneva, Arial, Helvetica, sans-serif;
   color: black;
   word-spacing: 2px;
}

</pre>

### CSS Tag (H1-H6, P)

<pre>
h1 {
   font-family: TheanoOldStyleRegular, Verdana;
   font-size: 30px;
   color: #f8edf0;
}

h2 {
   font-size: 16px;
   text-indent: 20px;
}

h3 {
   font-size: 14px;
   padding-left: 10px;
   padding-right: 10px;
   padding-top: 3px;
   padding-bottom: 3px;
   float:left;
   margin-right: 10px;
   border-radius: 5px;
   box-shadow: 2px 2px 6px rgba(20,20,20,0.3);	
}
p {
   font-size: 12px;
   line-height: 20px;
   margin-bottom: 30px;
}

</pre>

### CSS Tag (HEADER)

<pre>
header {
   float: left;	
   -webkit-transform: rotate(270deg) translate(-400px, -40px);
   -moz-transform: rotate(270deg) translate(-400px, -40px);
   -o-transform: rotate(270deg) translate(-400px, -40px);
   opacity: 0.2;
   text-shadow: 2px 2px 6px rgba(10,10,10,0.9);
}

header h1, header h2 {
   font-size: 90px;
   line-height: 60px;
}
	
header h2 {
   font-size: 35px;
}

</pre>

### CSS Tag,ID (NAV, #menu, #higlighted)

<pre>
a h1 {
   font-family: Verdana;
   font-size: 20px;
   height: 42px;
}

#menu {
   float: left;
   position: absolute;
   margin-left: 50px;
   margin-top: 80px;
   border: solid;
   border-color: #b76a7f;
   border-width: 1px;
}

#menu a {
   font-family: Verdana;
   padding-left: 7px;
   padding-top: 3px;
   padding-bottom: 3px;
   display: block;
   border: solid;
   border-color: #b76a7f;
   border-width: 1px;
   width: 160px;
   text-decoration: none;
   margin: -1px;
   color: #ffe5f3;
   text-transform: uppercase;
   font-weight: bold;
   font-size: 13px;
}

#menu a:hover {
   background-color: #f0a3b8;
}

#menu {
   height: 48px;
   overflow: hidden;
   -webkit-transition-property: height;
   -webkit-transition-duration: 0.5s;
   -webkit-transition-timing-function:ease-in-out;
   -webkit-transition-delay: 1s;
   -moz-transition: height 0.5s ease-in-out 1s;
   -o-transition: height 0.5s ease-in-out 1s;
}

#menu:hover {
   height: 255px;
   overflow: hidden;
   -webkit-transition-property: height;
   -webkit-transition-duration: 0.5s;
   -webkit-transition-timing-function:ease-in-out;
   -webkit-transition-delay: 0s;

   -moz-transition: height 0.5s ease-in-out 0s;
   -o-transition: height 0.5s ease-in-out 0s;
}

#highlighted {
   background-color: #E099AC;
}

nav {
   border-radius: 10px;
   box-shadow: 2px 2px 6px rgba(20,20,20,0.3);
}
</pre>

### CSS Tag, ID (DIV, #teksty)

<pre>
#teksty {
   margin-left: 240px;
   margin-right: 100px;
   margin-top: -30px;	
   position: absolute;
   overflow: auto;
   height: 660px;
   width: 720px;
   top: 80px;
}

</pre>

### CSS Tag (FOOTER)

<pre>
footer  {
  font-size: 10px;
  float: left;	
  margin-top: 713px;
  margin-left: 100px;
}
</pre>

### CSS Class (A.MOUSE)

<pre>
a.mouse {
   background-image: url(../obrazki/mouse.png); 
   background-repeat: no-repeat;
   background-position: right;
}

</pre>

### CSS Tag (IMG, FIGCAPTION, FIGURE)

<pre>
img {
   float: right;
   margin: 15px;
   margin-top: 45px;
   margin-right: 25px;
   border-width: 10px;
   border-color: #313131;
   border-style: solid;	
   background: black;
   padding: 1px;
   border-radius: 10px;
   box-shadow: 2px 2px 6px rgba(20,20,20,0.3);
}

figure {
   float:right;
}

figcaption {
	font-family: 'Just Another Hand', Verdana;
	padding-left: 10px;
	font-size: 20px;
}

</pre>

### CSS Tag (OL, UL, LI)

<pre>
ol {
   font-weight: bolder;
}

ul {
   padding-bottom: 10px;		
}

li {
   font-size: 12px;
   padding-bottom: 5px;
}

</pre>

### CSS Tag (DL, DT, DD)
<pre>
dt {
   font-weight: bold;
   font-size: 14px;
   color: #1c3f28;
}
dd {
   font-size: 12px;
   padding-bottom: 15px;
}

</pre>

### CSS Tag, Pseudo-Class (A, :LINK, :VISITED, :FOCUSED, :HOVER)

<pre>
a:link  {
	color: #777;
}
a:visited {
	color: gray;
}

a:focus {
	color: black;
}

a:hover {
	color: white;
	text-decoration: none;
}

</pre>

### CSS Tag (TABLE, TH, TR, TD)

<pre>
table {
   border: 0px;  
   margin: 0px;
}

th {
  border: 0px;
  background: #e2b6c2;
  padding: 0.3em;    
}

td {
   font-size: 12px;
   line-height: 20px;
   margin-bottom: 30px;
   border: 0px;
   padding: 3px;
   vertical-align: top;
   background: rgba(255,255,255,0.1);
   box-shadow: 1px 1px 3px rgba(20,20,20,0.3);
   text-shadow: 1px 1px 3px rgba(10,10,10,0.5);

}
td li {
   margin-left: 15px;
}

</pre>

### CSS Tag (EM, Q, BLACKQUOTE)
<pre>
em q  {
   font-family: 'Just Another Hand', Verdana;
   font-family: ;
   font-size: 40px;
   color: #f8edf0;
}

blockquote {
  text-align: right;
  padding-right: 250px;
}

</pre>

### CSS Tag,Attribute (INPUT, TEXTAREA),(Type)
<pre>
input[type="text"], #text, input[type="date"] {
   opacity: 0.3;
   border: 1px solid #b76a7f;
   padding: 3px;
}

input[type="submit"] {
   opacity: 0.7;
   border: 1px solid #b76a7f;
}

textarea {
   border-radius: 10px;
}

input {
   border-radius: 5px;	
}

input, textarea {
   box-shadow: 1px 1px 3px rgba(20,20,20,0.3);
   text-shadow: 1px 1px 3px rgba(10,10,10,0.5);
}
</pre>

### CSS Tag (AUDIO)
### CSS Tag (VIDEO)
### CSS Cascade Background


## HTML5 dla poczatkujacych resources
[HTML5 Szkolenia NobleProg](https://www.nobleprog.pl/szkolenia-html)

[HTML5 website standard]([https://www.nobleprog.com/deepseek-training](https://html.spec.whatwg.org)



## HTML5 dla poczatkujacych resources
[HTML5 Szkolenia NobleProg](https://www.nobleprog.pl/szkolenia-html)

[HTML5 website standard]([https://www.nobleprog.com/deepseek-training](https://html.spec.whatwg.org)
