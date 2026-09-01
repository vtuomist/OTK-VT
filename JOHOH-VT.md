# Johdatus ohjelmointiin 

Kurssin tehtäviä, vastauksia ja kuvia. 
- Tehtävät ovat numeroitu siinä järjestyksessä kuin ne ovat Moodlessa.
- Ohjelmistona käytän $$\color{blue}{\text{VS codea}}$$.

<br><br>









<details>
  
<summary> Harjoitus 1 tulostus, matematiikka </summary>
  
<p>









<details>
  
<summary> Toteutus </summary>
  
<p>

Päätin tehdä koko harjoituksen 1-5 yhteen ohjelmaan. Tämä helpottaa arviointia ja auttaa minua oppimaan paremmin.

Tehtävässä ja alkuun pääsemisessä oli hyvin raskasta se, että VScode on pakattu täyteen automaattisia täyttö ja avustus ohjelmia, joista on oppimiseen lähinnä haittaa.
Sain nämä kuitenkin pienen työstön jälkeen poistettua käytöstä.

Tässä harjoituksessa ainoa asia mihin käytin tekoälyä oli Python sanaston luomiseen discord palvelimelle. Siitä oli paljon hyötyä.
Käytin myös Googlea apuna ohjelman luomiseen, sillä minulle tuli ongelma sellaisen loopin tekemisessä, joka kysyisi tehtävän jälkeen uudestaan "minkä harjoitus tehtävän haluat suorittaa?".
Tähän löysin vastauksen "while True:" eli silmukka käynnistyy kun koodi saapuu sen kohdalle ja ainut tapa poistua siitä on 0 eli "break"

<img width="855" height="466" alt="image" src="https://github.com/user-attachments/assets/4ecbcd4d-6024-48fe-bbbc-f25b181c8116" />

<br><br>

## Tässä koodi ##

def select_number():
    tehtävä = (1, 2, 3, 4, 5)  

    while True:    
                    
        valinta = int(input("Minkä harjoitustehtävän haluat suorittaa, 1, 2, 3, 4, 5? poistu 0: "))

        if valinta == 0:
            print("Poistuit.")
            break

        while valinta < 1 or valinta > 5:
            valinta = int(input("Valitse yksi tehtävänumero 1 ja 5 välillä. poistu 0: "))

        if valinta == 1:
                print("Hello world!")
                print("Veeti Tuomisto")
                print("2001")
                print("Lahti")
                                                
        elif valinta == 2:
                hinta = float(input("Anna tuotteen veroton hinta: "))
                print(f"hinta alv kanssa: {hinta * 1.24}")

        elif valinta == 3:
                matka = int(input("Matkan pituus?: "))
                kulutus = float(f"{matka / 100}")
                print(f"Polttoaineen kultus tälle matkalle: {kulutus * 6.5}")

        elif valinta == 4:
                aika = int(input("Anna minuutit: "))
                tunnit = aika // 60
                minuutit = aika % 60
                print(f"{tunnit}t {minuutit}min")

        elif valinta == 5:
                numero1 = int(input("Anna 1-1000000 senttiä: "))
                tulos1 = numero1 // 50
                jakojäännös1 = numero1 % 50
                print(f"50 snt kolikoita {tulos1} kpl")           #50snt

                numero2 = jakojäännös1
                tulos2 = numero2 // 20
                jakojäännös2 = numero2 % 20
                print(f"20 snt kolikoita {tulos2} kpl")           #20snt
                
                numero3 = jakojäännös2
                tulos3 = numero3 // 10
                jakojäännös3 = numero3 % 10
                print(f"10 snt kolikoita {tulos3} kpl")           #10snt
                
                numero4 = jakojäännös3
                tulos4 = numero4 // 5
                jakojäännös4 = numero4 % 5
                print(f"5 snt kolikoita {tulos4} kpl")             #5snt

                numero5 = jakojäännös4
                tulos5 = numero5 // 2
                jakojäännös5 = numero5 % 2
                print(f"2 snt kolikoita {tulos5} kpl")             #2snt

                numero6 = jakojäännös5
                tulos6 = numero6 // 1
                jakojäännös6 = numero6 % 1
                print(f"1 snt kolikoita {tulos6} kpl")             #1snt

select_number()
<br><br>

Tässä vielä screenshot koko hommasta.

<img width="882" height="1374" alt="image" src="https://github.com/user-attachments/assets/8e4eb864-403a-4406-b566-f51ed232ce33" />


</p>

</details>









<details>

<summary> 1. Hello, world! </summary>

<p>

<br><br>
Tehtävä 1 oli perus vanha kunnon print("Hello, world!").

<img width="585" height="322" alt="image" src="https://github.com/user-attachments/assets/0a361362-38d3-4bde-a0e4-32a10693f883" />

</p>

</details>









<details>

<summary> 2. Arvolisävero laskuri </summary>

<p>

Tehtävä 2 oli arvolisäverolaskuri. Tehtävässä käytin float(), jotta laskuri toimisi mahdollisimman tarkasti. 
Toinen mainittava on f" joka mahdollisti lyhyen siistin koodin, jossa print() toimii laskutoimituksena ja vastauksena.

<img width="645" height="235" alt="image" src="https://github.com/user-attachments/assets/53661900-cc6a-4ba3-84bd-701e0d302373" />

</p>

</details>


















</p>

</details>

<br><br>
