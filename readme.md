
## Git Muistiinpanot/ohjeet

**Peruskomennot**:  
- git status
> Käytetään projektin nykytilanteen tarkistamiseen.
- git add
> Tätä käyttämällä kerrotaan Git:ille että sen pitää huomioida se kyseinen tiedosto ja siihen tehdyt muutokset.
- git commit
> Tällä komennolla niin sanotusti tallennetaan tehdyt muutokset, tämä myös tallentaa ajan ja sen käyttäjän kuka teki kyseisen tallennuksen. Tallenusviesti vaaditaan ennen kuin komento voidaan suorittaa kokonaan.
> > Tallennusviestin tekemiseen kirjoitetaan -m "viesti" komennon jälkeen.
- git clone
> Komentoa käytetään repositorin cloonaamiseen omalle työpöydälle, ja se samalla luo niin sanotun linkin niiden välille että tietoa niiden välillä voi siirtää sujuvasti.
- git push
> Komennolla siirretään tehdyt muutokset GitHubissa tallennettuun repositoriin tyyöpöydällä olevasta versiosta
- git pull
> Komennolla otetaan tehdyt muutokset GitHubissa tallennetusta repositorista työpöydällä olevaan versioon
- git log
> Tällä tarkistetaan edelliset commitit
> > Lisää --oneline komennon perään saadaksesi tiivistetyn version

___

**Paikallisen repositorin luominen**

Paikallisen repositorin luomiseen käytetään komentoa *git init*, siihen voi myös lisätä omat käyttäjätiedot *git config user.name* komennolla ja sähköposti lisätään *git config --global user.email "sähköposti tähän"*
