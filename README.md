# goit-js-hw-03

Zadanie 1. Generator slug

Napisz funkcję slugify(title), która przyjmuje tytuł artykułu, parametr title i zwraca slug utworzony z tego ciągu.

Wartością parametru title będą ciągi, których słowa są oddzielone tylko spacjami.
Wszystkie znaki slug muszą być pisane małymi literami.
Wszystkie słowa slug muszą być oddzielone myślnikami.


Weź poniższy kod i wstaw go po deklaracji swojej funkcji, aby sprawdzić, czy działa poprawnie. Konsola wyświetli wyniki jego działania.

console.log(slugify("Arrays for begginers")); // "arrays-for-begginers"

console.log(slugify("English for developer")); // "english-for-developer"

console.log(slugify("Ten secrets of JavaScript")); // "ten-secrets-of-javascript"

console.log(slugify("How to become a JUNIOR developer in TWO WEEKS")); // "how-to-become-a-junior-developer-in-two-weeks"



Zostaw ten kod do sprawdzenia swojemu mentorowi.

Na co będzie zwracał uwagę mentor podczas sprawdzania:

Zadeklarowano funkcję slugify(title);
Wywołanie slugify("Arrays for begginers") zwraca "arrays-for-begginers";

Wywołanie slugify("English for developer") zwraca "english-for-developer";

Wywołanie slugify("Ten secrets of JavaScript") zwraca "ten-secrets-of-javascript";

Wywołanie slugify("How to become a JUNIOR developer in TWO WEEKS") zwraca "how-to-become-a-junior-developer-in-two-weeks".


Zadanie 2. Kompozycja tablic



Napisz funkcję o nazwie makeArray, która przyjmuje trzy parametry: firstArray (tablica), secondArray (tablica) i maxLength (liczba). Funkcja musi utworzyć nową tablicę zawierającą wszystkie elementy z firstArray, a następnie wszystkie elementy z secondArray.



Jeśli liczba elementów w nowej tablicy przekracza maxLength, funkcja musi zwrócić kopię tablicy o długości elementów maxLength.
W przeciwnym razie funkcja powinna zwrócić całą nową tablicę.


Weź poniższy kod i wstaw go po deklaracji swojej funkcji, aby sprawdzić poprawność jej działania. Konsola wyświetli wyniki jego działania.

console.log(makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3)); // ["Mango", "Poly", "Ajax"]

console.log(makeArray(["Mango", "Poly", "Houston"], ["Ajax", "Chelsea"], 4)); // ["Mango", "Poly", "Houston", "Ajax"]

console.log(makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)); // ["Mango", "Ajax", "Chelsea"]

console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 2)); // ["Earth", "Jupiter"]

console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)); // ["Earth", "Jupiter", "Neptune", "Uranus"]

console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus", "Venus"], 0)); // []



Zostaw ten kod do sprawdzenia swojemu mentorowi.

Na co będzie zwracał uwagę mentor podczas sprawdzania:

Zadeklarowano funkcję makeArray(firstArray, secondArray, maxLength);

Wywołanie makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3) zwraca ["Mango", "Poly", "Ajax"];

Wywołanie makeArray(["Mango", "Poly", "Houston"], ["Ajax", "Chelsea"], 4) zwraca ["Mango", "Poly", "Houston", "Ajax"];

Wywołanie makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3) zwraca ["Mango", "Ajax", "Chelsea"];

Wywołanie makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 2) zwraca ["Earth", "Jupiter"];

Wywołanie makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4) zwraca ["Earth", "Jupiter", "Neptune", "Uranus"];

Wywołanie makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus", "Venus"], 0) zwraca [];

Wywołanie makeArray() z losowymi tablicami i losową liczbą zwraca poprawną tablicę.


Zadanie 3. Filtrowanie tablicy liczb



Napisz funkcję filterArray(numbers, value), która jako parametry przyjmuje tablicę liczb (numbers) i wartość (value). Funkcja powinna zwrócić nową tablicę zawierającą tylko te liczby z tablicy numbers, które są większe niż value.



Wewnątrz funkcji:

Utwórz pustą tablicę, do której będziesz dodawać pasujące liczby.
Użyj pętli do iteracji przez każdy element tablicy numbers.
Użyj warunkowej instrukcji if wewnątrz pętli, aby sprawdzić każdy element i dodać go do tablicy.
Zwróć nową tablicę z pasującymi liczbami jako wynik.


Weź poniższy kod i wstaw go po deklaracji funkcji, aby sprawdzić, czy działa poprawnie. Konsola wyświetli wyniki jego działania.



console.log(filterArray([1, 2, 3, 4, 5], 3)); // [4, 5]

console.log(filterArray([1, 2, 3, 4, 5], 4)); // [5]

console.log(filterArray([1, 2, 3, 4, 5], 5)); // []

console.log(filterArray([12, 24, 8, 41, 76], 38)); // [41, 76]

console.log(filterArray([12, 24, 8, 41, 76], 20)); // [24, 41, 76]




Zostaw ten kod do sprawdzenia swojemu mentorowi.

Na co będzie zwracał uwagę mentor podczas sprawdzania:

Zadeklarowano funkcję filterArray(numbers, value);
Wywołanie funkcji filterArray([1, 2, 3, 4, 5], 3) zwraca [4, 5];

Wywołanie funkcji filterArray([1, 2, 3, 4, 5], 4) zwraca [5];

Wywołanie funkcji filterArray([1, 2, 3, 4, 5], 5) zwraca [];

Wywołanie funkcji filterArray([12, 24, 8, 41, 76], 38) zwraca [41, 76];

Wywołanie funkcji filterArray([12, 24, 8, 41, 76], 20) zwraca [24, 41, 76];

Wywołanie funkcji filterArray() z losową tablicą i liczbą zwraca poprawną tablicę.
