# Oppimispäiväkirja: Paikallinen git

Olen ennenkin käyttänyt githubia omissa projekteissa ja myös koulu projekteissa, joten esimerkiksi itse alustojen käyttö tuntui luontevalta. En kuitenkaan muista mitään peruskomentoja ulkoa, niin niiden kanssa on vähän hakemista, mutta niiden käyttöä olenkin tullut opettelemaan. 

Lisäksi aiemmin olen enemmän vaan näpytellyt jotain sen sijaan että olen oikeasti ymmärtänyt mitä teen. Opin paljon haaroista. 

Minua auttoi oppimaan ja selvittämään esteet harjoitus ohjeita katsomalla ja tekoälyltä avun kysyminen tarvittaessa. 


## Osiossa käyttämäni Git-komennot

Harjoitus 2
| git init | aloitin uuden projektin  |
| git add | lisää tiedoston seuraavaan talletukseen esim hello.html |
| git commit -m " " | tallentaa muutokset kommentilla |
| git status | voi tarkastella muutoksia |
| git rm test.txt | poistin test.txt tiedoston |
| git mv -.txt -.txt | vaihtaa tiedoston nimen, hello.html -> index.html |


Harjoitus 3
| git log | tarkastelin aikaisempia talletuksia ja niiden tunnisteita  |
| git reset | peruutin seuraavaan talletukseen lisätyn tiedoston muutoksen |
| git restore | palautin tiedoston viimeisimpään tallennettuun versioon, eli peruutin muutokset |
| git revert tunniste | peruutin tekemäni talletuksen, eli poistin README.md tiedoston |

Harjoitus 4
| git status | näkee myös nykyisen haaran |
| git branch | näkee olemassa olevat haarat |
| git branch - | luo uuden haaran -> tyylit |
| git switch - | tällä pystyy vaihtamaan haaran |
| git merge -(haara jossa tehty muutoksia) | haarojen yhdistäminen |