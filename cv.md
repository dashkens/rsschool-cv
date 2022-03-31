# ***My CV***

## Full name: 
Darja Jekateriničeva
## Contact Info: 
- **Address**: Vilnius, Lithuania
- **E-mail**: darjajek@icloud.com 
## Summary
Technologies and media were always holding a special place in my heart. I’ve started to use Adobe programs since I was 9. At the same age my dad presented me an old and used photocamera which allowed me to dive into the creative media world. After school my best friend showed me a world of programming, which scared me at first. But after some years I came back to it, because I love solving logical problems and finding solutions to them. But at the same time my creative side was demanding to express itself. That is why I’ve decided to try Web Development as this field holds both creative and logical aspects. Even though I have basic knowledge of Web Development I am ready for new challenges and experience. 

## Skills:
- Adobe Ps, XD, Pr, Id, Ai - intermediate
- HTML, CSS - intermediate
- JS, C#, Unity - beginner

## Code example 
_One of the problem I had to solve for my class - the old game from the childhood._

    <title>Žaidimas 15</title>
    <style>
        .game15{
           border: 10px inset blue;
           width: 296px; height: 296px;
           margin: auto;
        }
        .game15 div{
           border: 10px inset blue; 
           width: 50px; height:50px;
           float: left; margin: 2px;
           background: rgb(0,100,255);
           font: bold 36px Tahoma;
           text-align: center;
           color: black;
           text-shadow: 2px 2px 2px white;
        }

        .game15 div:hover{
            color:gold;
        }
        .MMM {
            margin-top: 50px;
        }
        </style>
        
    <script>
    function start() {
        for(var i = 1; i < 16; i++){
            document.getElementsByClassName('lang')[i-1].innerHTML = i;
        }
        //tikslas gauti <input type ="button" value="Sumaisyti">
        var M = document.createElement('input');
        M.setAttribute('type','button');
        M.setAttribute('value','Sumaisyti');
        M.setAttribute('id','MMM');
        document.getElementsByClassName('game15')[0].appendChild(M);
        document.getElementById('MMM').addEventListener('click', sumaisyk);
    }
    //--------------------------------
    function sumaisyk(){
        
    }
    </script>
    
</head>
<body onload="start()">

    </head>
    <body>
        <!-- div.game15>div.lang*16 -->
        <div class="game15">
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <div class="lang"></div>
            <!-- <div class="lang"></div> -->
        </div>
        
</body>

## Experience: 
Now it is my first semester where me and my classmates are delevoping real project, which I could present in the end of June. For now my experience is solving problems using JS, C# and creating simple websites using HTML and CSS. 
## Education: 
1. VILNIUS TECH, Vilnius, Lithuania. 
   - Degree: Communication in Entertainment Industries
   - 2016 - 2020.

2. Vilnius Business College, Vilnius, Lithuania
   - Degree: Computer Science
   - 2020 - Present.

## English: 
I've been learning English for 19 years. I've been participating in a student exchange program (twice) and have also completed an internship abroad. This summer I will be participating in Work&Travel USA program. Also, as there is not much relevant or scientific information in Lithianian language, I didn't have a choice but find this info in English. All this experience allows me to use and understand English on a high level.

