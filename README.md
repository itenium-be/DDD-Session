DDD & BDD
=========

Session by Gaëtan.

Date TBD: 2024-11 - 2024-12

2 services:
- 1 die een heel kleine UI bevat
- 1 die puur backend is.

Services connected by a messaging service (ex: Apache Pulsar).

Binnen de service die de UI bevat zou de nodige code al voorzien zijn, alsook de bijhorende providers voor de pact testen.
Deze zou enkel gebruikt worden voor input en het versturen van events.

De workshop zou volledig draaien om de tweede service.

Exercises:
- Schrijven van een pact test (consumer) voor een bepaald event (waarvoor de provider dus al voorzien is).
- Ik zou (momenteel nog falende) BDD's voorzien voor bepaalde domein logica die geimplementeerd moet worden.

## Additional Infos

Na een korte uitleg rond BDD's, volgt de opdracht om het domein aan te passen zodanig dat deze testen slagen. Ik zou hen logica laten implementeren waarvoor het makkelijker en intuitiever is om deze buiten het domein te implementeren (in de eventhandler). Hier heb ik al het perfect voorbeeld voor, aangezien ik daar onlangs tegen ben gelopen. Ik zou het verschil in beide implementaties (binnen het domein of in de eventhandler) dan achteraf toelichten om de moeilijkheden van DDD wat duidelijk te maken.Tenslotte zou ik een opdracht geven om de huidige logica aan te passen naar nieuwe "requirements", specifiek om enkele voordelen van DDD aan te kaarten (betere domein kennis en meer flexibel bij evoluerende business-requirements). Ik zou deze aanpassing dan ook vergelijken met dezelfde aanpassing zonder DDD approach en de moeilijkheden die daarmee gepaard zouden gaan. Dit is puur gebaseerd op mijn huidige ervaring

### DDD

Het kan wat oppervlakkig blijven en kan meer draaien om de filosofie erachter (discussies over domein, pro's en con's van bepaalde implementaties,...) of ik kan er meteen volledig op ingaan met net iets complexere zaken (aggregates, aggregate roots, value objects, entities, invarianten...).
