# Voorbewerking van de datasets

Er zijn veel verschillende datasets gebruikt om onze datastory te ondersteunen. Toen eenmaal het onderwerp van onze datastory rond was, begon ieder het internet af te struinen op zoek naar toepasselijke datasets. Naarmate het onderzoek vorderde, werd het duidelijker wat voor soort data wij nodig hadden, en was het daarmee ook makkelijker specefiekere data te zoeken en te vinden. Elke groepsgenoot heeft wel meerdere datasets gevonden. 

## Voorbewerking 

Sommige van de gebruikte datasets hebben wij aangepast om zo met gemak de data te analyseren en te laten visualiseren:
- Nederlandse datasets bevatten vaak komma's waarmee floats worden definieerd, wat zorgde voor problemen bij het plotten van grafieken. Plotly ziet deze gegevens als strings en daarom werden de gegevens onjuist gevisualiseerd. Voor desbetreffende kolommen is code geschreven om de komma's in punten te veranderen. Het type van de gegevens wordt van string naar float omgezet. Dit is voor meerde datasets gedaan. 
- Sommige datasets hadden niet voor elke kolom een variabele naam gegeven. Om het voor ons makkelijker te maken met deze dataset om te gaan, hebben wij in sommige gevallen handmatig een kolom een naam gegeven, bijvoorbeeld iets als 'Jaartal'.
- Daarnaast is handmatig een dataset gemaakt op basis van verschillende bestaande datasets. Meerdere stukken data van verschillende sets is bij elkaar geplakt in een document.