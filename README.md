# ZaczepkiFacebook
Skrypt do automatycznego odpowiadania na zaczepki (dziala na kompie)

# Jak uzywac:

Wejdz na facebook.com/pokes

Nastepnie kliknij ppm i kliknij "Zbadaj element"
![Zbadaj element](https://imgur.com/a/2uXeVw6)
Wklej ten kod do zakladki "Console" (Konsola)
![Wklej do konsoli](https://imgur.com/a/BmoGWKp)
```js
function zaczep(){try{let odz = document.querySelector("div[aria-label='Odpowiedz na zaczepkę']");if (odz.ariaLabel == "Odpowiedz na zaczepkę") {odz.click();console.log("Zaczepilem wlasnie osobe!");}else{console.log("To nie jest zaczepka!");}}catch(e){console.log("Nie znalazlem osoby do zaczepienia \n\n\n ZIGNORUJ TO DLA DEVELOPERA - Error occured > " + e);}}let run = setInterval(zaczep, 10000);
```

i kliknij ENTER

I ciesz sie automatycznymi zaczepkami

By zatrzymac skrypt nalezy odswiezyc karte 

Skrypt dziala w tle co oznacza ze majac odpalna karte na przegladarce mozna robic wszelkie inne czynnosci na komputerze 
