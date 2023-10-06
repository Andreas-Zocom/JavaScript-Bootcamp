# JavaScript-Bootcamp
Array, functions, if -else, switch case, Loop, DOM manipulation

## Lets get together

1. skapa en enkel webbsida som visar en lista över tal från 1 till 10, men bara de udda talen ska visas i fet stil. index.html kan se ut så här.  
```javascript
<!DOCTYPE html>
<html>
<head>
    <title>Övning</title>
</head>
<body>
    <ul id="numberList">
    </ul>
    <script src="script.js"></script>
</body>
</html>
``` 

1b. Skapa en enkel webbsida som visar en lista över namn från en array. Du vill också markera namnen som börjar med bokstaven "A" i fet stil. 

```javascript
const names = ["Alice", "Bob", "Charlie", "Anna", "David", "Eve"];
```

3. Skapa en enkel webbsida som visar en lista över namn från en array.
Men först efter att du har tryckt på en knapp(button). index.html och listan kan se ut så här.

```javascript
const names = ["Amelia", "Arne", "Kalle", "Ebba", "David", "Eve", "Jacob"];
```
```javascript
<!DOCTYPE html>
<html>
<head>
    <title>Övning</title>
</head>
<body>
    <button id="listArrayButton">Click me</button>
    <ul id="numberList">
    </ul>
    <script src="script.js"></script>
</body>
</html>
``` 



4. skapa en lista över städer och använd sedan JavaScript för att rendera listan i en HTML-tabell. index.html kan se ut så här.

```javascript
<!DOCTYPE html>
<html>
<head>
    <title>Städer</title>
</head>
<body>
    <h1>Lista över städer</h1>
    <table id="cityTable">
        <thead>
            <tr>
                <th>Stad</th>
            </tr>
        </thead>
        <tbody>
        </tbody>
    </table>
    <script src="script.js"></script>
</body>
</html>
``` 
Array med städer

```javascript
const cities = ["Stockholm", "Göteborg", "Malmö", "Uppsala", "Lund"];
```
5. Skapa en sida med en enkel meny där användaren kan ändra bakgrundsfärg
baserat på användarens val. index.html kan se ut så här.

```javascript
<!DOCTYPE html>
<html>
<head>
    <title>Bakgrundsfärgändring</title>
</head>
<body>
    <h1>Välj en bakgrundsfärg:</h1>
    <ul>
        <li><button id="redButton">Röd</button></li>
        <li><button id="blueButton">Blå</button></li>
        <li><button id="greenButton">Grön</button></li>
        <li><button id="greenButton">Gul</button></li>
        <li><button id="greenButton">Beige</button></li>
    </ul>
    <script src="script.js"></script>
</body>
</html>
``` 

6. skapa en Kalkylator med grundläggande operationer
   index.html kan se ut så här.

```javascript
<!DOCTYPE html>
<html>
<head>
    <title>Kalkylator</title>
</head>
<body>
    <h1>Grundläggande kalkylator</h1>
    <input type="number" id="num1" placeholder="Tal 1">
    <input type="number" id="num2" placeholder="Tal 2">
    <select id="operator">
        <option value="add">+</option>
        <option value="subtract">-</option>
        <option value="multiply">*</option>
        <option value="divide">/</option>
    </select>
    <button id="calculateButton">Beräkna</button>
    <p>Resultat: <span id="result"></span></p>
    <script src="script.js"></script>
</body>
</html>

``` 

7. Visa veckodag efter att användaren angett ett nummer och tryckt på knappen Visa veckodag. index.html kan se ut så här.

```javascript
<!DOCTYPE html>
<html>
<head>
    <title>Veckodagar</title>
</head>
<body>
    <h1>Veckodagar</h1>
    <label for="day">Ange ett nummer (1-7): </label>
    <input type="number" id="day">
    <button id="showDayButton">Visa veckodag</button>
    <p>Veckodag: <span id="weekday"></span></p>
    <script src="script.js"></script>
</body>
</html>

``` 
