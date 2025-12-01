# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

En ymmärtänyt ihan täysin 100% kaikkea tästä kappaleesta / osiosta.
Pinnallisesti joo mutta ihan ei vielä loksahtanut syvälle tietosuuteen mitä kaikkea tapahtuukaan "konepellin alla".
Tai sitten täytyy odottaa, että tieto syventyy itselläni ja ehkä seuraavana päivänä ne onkin selkeämpiä jo.
Samalla tuli myös paljon selkiyttä push, clone komentoihin, joita olen käyttänyt aikaisemmin tietämättä mitään muuta kuin että toisella haetaan projekti ja toisella viedään projekti githubiin.

Omituisimmat komennot tässä osiossa oli checkout (tuli jo aikaisemmassakin mutta enemmän kokeilin tässä osiossa) 
ja fetch/merge/pull yhdistelmä tai eroavaisuudet.
ChatGPT sanoi checkoutin olevan vanha komento, josta ollaan siirrytty switch ja restore komentoihin. Pitääköhän tämä paikkaansa? :/

Minua auttoi oppimaan kaikki harjoitukset, kuvat ja chatGPT.
Päiväkirja 2 piti taas etsiä tai en meinannut ensin päästä vaihtamaan haaraa. Komentotulkki kuitenkin ohjeisti ja toivottavasti ymmärsin ohjeet oikein. Mutta tallensin paivakirja1.md -tiedoston ensin paivakirja1 haaraan ja sitten pääsin vaihtamaan haaraa paivakirja2:een.



## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| clone | tuo etärepositorista paikalliseen repositorioon kaikki päivitykset |
| push | vie paikallisesta repositoriosta etärepositorioon kaikki päivityset |
| fetch | tuo etärepositoriosta halutun projektin / hakemiston, mutta ei yhdistä sitä suoraan paikalliseen repositorioon vaan tekee siitä erillisen repositorion (?) |
| merge | yhdistää kaksi haluttua repositorio yhteen |
| pull | fetch ja merge yhdistettynä |
| checkout | vaihtaa repositoria ja myös palaa esim tiedoston muutos päivityksissä taaksepäin. |
| switch | vaihtaa haaraa |
| cd | vaihtaa hakemistoa = 'change directory' |
| remote | listaa etärepositorit. -v parametrilla saa enemmän tietoa |
| branch | listaa kaikki käytettävissä olevat haarat siitä hakemistossa / repositoriossa |
| status | näyttää tallentamattomat tiedostot / hakemistot |