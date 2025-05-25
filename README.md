Syllabification_cro_v2.1.py (last update 25/05/2025)

Upute:
 - Txt datoteka koju želimo obraditi mora se nalaziti u istom direktoriju (folder) kao i datoteka syllabification_cro_v2.1.py
 - Pokrenite Syllabification_cro_v2.1.py i odaberite txt datoteku koju želite obraditi
 - Program obrađuje red po red teksta u odabranoj datoteci
 - Program će kreirati 6 novih txt datoteka i jednu Excel datoteku
 
Izlaz:
 _frek.txt je ispis izbrojanih unigrama, bigrama, trigrama, slogova i metaslogova (1=konsonant, 0=vokal)
 _metafrek.txt je udio pojedinih vrsta slogova u tekstu, sortiranih od najzastupljenije prema najmanje zastupljenoj
 _rez.txt je ispis pojedinih riječi s granicama sloga i korištenim pravilom za slogovanje
 _stat.txt je udio pojedinih slogova u tekstu, sortiranih od najzastupljenijeg prema najmanje zastupljenom
 _ubt.txt je txt verzija tablice koja sadrži podatke u omjerima n-grama, slogova, metaslogova i rime, te koeficijentu konsonantskih skupinama i slogotvornom R
 _ubt.xlsx je Excel verzija tablice koja sadrži podatke u omjerima n-grama, slogova, metaslogova i rime, te koeficijentu konsonantskih skupinama i slogotvornom R
 _ubtfrek.txt (trenutačno prazna datoteka)
 
Za detaljan opis podataka u Excel tablici, vidi:
Bakarić, Nikola; Nikolić, Davor
Dataset of stylistic features of Croatian folklore genres // Paremiology between tradition and innovation / Babič, Saša ; Jakop, Nataša ; Mrvič, Rok (ur.). 
Ljubljana: Research Center of the Slovenian Academy of Sciences and Arts, 2024. str. 63-71 . doi: https://doi.org/10.3986/9789610508861_04


Za citiranje ovog programa koristite:
Bakarić, Nikola ; Nikolić, Davor
Python syllabification script for Croatian, 2015. 1, 1. https://github.com/nbakaric/Croatian-syllabification
