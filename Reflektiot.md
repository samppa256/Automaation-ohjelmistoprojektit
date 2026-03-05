1. Aggregaatio yhdistää RobotArmin, sekä AssemblyStationiin että MobileRobottiin. Jolloin siis luodaan uusi RobotArm aina kun luodaan uusi MobileRobot tai AssemblyStation. Kun meillä on 3 AssemblyStationia sekä 2 MobileRobottia, niin Cell solussa on yhteensä 5 RobotArmia
2.
a. MobileRobotilla on oma noodi, joka luodaan, kun luokka luodaan. Tapahtuu rivillä 27
b. MobileRobotin oma noodi, liitetään rootNodeen. Tapahtuu rivillä 263
c. Robottikädellä on oma noodinsa, jotka liitetään MobileRobotin noodin alle. Tapahtuu rivillä 241
d. Tasolla on laatikon muotoinen geometria, joka liitetään MobileRobot noodiin.Tapahtuu rivillä 262

Reflektio:

1. Miten UML luokkakaaviota käytetään seuraavissa tilanteissa:
\n**a. Ohjelmistoa suunniteltaessa**
  Selkeyttää kokonaiskuvan hahmottamista. Tässä vaiheessa    suunnitellaan sopivat luokat ja niiden väliset yhteydet
b. Suunnittelun jälkeen, kun koodaustyötä jaetaan tiimissä
c. Valmiin ohjelmiston dokumentointiin
d. Ylläpitovaiheessa, kun tehdään muutoksia yhteen luokkaan ja arvioidaan vaikutuksia muihin luokkiin, jotka käyttävät kyseistä luokkaa

3. Jos MobileRobot kyytiin laitetaan kappale, niin kuinka 3D pelimoottorin ominaisuuksia voidaan
hyödyntää niin, että kappale liikkuu MobileRobotin mukana?


4. Monella kurssilaisella on tietotekniikan sivuaine, mutta emme voi olettaa sellaista esitietoa.
Kurssi on pyritty suorittamaan niin, että kaikki pääsee etenemään omaan tahtiin. Mitä esitietoa
sinulla on ohjelmistojen suunnitteluun ja visuaaliseen mallintamiseen esimerkiksi UML:llä? 
 
