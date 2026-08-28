# Ohjelmoinnin työkalut ja käyttäjäkokemus.

Kurssin tehtäviä, vastauksia ja kuvia. Tehtävät ovat numeroitu siinnä järjestyksessä kuin ne ovat Moodlessa. 
Ohjelmistona käytän $$\color{blue}{\text{VS codea}}$$.


<details>

<summary> # 1. Debuggaus tehtävä </summary>

<p>
  



<img width="747" height="522" alt="image" src="https://github.com/user-attachments/assets/9c8631dc-05eb-4313-84d9-3d598c96aca4" />

<br><br>
Tehtävässä tutustuttiin debug toimintoon "arvaa luku pelillä". Tehtävän tarkoituksena oli vastata kysymyksiin debug toiminnon perusteella.
<br><br>

<img width="1282" height="1439" alt="OTK T1 Debug" src="https://github.com/user-attachments/assets/85d5fa14-bda7-47ed-ba58-53f3114d7247" />

Tehtävässä kysyttiin:
- satunnaisesti arvottu numero:      1-10 välillä. Minulle se oli 4.
- yritysten määrä:                   2
- pelin päättävää ehtoa:             else, oikean numeron löydyttyä.
- Jokaisen kierroksen muuttuja:      Jokaisella kierroksella muuttuja oli satunnainen numero.

Tehtävässä oli lisäkysymyksiä:
- Arvottava luku oli 4 (vasen yläreuna), Luku olisi voinut olla välillä 1-10.
- Yritysten määrä oli 2 (vasen reuna), luku olisi suurempi jos olisi mennyt ekalla.
- Ensimmäisellä kierroksella toteutui elif koska lukuni oli liian suuri. Toisella kierroksella toteutui else, sillä luku oli     oikea. Jos olisin vastannut liian pienenellä luvulla if olisi toteutunut.
- Jos salainen luku olisi kiinteä, se ei olisi enään satunnainen ja pysyisi lukuna "7" joka kierroksella.
</p>
</details>









<details>

<summary> # 2. Harjoitus Debuggaus (tentti) teht 1 </summary>

 <p>
   
<br><br>

Ensimmäisessä tehtävässä oli lähdekoodi, jonka tarkoitus oli etsiä sanojen "cat", "elephant", "dog", "butterfly", "bird" joukosta pisin sana. Jostain syystä koodin pisti pisimmäksi sanaksi "elephant" vaikka "butterfly" on pidempi.

<img width="1268" height="1439" alt="image" src="https://github.com/user-attachments/assets/2503e91e-eaa4-463f-bb49-64b064145346" />

<br><br>

Huomasin että elephant on nimilistassa ennen butterflyta ja koodi vain valitsi listasta "pisimmäksi nimeksi" ensimmäisen nimen joka on pidempi kuin 5 kirjainta. Testasin tämän vaihtamalla butterflyn ja elephantin nimeä ja tarkkailemalla vasemman yläreunan longest word kohtaa.

<img width="2422" height="1439" alt="image" src="https://github.com/user-attachments/assets/a8910138-4a3c-4ba9-b0fd-5930e025e2e9" />

<br><br>

Ongelma oli selkeästi if 5 > max_length: kohdassa koodia ja sen korjattua longest word toimi moitteettomasti.

<img width="1285" height="1438" alt="OTK Debug tentti 1 k1" src="https://github.com/user-attachments/assets/04e2f223-fdd1-4f2b-9738-517cd369a8de" />

</p>

</details>











