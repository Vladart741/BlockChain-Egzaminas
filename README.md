# BlockChain-Egzaminas

## Užduoties formuluotė
Naudodami Jums priimtiniausias programavimo priemones (pvz. python/django +python-bitcoinlib + Bitcoin Core) realizuokite stipriai supaprastintą Bitcoin tinklo Blockchain (blokų) explorer'į, kuris yra internetinė programa (angl. web application), veikianti kaip Bitcoin blockchain'o paieškos variklis (angl. Bitcoin search engine), leidžiantis "ištraukti" ir vizualiai pateikti Bitcoin blokchain tinklo informaciją pagal įvairius paieškos kriterijus, kaip kad blokų/transakcijų adresus (hash'us), bloko numerį ir pan.

## Realizacija
Programos kūrimui buvo naudojama ASP.Net  Blockchain API biblioteka. Programa leidžia atlikti paiešką blockchain'ę pagal šiuos kriterijus:

![image](https://user-images.githubusercontent.com/12825358/72517261-bf3f5680-385b-11ea-9a14-df5fcd379599.png)

Taip pat kiekvienas paieškos kriterijus turi savo atitinkamą reikalavimą (pvz.: norint ieškoti transakciją pagal jos hash'ą, reikės į atitinkamą langą jį įvesti):

![image](https://user-images.githubusercontent.com/12825358/72517308-d54d1700-385b-11ea-8953-860f3ff9523a.png)

Gauti rezultatai, atliekant paiešką pagal, pavyzdžiui, trasakcijos hash'ą atrodo štai taip:

![image](https://user-images.githubusercontent.com/12825358/72517342-e8f87d80-385b-11ea-95c9-2abaf6220837.png)

Pasirenkant LatestBlock gaunamas paskutinis sugeneruotas blokas:

![image](https://user-images.githubusercontent.com/12825358/72517409-062d4c00-385c-11ea-8ade-99be0a62f75a.png)

