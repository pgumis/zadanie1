# zadanie1

1. (max. 10%)
Proszę napisać program serwera (dowolny język programowania), który realizować będzie następującą funkcjonalność:
a. po uruchomieniu kontenera, serwer pozostawia w logach informację o dacie uruchomienia, imieniu i nazwisku autora serwera (imię i nazwisko studenta) oraz porcie
TCP, na którym serwer nasłuchuje na zgłoszenia klienta.
b. na podstawie adresu IP klienta łączącego się z serwerem, w przeglądarce powinna zostać wyświetlona strona informująca o adresie IP klienta i na podstawie tego adresu IP, o dacie i godzinie w jego strefie czasowej. 

ODPOWIEDŹ: plik index.html

![image](https://user-images.githubusercontent.com/2741563/174152389-5a509824-98e3-4c8b-9b2f-9c39b2578806.png)

2. (max. 50%)
Opracować plik Dockerfile, który pozwoli na zbudowanie obrazu kontenera realizującego funkcjonalność opisaną w punkcie 1. Przy ocenie brane będzie sposób opracowania tego pliku (dobór obrazu bazowego, wieloetapowe budowanie obrazu, ewentualne wykorzystanie warstwy scratch, optymalizacja pod kątem funkcjonowania cache-a w procesie budowania). Dockerfile powinien również zawierać informację o autorze tego pliku (ponownie imię i nazwisko studenta). 

ODPOWIEDŹ: plik Dockerfile

![image](https://user-images.githubusercontent.com/27415763/174152953-a78ff57a-e599-4ecf-bd3b-a002ec346260.png)

3. (max. 20%)
Należy podać polecenia niezbędne do:
a. zbudowania opracowanego obrazu kontenera,
b. uruchomienia kontenera na podstawie zbudowanego obrazu,
c. sposobu uzyskania informacji, które wygenerował serwer w trakcie uruchamiana kontenera (patrz: punkt 1a),
d. sprawdzenia, ile warstw posiada zbudowany obraz.

ODPOWIEDŹ: 
a)
![image](https://user-images.githubusercontent.com/27415763/174153501-d4644e91-daf5-40f0-a765-f069becf3b08.png)

b) 
![image](https://user-images.githubusercontent.com/27415763/174153480-4585ebe0-d177-4024-bf92-434d49b7743d.png)

c)
![image](https://user-images.githubusercontent.com/27415763/174154238-9edf0d16-1fc6-4d7d-ae26-5d7dc23ffb41.png)

d)
![image](https://user-images.githubusercontent.com/27415763/174154892-0a9653ed-40b8-4624-a97a-445c29f84754.png)
![image](https://user-images.githubusercontent.com/27415763/174154951-e60d3a1a-246a-42b7-980c-39f58c0c432d.png)

4. (max. 20%)
Zbudować obrazy kontenera z aplikacją opracowaną w punkcie nr 1, które będą pracował na
architekturach: linux/arm/v7, linux/arm64/v8 oraz linux/amd64. Obrazy te należy przesłać do
swojego repozytorium na DockerHub. W sprawozdaniu należy podać wykorzystane instrukcje wraz
z wynikiem ich działania I ewentualnymi komentarzami.
![image](https://user-images.githubusercontent.com/27415763/174156005-88dff7b9-1fc0-4145-a2df-2953a6ff0e5b.png)
![image](https://user-images.githubusercontent.com/27415763/174155970-13db0b41-ff67-4841-a3b7-bc0d215021d2.png)

UWAGA: (+10%) Wszystkie informacje, które trzeba dostarczyć w sprawozdaniu (punkty 1-4)
można opracować w postaci pliku zadanie1.md a ten plik umieścić na koncie GitHub jako
zwyczajowy opis zawartości repozytorium git. Na tym repozytorium proszę umieścić też
opracowane źródła dla serwera oraz przygotowany plik Dockerfile (oraz wszystkie inne, niezbędne
Państwa zdaniem pliki). W takim wypadku, jako sprawozdanie można przekazać wyłącznie plik
tekstowy zawierający linki do użytego repozytorium na GitHub oraz DockerHub .
