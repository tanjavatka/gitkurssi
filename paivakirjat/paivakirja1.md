# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Tehtävissä oli vaikeaa ymmärtää ohjeet ja mitä kaikki sanat tarkoittikaan. Esim 'tallennetut tiedostot' -> mitkä ne nyt taas olikaan. Sekä se mitä tehtävässä nyt loppujen lopuksi haluttiin tehtävän. Joissain kohdissa olin myös liian nopea tallentamaan (commit) asioita niin joutui peruuttamaan tekemisiään. :D

Toiseksi haarojen ja git tilojen hahmotus vei aikaa. Onneksi kuvat auttoivat hahmottamaan ja kun luki useamman kerran teoriaa ja ohjeita niin alkoi ymmärtämään. 

Lisäksi kyselin chatGPT:ltä, että selittää joitain komentoja tai lyhenteitä esim -c mistä se tulee. Ja jos halusin päästä cmd:stä suoraan johonkin, esim nettisivun avaaminen eli sen index.html tiedoston avaaminen suoraan komentotulkista, ettei tarvinnut mennä GUI kansioon/hakemistoon avaamaan sitä.

Kaikki harjoitukset auttoivat oppimaan ja kuvat.
Lisäksi tämän päiväkirjan avaus ei olisi onnistunut ilman muiden oppilaiden kyselyjä ja opettajan ohjeita teams -alustalla.

Helpointi oli add ja commit komennot koska niitä olin jo käyttänyt. Mutta aikalailla kaikki muu oli uutta.

Lisäsin taulukkoon muitakin komentoja kuin pelkästään git komentoja.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| ------- | ------ |
| status | tarkistaa onko git hakemistossa uusia tai tallentamattomia tiedostoja|
| add | lisää joko yhden tiedoston (add testi.txt) tai kaikki tiedostot (add .) valmiiksi tallennusta varten|
| commit | tallentaa uudet tiedostot stage tilasta tallennettuihin tiedostoihin paikallisesti. -m lisää vielä tietyn kommentin tallennukseen |
| switch | vaihtaa haaraa (branch) -c parametri luo samalla uuden haaran |
| clone | kloonaa etärepositorista tiedoston / ohjelman / hakemiston |
| log | näyttää edelliset tallennus toiminnan. Parametrina voi määrittää kuinka monta edellistä tallennusta haluaa nähdä (log -2) |
| reset | poistaa tallennus jonosta kaikki tallentamattomat eli kaiken mitä add on lisännyt "odotus tilaan". Parametrina voi poistaa vain tietyn lisäyksen / tiedoston |
| config | voidaan määritellä alku asetuksia git paikalliseen repositoriin |
| branch | näyttää mikä haara on käytössä / työn alla |
| rm | poistaa tiedoston / hakemiston |
| mv | siirtää tiedoston / hakemiston paikkaa tai nimeää uudelleen |
| revert | poistaa jo tallennetun tiedoston / hakemiston |
| mkdir | luo uuden hakemiston |
| open | avaa tiedoston, ohjelman, kansion. (open index.html) |
| ls | listaa hakemiston sisällön. -l listaa kaikki tiedot. -a näyttää myös piillotetut |
| touch | luo uuden tyhjän tiedoston |
| cat | näyttää mitä tiedosto pitää sisällään |