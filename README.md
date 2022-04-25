> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Titel
Pauline van Aken performance audit.


## ContentAudit
Ik heb de website geanalyseerd die ik zelf heb gebouwd voor de klant Pauline van Aken. De performance audit houd ik op 25/04/2022. De url is [PaulineVanAken](https://paulinevanaken.nl/). 
![index of paulinevanaken.nl](/assets/index.png)
<!-- Beschrijf de website die je hebt geanalyseerd en de datum dat je hebt getest. Voeg de url en een screenshot van de website toe.  -->

![Metrics](/assets/metrics.png)


### First Contentful Paint (FCP)
De uitslag van de First Contentful Paint is 0.8s en is daarmee goed genoeg. Eventuele verbeteringen zou zijn "Reduce unused CSS" er zijn een aantal ongebruikte styles van globale stylesheet die weg kunnen. 

### Time to Interactive (TTI)
Time to Interactive is 1.5s en daarmee groen en goed. Minder blocking resources zou het laden/renderen sneller maken.

### Speed Index
Speed index is 1.1s en daarmee groen en goed. Reducing blocking resource sizes zou het ook versnellen.

### Total Blocking Time (TBT)
Total blocking time is 20ms daarmee groen en goed. Het zou sneller kunnen door third-party resources the lazy-loaden.

### Largest Contentful Paint (LCP)
Largest contentful paint is 5.4s en daarmee rood en niet goed. Door enorme network payloads te reduce. Geen critical requests chainen.

### Cumulative Layout Shift (CLS)
De Cumulative Layout Shift is 0.36s en daarmee slecht. Image elements explicit width en height zodat ze niet verschieten tijdens het laden. Avoid large layout shifts.

## Bronnen

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
