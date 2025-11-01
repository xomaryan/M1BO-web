# Stel je voor
Mijn gitHub-link van webpagina
## HTML
```code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anna-Maria</title>
    <link rel="stylesheet" href="stijl.css">
    <header>
       
        <h1>Stel je voor</h1>
       
    </header>

</head>
<body>
    <section>
    <nav>
     
        <article id="article1" class="article">
            
          
            <h2 class="articleHeader">Anna-Maria Borosovska</h2>
             <p class="articleText1">

                Mijn naam is Anna-Maria en ik ben 16 jaar oud. Ik ben geboren in Oekraïne, 
                maar woon nu in Nederland. Ik heb de volledige middelbare school afgerond 
                en nu volg ik een mbo-opleiding tot Software Developer.

            </p>
            
    <hr>
            <h2 class="articleHeader">Mijn Woonplaats</h2>
             <p>
                
                Dat is een bijzondere vraag, want ik heb eigenlijk twee plekken die ik als thuis zie: 
                één in Oekraïne en één in Nederland.
                Mijn eerste thuis is Oekraïne. 
                Ik ben geboren in de mooie stad Zhytomyr en heb daar twaalf jaar gewoond.
                Zhytomyr ligt in het westen van het land. 
                Daar ging ik naar school, volgde ik danslessen en zat ik op de muziekschool.   
                Mijn tweede thuis is Assendelft. Ik woon nu al drie jaar in Nederland, 
                en Assendelft begint echt als thuis te voelen. 
                Het ligt in de provincie Noord-Holland 
                en staat bekend om zijn lange dorpslint – een van de langste straten van Nederland.

            </p>
    
    <hr>
             
            <h2 class="articleHeader">In mijn vrije tijd... </tijd></h2>
             <p>
             
                Dansen is mijn grote passie. Ik dans al meer dan tien jaar en heb veel ervaring. 
                Mijn moeder nam me mee naar mijn eerste dansles toen ik vijf jaar oud was, 
                en sindsdien is dans een belangrijk deel van mijn leven. Ik ben zelfs kandidaat voor de titel
                <b> Master of Sport </b> in dans.

        
        <br>
                Toen ik acht was, kwam er een vrouw in mijn klas in Oekraïne die prachtig viool speelde. 
                Haar muziek raakte me diep en inspireerde me om zelf viool te leren. 
                Kort daarna begon ik op de muziekschool, 
                waar ik mijn opleiding als violist met heel goede resultaten heb afgerond.

            </p>
            
             <p>
        <br>    Ik hou van een actief en creatief levem, daarom 
                neem ik deel aan verschillende casings. Eén van 
                de castings die mij het meest is bijgebleven, was mijn 
                deelname aan de film <b>"Koning van de Zwervers"</b>. Mijn 
                muzikale opleiding en sportcarrière hebben mij enorm geholpen 
                bij dit project. Ik kijk vol verwachting uit naar de première 
                van deze film.
                <br>Naast dans en muziek geniet ik van mijn vrije tijd. Ik breng graag tijd door met vrienden,
                maak wandelingen met mijn ouders in het park, speel games, leer coderen en kijk films. 
                Deze momenten geven me rust en plezier naast mijn creatieve en sportieve activiteiten.

            </p>
           
    <hr>
           
            <h2>Wat kan ik al?</h2>
             <p>
             
                Ik ben gedisciplineerd en creatief. 
                Ik leer snel en kan nieuwe informatie goed en snel opnemen.
                Ook nieuwe onderwerpen of vaardigheden pak ik makkelijk op.
                Ik werk graag zelfstandig,
                maar ik functioneer ook goed in een team. 
                Ik heb ervaring met dans, muziek en coderen. 
                Wat ik begin, maak ik ook af.

            </p>
            
    <hr>
            
            <h3 class="articleHeader1"> Mijn top 10 games</h3>
             <p1>
                1. Het bordspel ‘Monopoly’<br>
                2. Schaken<br>
                3. Dwaas<br>
                4. Mobile Legends<br>
                5. PUBG mobile<br>
                6. Roblox<br>
                7. The Sims 4<br>
                8. Minecraft<br>
                9. Fortnite<br>
                10. Subway Surf<br>
             </p1>
    <hr>
<div class="gallery">
     <div class="gallery-item">
         <a target="_blank" href="paint.png">
         <img src="paint.png" alt="its,mee">
    </a>
        <div class="desc">Mijn eerste expositie</div>
    </div>
 

<div class="gallery-item">
        <a target="_blank" href="nature.png">
        <img src="nature.png" alt="nature" width="600" height="400">
    </a>
        <div class="desc">Nederlandse fauna</div>
</div>


<div class="gallery-item">
        <a target="_blank" href="actor.jpg">
        <img src="actor.jpg" alt="actor" width="600" height="400">
    </a>
        <div class="desc">"Koning van de Zwervers"</div>
</div>


<div class="gallery-item">
        <a target="_blank" href="dance.png">
        <img src="dance.png" alt="dance" width="600" height="400">
    </a>
        <div class="desc">Dans en sport</div>
</div>

            
</article>
</nav>
    </section>  
    </body>
    <script>
        const now = new Date();
        const hour = now.getHours();

        if (hour >= 12) {
            document.body.classList.add('dark');
        }
    </script>
</html>
```


## CSS
```code
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);
}

header {
  background-color: rgba(145, 228, 251, 0.529);
  text-align: center;
   border: 4px inset rgba(0,0,0,0.1);
   border-radius: 20px;
   font-size: xx-large;
   padding:50px;
   width: 60%;
   margin: 10px;
   margin: 0 auto;
}

article {
    border: 4px inset rgba(0,0,0,0.1);
    border-radius: 20px;
    padding: 30px;
    margin: 0 auto;
    font-size: 90%;
    background: #eee;
    width: 60%;
   text-align: left;
}

p::first-letter{
    color: black;
    font-size: x-large;
    }

div.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
}

div.gallery-item {
  margin: 5px;
  border: 1px solid #ccc;
  width: 190px;
}

div.gallery-item:hover {
  border: 1px solid #777;
}

div.gallery-item img {
  width: 100%;
  height: auto;
  padding: 0.1px;
}

div.gallery-item div.desc {
  padding: 0.1px;
  text-align: center;
  width: 100%;
  height: auto;
}
```
