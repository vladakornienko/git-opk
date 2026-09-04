# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Koska teen tämän kurssin nyt toisen kerran, tämän osion asiast olivat minulle jo aika tuttuja. Edellisestä kerrasta on kutenkin kulunut jonkin aikaa, joten olin unohtanut monia Git-komentoja ja sitä, mitä missäkin vaiheessa piti tehdä. Kun aloitin tehtävät uudestaan, osa asioista palautui mieleen melko nopeasti, mutta joitakin asioita piti katsoa ohjeista. Viime kerrasta jäi hyvin mieleen komennot: add, status, commit, switch, tag sekä haaran vaihtaminen.

Tehtävissä ei ollut tällä kertaa mitään täysin uutta, mutta välillä jouduin miettimään esimerkiksi sitä, mikä komento piti tehdä seuraavaksi. Aluksi myös eri komentojen tarkoitukset menivät vähän sekaisin. Kun tein tehtäviä vaihe vaihe vaiheelta, niiden käyttö alkoi taas tuntua tutummalta.

Minua auttoi eniten se, että pystyin kokeilemaan komentoja itse ja katsomaan, mitä niiden jälkeen tapahtui. Käytin paljon git-status-komentoa, koska sen avulla oli helppo tarkistaa, missä vaiheessa olin.

Huomasin myös, että vaikka olin tehnyt nämä asiat jo aikasemmin, kaikkea ei voi muistaa pitkän tauon jälkeen. Toisaalta nyt tehtäviä tehdessä monet asiat tuntuivat tutuilta, joten niiden palauttaminen mieleen oli helpompaa kuin ensimmäisellä kerralla. Tämän osion jälkeen Gitin peruskomennot ovat taas paremmin mielessä. Toivottovasti tällä kertaa onnistun suorittamaan tämän kurssin paremmin.

## Osiossa käyttämäni Git-komennot
 
| git status | Näyttää repositorion tilanteen ja kertoo mitä tiedostoissa on muuttunut. |
| git add . | Lisää muuttuneet tiedostot seuraavaa committia varten. |
| git commit -m "..." | Tallentaa tehdyt muutokset Gitin historiaan. |
| git log | Näyttää repositorion aikasemmat commitit. |
| git branch | Näyttää repositorion haarat. |
| git push | Lähettää paikalliset commitit GitHubiin. |
| git revert | Tekee uuden commitin, joka kumoaa aikasemman commitin muutokset. |
| git switch | Vaihtaa toiseen haaraan. |
| git merge | Yhdistää yhden haaran muutokset toiseen haaraan. |
| git merge --no-ff | Yhdistää haarat niin, että Git tekee aina erillisen merge-commitin. |