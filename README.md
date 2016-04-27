# Culturele Selectie van Sprookjes

In het hoorcollege van vandaag hebben we het gehad over de culturele selectie van sprookjes. Uit de gepresenteerde analyses bleek dat er aanwijzingen zijn om aan te nemen dat de culturele selectie van sprookjes onderhevig is aan een "personage bias" waarbij succesvolle verhalen de voorkeur geven aan bepaalde personagetypes. Het doel van dit werkcollege is om dit wat verder uit te werken.

In het hoorcollege hebben we enkel gekeken naar abstracte personagetypes, maar we hebben nog weinig gezegd over de *relaties* tussen de verschillende personages. Het doel van deze opdracht is om te onderzoeken of er verschillen te vinden zijn in de relaties tussen personages in succesvolle en onsuccesvolle verhalen. 

## Opdracht 1: Personage-extractie

De volgende twee lijsten bevatten 21 succesvolle en 21 onsuccesvolle verhalen:

Succesvol (N = 21): “The Frog King” (“Iron Henry”) (1), “Little Brother and Little Sister” (11), “Rapunzel” (12), “Hansel and Gretel” (15), “The Fisherman and his Wife” (19), “The Brave Little Tailor” (20), “Ashputtle” (“Cinderella”) (21), “Mother Holle” (24), “Little Red Cap” (“Little Red Riding Hood”) (26), “The Musicians of Bre- men” (27), “The Devil with the Three Golden Hairs” (29), “Brier Rose” (“Sleeping Beauty”) (50), “King Thrushbeard” (52), “Snow White” (53), “Rumpelstiltskin” (55), “Thousandfurs” (65), “Jorinde and Joringel” (69), “Hans in Luck” (83), “The Lilting, Leaping Lark” (“Beauty and the Beast”) (88), “The Goose Girl” (89), “Snow White and Rose Red” (161).

Onsuccesvol (N = 21): “A Good Stroke of Business” (7), “The Girl Without Hands” (31), “The Magic Table, The Gold Donkey, and the Cudgel in the Sack” (36), “The Knapsack, the Hat, and the Horn” (54), “Frederick and Liza-Kate” (59), “Farmer Little” (61), “Six Who Made Their Way in the World” (71), “The Carnation” (76), “Brother Scamp” (81), “The Golden Children” (85), “The King of the Golden Mountain” (92), “The Spirit in the Bottle” (99), “Bearskin” (101), “Hans My Hedgehog” (108), “The Jew in the Brambles” (110), “The Prince Who Feared Nothing” (121), “The Donkey Lettuce” (122), “Faithful Ferdinand and Faithless Ferdinand” (126), “Hefty Hans” (166), “The Poor Boy in the Grave” (185), “Maid Maleen” (198).

De Nederlandse versies van deze verhalen kun je vinden op de website http://www.beleven.org/verhalen/grimm/. De nummers tussen haakjes achter de titels corresponderen met de Nederlandse versies op deze website. Kies tenminste 2 verhalen. Lees de twee verhalen en noteer alle personages die erin voorkomen (als een personage met meerdere namen wordt aangeduid, moet je voor elk personage slechts één naam te noteren). 

## Opdracht 2: Relationeel Netwerk

Nu we de personages geëxtraheerd hebben, kunnen we proberen om de relaties tussen de personages te beschrijven. In deze opdracht zullen we de relaties tussen personages representeren als een netwerk. Zo'n netwerk heeft veel weg van een sociaal netwerk, zoals Facebook en Twitter. In het personagenetwerk vormen personages "knopen" en de relaties tussen personages kunnen opgevat worden als "links". In deze opdracht nemen we gemakshalve aan dat twee personages een relatie met elkaar aangaan als ze in dezelfde zin voorkomen. 

Maak een tabel waarin de kolommen en de rijen de personagenamen bevatten die je genoteerd hebt in opdracht 1. Noteer vervolgens in iedere cel of een bepaald personage met een ander personage in een zin in het verhaal voorkomt. (Een personage komt uiteraard altijd met zichzelf voor, maar die cel mag je leeglaten).

## Opdracht 3: Visualisatie

In de vorige opdracht hebben we een zogeheten "co-occurrence"-tabel gemaakt van personages in verhalen. Deze co-occurrence-tabellen kunnen we weergeven als een netwerk met behulp van netwerkvisualisatieprogramma's. Een goed programma om dat te doen is het programma Gephi. Dat kun je downloaden van https://gephi.org/. 

Voordat we dat co-occurrence-tabellen kunnen inladen in Gephi, moeten we ze eerst in een nèt iets ander formaat representeren. Maak een nieuwe tabel met twee kolommen waarvan de eerste "source" is genoemd en de ander "target". Loop alle rijen langs (of kolommen) in je co-occurrence-tabel en noteer als twee personages samen voorkomen in de eerste kolom de naam van het eerste personage en in de tweede kolom de naam van het tweede personage. De tabel moet er uiteindelijk ongeveer zo uitzien:

    source,target
    sneeuwwitje,dwerg
    sneeuwwitje,jager
    jager,heks
    heks,jager
    etc.

Sla dit bestand op als een CSV-bestand en open het met Gephi. Volg het tutorial op https://gephi.org/users/quick-start/ om een elegante visualisatie van het netwerk te maken.
