1. Aggregaatio yhdistää RobotArmin, sekä AssemblyStationiin että MobileRobottiin. Jolloin siis luodaan uusi RobotArm aina kun luodaan uusi MobileRobot tai AssemblyStation. Kun meillä on 3 AssemblyStationia sekä 2 MobileRobottia, niin Cell solussa on yhteensä 5 RobotArmia
2.
a. MobileRobotilla on oma noodi, joka luodaan, kun luokka luodaan. Tapahtuu rivillä 27
b. MobileRobotin oma noodi, liitetään rootNodeen. Tapahtuu rivillä 263
c. Robottikädellä on oma noodinsa, jotka liitetään MobileRobotin noodin alle. Tapahtuu rivillä 241
d. Tasolla on laatikon muotoinen geometria, joka liitetään MobileRobot noodiin.Tapahtuu rivillä 262
