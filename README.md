# git-oppimispaivakirja

Kurssin nimi: Git-versionhallinta
Toteutuskoodi: SOF013AS2A-3002
Tekijän nimi: Malisha Meriläinen

Tässä repositoriossa on oppimispäiväkirjatehtävät 1-3. 


# Oppimispäiväkirja: Paikallinen git (2-4)

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



# Oppimispäiväkirja: Hajautettu git (5)

## Osiossa käyttämäni Git-komennot

Harjoitus 5
| git remote add origin - | määrittelin etärepositorion  |
| git remote -v | etärepositorio asetusten tarkistus |
| git push -u origin master | tietojen vienti etärepositorioon (github) |
| git fetch | hakee muutoksia, mutta ei yhdistä |
| git merge origin/master | yhdistää muutokset etärepositoriosta paikalliseen |# Oppimispäiväkirja: Hajautettu git



# Oppimispäiväkirja: Hajautettu git (6-7)

## Osiossa käyttämäni Git-komennot

Harjoitus 6
| git pull origin develop | toin etärepositorion muutokset paikalliseen tiedostoon |
| git push origin develop | vein etärepositorioon muutokset |

Harjoitus 7
| git switch -c - | tekee ominaisuushaaran |
| git push -u origin - | vie ominaisuushaaran etärepositorioon |
| git branch -d  - | poistaa haaran paikallisesti |