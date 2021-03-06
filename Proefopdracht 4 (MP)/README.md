# Proefopdracht 4 multiplayer pong game

De proefopdracht is gekozen uit een tiental proefopdrachten en bestaat uit het maken van een multiplayer Pong game in de Unity 5 ontwikkelomgeving.
</br>
</br>
Het verwachte resultaat luid als volgt: 'een PC unity build van een simpele multiplayer Pong game, waarbij je tegen een menselijke  tegenstander kunt spelen die op een andere computer speelt. Op de server moet de input van beide  spelers gesynchroniseerd worden zodat de latency minimaal is.'

## Kenmerken

- [NetworkManager](https://docs.unity3d.com/ScriptReference/Networking.NetworkManager.html)
- [Multiplayer and Networking](https://docs.unity3d.com/Manual/UNet.html)
- [NetworkTransport](https://docs.unity3d.com/ScriptReference/Networking.NetworkTransport.html)

## Software anaylse

Voor deze proefopdracht hoeft er geen software analyse gemaakt te worden voor de verschillen tussen ontwikkelomgevingen, maar moet er onderzoek gedaan worden naar de mogelijkheden in
de opdracht besloten ontwikkelomgeving, Unity 5.

Zoals gezegd ik de besloten ontwikkelomgeving Unity 5 en zullen we eerst kijken naar de mogelijkheden van een pong spel.
Het maken van een pong spel is op het eerste oog erg makkelijk.
De kennis en eventuele nodige tutorials schikken er, ook is er ervaring aanwezig met de Unity 5 ontwikkelomgeving.
Het pong spel zal uitsluitend 2 dagen mogen duren om te maken en zal voor ervaring geen forse toepassing brengen.

Het maken van een spel met een multiplayer functie is ook vanuit eerdere ervaring gemakkelijk en snel te doen.
Al hoewel valt het combineren van deze twee echter iets slechter.
Zo moet er gekeken worden naar hoe het combineren van het Pong spel en de multiplayer op de meest optimale manier te doen valt.

Er word als oplossing aangeraden, door gebruik te maken van 'high level scripting API'.
Deze manier zal het spel van een eenvoudige multiplayer functie voorzien.
Dit is dan ook de manier die er gebruikt zal worden.

Overigens word de mogelijkheid van NetwerkTransport aangeraden, maar dit valt uitsluitend voor geavanceerde spelen (waaronder het spel niet valt).

Ook de doeleisen van minimale input latency en menselijke tegenstander functies, zullen hiermee bereikt worden.

## Leerdoelen

- Het kunnen aanleggen van een basis begrip voor multiplayer spelen.
- Het kunnen impleteren van een multiplayer functie in een spel concept.
- Het kunnen aantonen dat ik goed met multiplayer development om kan gaan.
- Het kunnen gebruiken van de functionaliteit (multiplayer).
- Het kunnen demonstreren van multiplayer functies.
- Het kunnen gebruiken van en omgaan met een derde partij software.

## Planning

| | maandag | dinsdag | woensdag | donderdag | vrijdag |
| --- | --- | --- | --- | --- | --- |
| week 1 | Keuze maken van proefopdracht. Proefopdracht testen op mogelijkheden (het testen van de: Pong mechanics, UNET kennis, multiplayer functie, invoer latency, concept bruikbaarheid). Deze testen omzetten in een software analyse. | Besluit maken van proefopdracht en ontwikkelomgeving. Beginnen met het maken van productie waarde. Met als begin het Pong spel met de benodigde mechanics, speelmogelijkheden en de twee speler functie (tijdelijk offline). | Productie reflecteren in relatie met verwachtigen. Begin maken van de multiplayer functie van het gemaakte Pong spel. | Uitbreinden van de multiplayer functie met uitgebreide database. Het usertesten van de multiplayer functie. | Complete bouw (Pong spel en multiplayer) afronden en polishen met de usertest feedbacks, eisen en verwachtigen. |
| week 2 | Spel gereed maken en reflecteren op extra mogelijkheden en/of uitbreidingen. Begin maken met uitbreidingen. | Spel uitbreindingen volbrengen tot complete extra functie en een persoonlijk twist geven. Het spel nogmaals polishen voor klaar gereed. | Laatste versie van het gemaakte spel online zetten en het inleveren van verwijzing naar team, GIT repository URL, speelbare versie URL en documentatie URL. | Portfolio gereed maken met de verwachte materialen (invullen van template gedeeltes met de huidige proefopdracht). | Inleveren van het reflectie formulier en de overige onderdelen. |

## Bronnen

- [Multiplayer aanwijzingen](https://docs.unity3d.com/Manual/UNetOverview.html)
- [Tutorial series: 'Multiplayer Pong Unity'](https://www.youtube.com/watch?v=1fFdYzGm78U&list=PLVcHD3Lkf4Uab7Nle6GPdJk7qK2KnOL11)
- [Tutorial series: 'How to make a game like Pong in Unity 5'](https://www.youtube.com/watch?v=ztOV-GqjTOM&list=PLiRrp7UEG13a3aiu4G09ygfdb-NV7Op7C)
- [Tutorial series: 'How to make a 2D Game - Unity 4.3 course'](https://www.youtube.com/watch?v=9h-z0AyG42k&list=PLPV2KyIb3jR4_IYZY2V0G3IUYcx1zZkJe)
- [Tutorial video: 'Unity Pong Game in 20 minutes'](https://www.youtube.com/watch?v=1oY--Zk9b6w)
- [Tutorial video: 'UNET basics - How to get started with Unity3D Networking'](https://www.youtube.com/watch?v=0H_ikQp9aTI)
- [Tutorial stream: 'Unity Multiplayer (UNET) - Transport Layer API'](https://www.youtube.com/watch?v=qGkkaNkq8co)
