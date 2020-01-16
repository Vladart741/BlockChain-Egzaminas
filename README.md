# BlockChain-Egzaminas

## Užduoties formuluotė
Naudodami Jums priimtiniausias programavimo priemones (pvz. python/django +python-bitcoinlib + Bitcoin Core) realizuokite stipriai supaprastintą Bitcoin tinklo Blockchain (blokų) explorer'į, kuris yra internetinė programa (angl. web application), veikianti kaip Bitcoin blockchain'o paieškos variklis (angl. Bitcoin search engine), leidžiantis "ištraukti" ir vizualiai pateikti Bitcoin blokchain tinklo informaciją pagal įvairius paieškos kriterijus, kaip kad blokų/transakcijų adresus (hash'us), bloko numerį ir pan.

## Realizacija
Programos kūrimui buvo naudojama ASP.Net  Blockchain API biblioteka. Programa leidžia atlikti paiešką blockchain'ę pagal šiuos kriterijus:

![image](https://user-images.githubusercontent.com/12825358/72510338-f14bbb00-3851-11ea-9f38-e508db77b407.png)

Taip pat kiekvienas paieškos kriterijus turi savo atitinkamą reikalavimą (pvz.: norint ieškoti transakciją pagal jos hash'ą, reikės į atitinkamą langą jį įvesti):

![image](https://user-images.githubusercontent.com/12825358/72510835-c9108c00-3852-11ea-93ee-cb3a89d3433d.png)

Gauti rezultatai, atliekant paiešką pagal, pavyzdžiui, trasakcijos hash'ą atrodo štai taip:

![image](https://user-images.githubusercontent.com/12825358/72510576-5dc6ba00-3852-11ea-85dc-d4a530331248.png)

Pasirenkant LatestBlock gaunamas paskutinis sugeneruotas blokas:

![image](https://user-images.githubusercontent.com/12825358/72511408-cbbfb100-3853-11ea-9210-e31851b015a8.png)

