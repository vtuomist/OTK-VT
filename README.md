# Ohjelmoinnin työkalut ja käyttäjäkokemus.

Kurssin tehtäviä, vastauksia ja kuvia. 
- Tehtävät ovat numeroitu siinä järjestyksessä kuin ne ovat Moodlessa.
- Moniosaiset tentit ovat merkattu (tentti) tagillä ja kysymykset ovat eritelty omiin osioihinsa tehtävinä.
- Ohjelmistona käytän $$\color{blue}{\text{VS codea}}$$.

<br><br>

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




<br><br>




<details>

<summary> # 2. Harjoitus Debuggaus (tentti) </summary>

<p>




<details>

<summary>  # Tehtävä 1 </summary>

<p>

# Word Length Bug


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









<details>

<summary>  # Tehtävä 2 </summary>

<p>

# SyntaxError


<br><br>

Koodista puuttu sulku. L14

<img width="568" height="416" alt="image" src="https://github.com/user-attachments/assets/bb9370a1-cf30-4754-86b3-65a316a307b8" />

<br><br>

Korjattuna.

<img width="1187" height="1439" alt="image" src="https://github.com/user-attachments/assets/e4cf8dd4-b577-43b3-883c-304993794efd" />

</p>

</details>









<details>

<summary>  # Tehtävä 3 </summary>

<p>

# IdentationError

<br><br>

Koodia ei oltu jäsennelty oikein. Asioita piti tabailla oikean järjestykseen.

<img width="1275" height="1439" alt="image" src="https://github.com/user-attachments/assets/a993d091-1ec7-4ffd-a05f-bb4c23764913" />

</p>

</details>









<details>

<summary>  # Tehtävä 4 </summary>

<p>

# NameError

<br><br>

Koodista puuttuu kirjain.

<img width="659" height="252" alt="image" src="https://github.com/user-attachments/assets/a3de83a8-3184-461c-9672-ddd1fbe6bb87" />

<br><br>

Lisäsin puuttuvan "e" kirjaimen ja koodi alkoi toimia.

<img width="1091" height="995" alt="image" src="https://github.com/user-attachments/assets/ea85ca50-20f0-4b34-925d-972c38b9b844" />

</p>

</details>









<details>

<summary>  # Tehtävä 5 </summary>

<p>

# TypeError

<br><br>

Koodi ei tiennyt mitkä numerot sen pitää laskea.

<img width="734" height="386" alt="image" src="https://github.com/user-attachments/assets/087e57c3-068b-4691-991b-c2543e64ff53" />

<br><br>

Kerroin koodille mitkä numerot laskea. (numbers[0], numbers[1], numbers[2])

<img width="797" height="818" alt="image" src="https://github.com/user-attachments/assets/e27b0828-cc23-4395-962f-12c29bef7f30" />

</p>

</details>









<details>

<summary>  # Tehtävä 6 </summary>

<p>

# LogicError

<br><br>

Koodissa ei ollut logic erroria vaan toimi kuten tarkoitettu.


<img width="753" height="826" alt="image" src="https://github.com/user-attachments/assets/8be7a907-287d-413e-bcc4-ff0d63325a37" />

</p>

</details>









<details>

<summary>  # Tehtävä 7 </summary>

<p>

# CalculatorError

<br><br>

Yhteen- ja kertolaskun vastaukset menevät väärinpäin, koska yhteen lasku pyytää kertomaan numerot ja sama toisinpäin.

<img width="1140" height="854" alt="image" src="https://github.com/user-attachments/assets/ec0743ca-cc97-4389-8028-337f4a549b61" />

<br><br>
Koodi on korjattu vaihtamalla add_numbers ja multiply_numbers oikeille paikoille.
<br><br>
<img width="897" height="876" alt="image" src="https://github.com/user-attachments/assets/dd94277a-956f-4b07-b05d-5e318797bbd3" />

</p>

</details>









<details>

<summary>  # Tehtävä 8 </summary>

<p>

# Grade checker bug

<br><br>

Tehtävässä tuli pelkkää F kaikilla paitsi 90% koska koodissa annettiin palautus arvoksi tasan 80% eikä suurempi kuin 80%.

<img width="260" height="228" alt="image" src="https://github.com/user-attachments/assets/9ca3ff28-dec3-431e-b957-68c3dd9c1924" />

<br><br>
Koodi lähti toimimaan kun merkit vaihdettiin.

<img width="1098" height="1079" alt="image" src="https://github.com/user-attachments/assets/d3f8226e-83c0-452e-b3e2-80be579ab655" />

</p>

</details>









<details>

<summary>  # Tehtävä 9 </summary>

<p>

# Number counter bug

<br><br>

Koodi antaa väärän vaustauksen 10: 6, koska koodin arvot ovat asetettu väärin. Koodi aloittaa lisää laskuihin yhden lisää "count = 1" ja laskee mukaan myös 10 koska "if num >= 10:"

<img width="707" height="739" alt="image" src="https://github.com/user-attachments/assets/cf07079d-45d6-4839-b3f0-9002ad3e3d14" />

<br><br>

Koodi on korjattu kun countin aloittaa nollasta ja 10 ei laske itseänsä mukaan.

<img width="718" height="710" alt="image" src="https://github.com/user-attachments/assets/a61880aa-c374-4a58-bba1-add8c31309b1" />

</p>

</details>




</p>

</details>
