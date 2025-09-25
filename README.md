# Hyvinvointivaltio-analyysi

Tämä sivusto sisältää syvällisen analyysin hyvinvointivaltion merkityksestä, sen kritiikistä ja moraalifilosofisista taustoista. Sivusto on rakennettu GitHub Pages:lle ja sisältää neljä keskeistä osiota.

## Tekniset ominaisuudet

- **Responsiivinen design**: Toimii mobiilissa, tabletissa ja työpöydällä
- **Sticky navigation**: Yläpalkki pysyy näkyvissä sivua vierittäessä
- **Tumma/vaalea teema**: Käyttäjä voi vaihtaa teemojen välillä
- **LocalStorage**: Teemavalinta tallennetaan selaimen muistiin
- **GDPR-yhteensopiva**: Cookie consent -kysely EU-säädösten mukaisesti
- **Semantic HTML**: Saavutettava ja hakukoneoptimoitu rakenne

## Sivuston rakenne

### Kansiot
- `/css/` - Tyylitiedostot
- `/js/` - JavaScript-funktionaalisuus  
- `/pages/` - Analyysin eri osiot HTML-muodossa

### Tiedostot
- `index.html` - Etusivu osiokatsauksineen
- `styles.css` - Kaikki tyylimäärittelyt (vaalea/tumma teema)
- `main.js` - Teemavaihto, cookie consent, navigation
- Neljä analyysisivua `/pages/` -kansiossa

## Osioyhdistykset

1. **Oppimiskatko** - Tieteen vs. politiikan oppimismallit
2. **Empiiriset vastaukset** - Vastaukset ideologisiin kritiikkeihin
3. **Yhteiskunnallinen sopimus** - Itsekäs politiikka tuhoaa itsensä  
4. **Moraaliset juuret** - Miksi faktat eivät muuta mielipiteitä

## Käyttöönotto GitHub Pages:ssa

1. Luo uusi repository nimeltä `hyvinvointivaltio-analyysi`
2. Lisää kaikki tiedostot repositoryyn kansioineen
3. Mene Settings > Pages
4. Valitse source: "Deploy from a branch"
5. Valitse branch: `main` ja folder: `/ (docs)`
6. Sivusto on valmis osoitteessa: `https://stochastic-philosophy.github.io/hyvinvointivaltio-analyysi/`

## Tekniikat

- **HTML5**: Semanttinen markup
- **CSS3**: Custom properties, flexbox, grid
- **Vanilla JavaScript**: Ei ulkoisia riippuvuuksia
- **GitHub Pages**: Staattinen hosting

## Tietosuoja

Sivusto tallentaa ainoastaan teemavalintaa selaimen localStorage:een käyttäjän suostumuksella GDPR-säädösten mukaisesti.
