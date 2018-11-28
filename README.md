# formulier
Formulier pro1
http://26408.hosts2.ma-cloud.nl/bewijzenmap/periode1.2/pro1/formulieren/
<!DOCTYPE html>
<html lang="nl">
  <head>
    <title> POP </title>
    <meta charset="utf-8">
    <meta name="description" content="formulier">
    <meta name="keywords" content="formulier">
    <meta name="author" content="Twan Lases">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <form action="http://bla.hosts.ma-cloud.nl/pop.php" method="get">
    <h1> Een plan voor jouw ontwikkeling</h1>
    Om een eerste stap te zetten naar een persoonlijk opleidingplan zul je eerst een paar vragen voor jezelf moeten beantoorden. Dit formulier helpt jou daar bij.
    <br>
    Naam:  <input type="text" placeholder="Bv. Jan Jansen" required autofocus>
    <select name="class" id="class" required>
      <option value="">Selecteer jouw klas</option>
      <option value="class">MG1A</option>
      <option value="class">MG1B</option>
      <option value="class">MG1C</option>
      <option value="class">MG1D</option>
    </select>
    <br>
    <fieldset>
      <legend>Welbevinden</legend>
        Hoe positief ben je over de opleiding?
        <br>
        <br>
        <input type="radio" name="cijfer" value="1">1
        <input type="radio" name="cijfer" value="2">2
        <input type="radio" name="cijfer" value="3">3
        <input type="radio" name="cijfer" value="4">4
        <input type="radio" name="cijfer" value="5">5
        <input type="radio" name="cijfer" value="6">6
        <input type="radio" name="cijfer" value="7">7
        <input type="radio" name="cijfer" value="8">8
        <input type="radio" name="cijfer" value="9">9
        <input type="radio" name="cijfer" value="10">10
        <br>
        Hoe gemotiveerd ben je momenteel om de opleiding af te maken?
        <br>
        <br>
        <input type="radio" name="motivatie" value="1">1
        <input type="radio" name="motivatie" value="2">2
        <input type="radio" name="motivatie" value="3">3
        <input type="radio" name="motivatie" value="4">4
        <input type="radio" name="motivatie" value="5">5
        <input type="radio" name="motivatie" value="6">6
        <input type="radio" name="motivatie" value="7">7
        <input type="radio" name="motivatie" value="8">8
        <input type="radio" name="motivatie" value="9">9
        <input type="radio" name="motivatie" value="10">10
        <br>
        Hoe veel vertrouwen heb je momenteel in je eigen kunnen>
        <br>
        <br>
        <input type="radio" name="vertrouwen" value="1">1
        <input type="radio" name="vertrouwen" value="2">2
        <input type="radio" name="vertrouwen" value="3">3
        <input type="radio" name="vertrouwen" value="4">4
        <input type="radio" name="vertrouwen" value="5">5
        <input type="radio" name="vertrouwen" value="6">6
        <input type="radio" name="vertrouwen" value="7">7
        <input type="radio" name="vertrouwen" value="8">8
        <input type="radio" name="vertrouwen" value="9">9
        <input type="radio" name="vertrouwen" value="10">10
    </fieldset>
    <br>
    <fieldset>
      <legend>sterke kanten</legend>
      Wat zijn jouw sterke kanten?
      <br>
      <br>
      <input type="checkbox" name="sterke" value="Coderen in HTML/CSS">Coderen in HTML/CSS
      <input type="checkbox" name="sterke" value="Programmeren in Java">Programmeren in Java
      <input type="checkbox" name="sterke" value="Scripting: programmeren in JavaScript">Scripting: programmeren in JavaScript
      <input type="checkbox" name="sterke" value="Plannen">Plannen
      <input type="checkbox" name="sterke" value="Samen werken">Samen werken
    </fieldset>
    <br>
    <fieldset>
      <legend>Nog te ontwikkelen</legend>
      Aan welke skills moet je nog extra aandacht besteden?
      <br>
      <br>
      <input type="checkbox" name="Skillz" value="Skillz">Coderen in HTML/CSS
      <input type="checkbox" name="Skillz" value="Skillz">Programmeren in Java
      <input type="checkbox" name="Skillz" value="Skillz">Scripting: programmeren in JavaScript
      <input type="checkbox" name="Skillz" value="Skillz">Plannen
      <input type="checkbox" name="Skillz" value="Skillz">Samen werken
    </fieldset>
    Met welke lessen heb je nog moeiten?
    <br>
    <br>
    <textarea rows="4" cols="50" id="textArea" placeholder="plaats hier Opmerkingen"></textarea>
    <br>
    <br>
    Welke lessen gaan goed?
    <br>
    <br>
    <textarea rows="4" cols="50" id="textArea" placeholder="plaats hier Opmerkingen"></textarea>
    <br>
    <br>
    Opmerkingen?
    <br>
    <br>
    <textarea rows="4" cols="50" id="textArea" placeholder="plaats hier Opmerkingen"></textarea>

    <input id="send" type="submit" value="verstuur"/>
    </form>
    <footer>
      <a href="http://validator.w3.org/check?uri=referer" target="_blank">
      <img src="http://blog.boyet.com/blog/files/media/image/valid-html5-blue.png" alt="Valide HTML5"></a>
      <a href="http://jigsaw.w3.org/css-validator/check/referer" target="_blank">
      <img src="http://jigsaw.w3.org/css-validator/images/vcss-blue.gif" alt="Valide CSS"></a>
    </footer>
  </body>
</html>
