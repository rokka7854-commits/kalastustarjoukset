# Kalakerhon tarjousvahti

Puhelimelle sopiva PWA kalastusvälineiden alennusten ja hintamuutosten seuraamiseen.

## Toiminnot

- tuoteryhmärajaukset vieheille, vavoille, keloille, siimoille ja elektroniikalle
- Happy Anglerin ja Ruodon julkisten tuotetietolähteiden tarjoushaku
- laitteen omaan selaintallennustilaan jäävä hintavertailu
- suorat kauppalinkit Motonetiin, Jigiparatiisiin, GoFishiin ja Sportfishtackleen

Sovellus näyttää vain hinnat, joille lähdekauppa ilmoittaa vertailu- tai normaalihinnan. Tiedot ovat suuntaa-antavia; saatavuus ja lopullinen hinta varmistetaan aina verkkokaupasta.

## Kehitys

Sovellus on Cloudflare Worker -pohjainen. Lähdekoodi on tiedostossa `worker/index.js`.

GitHub Pages on pelkkää staattista hostingia, joten tämän version automaattinen tuotehaku tarvitsee Worker-ajoympäristön. GitHub-repository sisältää lähdekoodin ja julkaisuhistorian.
