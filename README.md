# José sass -> css 

## Stáhnout tenhle zdroják

   git clone https://github.com/januhl/jose.git

## Zapnout:

Zavolej v adresáři kam sis to dal:

    docker-compose up -d

První spuštěné trvá dlouho, další bude rychlé.

## Vypnout:

Zavolej v adresáři kam sis to dal:

    docker-compose down

## Přihlášení se dovnitř do image

    docker-composer exec node bash

## Odhlášení se ven

    exit

## Při prvním spuštění uvnitř image nainstaluj potřebné balíčky (jen 1x)

    npm install

## Kompilace

   `npm run dev` - bez minifikace

   `npm run watch` - bez minifikace + pořád přepočítává dokud to nevypneš ctrl+c

   `npm run prod` - produkční - s minifikací
