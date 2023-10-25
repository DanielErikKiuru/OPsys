#Praktikum 5

Selles praktikumis sain teada rohkem linuxi failiõiguste kohta. <br>

5.1<br> 
a) kataloogis /tmp/kaust oleva faili minufail.txt lugemiseks on vaja vähemalt r õigusi.<br>
b) kataloogis /tmp/kaust oleva faili minufail.txt kustutamiseks on vaja vähemalt x õigusi.<br>  

5.2 <br>
Shelli skriptifaili käivitamiseks on vaja veel lisaks read õigusi.<br>

5.3<br>
Igal kasutajal on omanimeline grupp turvalisuse jaoks. Et kasutajad saaksid jagada faili asukohti, nii et ühele oleks keelatud ja teisele lubatud.<br>

5.4<br>
![image](https://github.com/DanielErikKiuru/OPsys/assets/146202163/b03c2b62-a72e-4eee-b50c-80da1211ece1)<br>

5.5<br>
![image](https://github.com/DanielErikKiuru/OPsys/assets/146202163/7d7b9ec0-007e-4484-86b5-b25fb15ae7d0)<br>

5.6 <br>
Setuid võib vähendada turvalisust, kui programmi setuid on seotud root kasutajaga, siis saab programmi kasutaja kõik root õigused omale.<br>

5.7<br>
Peetri loodud faili saavad kustuda: opetaja, main kasutaja(daniel), jukuisa.<br>

5.8<br>
![image](https://github.com/DanielErikKiuru/OPsys/assets/146202163/52626635-d48d-460b-91f5-0cc059a4be93)<br>

5.9<br>
Chattr +i parameetriga faili ei saa keegi kustutada ega muuta. Faili saab kustutada niimoodi, et tuleb eemaldada +i väärtus selleks kasutada käsku (sudo chattr -i testfail-2).<br> 


