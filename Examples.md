		Gene Vangampelaere (gene@digie.be) // Voorbeeld prompts
# Tree of thought
Stel je voor dat drie verschillende experts deze vraag beantwoorden.
Alle experts schrijven 1 stap van hun denkwijze op,
en delen dit met de groep.
Dan gaan alle experts verder met de volgende stap, enz.
Als een expert zich op een bepaald punt realiseert dat hij het mis heeft, dan vertrekt hij.
Ga door zonder te onderbreken, totdat er een definitieve oplossing is.

De vraag luidt:
De som van 2 niet negatieve getallen is 36, Vind de getallen als de verschillen van hun vierkantswortel zo groot mogelijk moeten zijn.


# Knowledge cut-off
Kun je me meer vertellen over de recente steekpartij in een kerk in Sydney?

# PDF summarize
*use Microsoft Edge browser*

- Open a [PDF document](https://www.baloise.be/dam/baloise-be/over-ons/documents/nl/wet-recht/modelovereenkomst-voor-de-verplichte-aansprakelijkheidsverzekering-inzake-motorrijtuigen.pdf) in your Edge browser
- Use prompt: *can you summarize this page?*
- Mijn motor is verzekerd en dit is de polis. Is mijn auto dan ook mee verzekerd?
- Kunt u een praktijkvoorbeeld geven van aansprakelijkheidsdekking?
- ik geef een presentatie over dit document. Welke zaken moeten zeker aan bod komen?
- Genereer een afbeelding dat ik op de titelslide kan gebruiken.




# Behave as a historical person
Ik wil dat je je gedraagt als {persoon}, een beroemd historisch figuur. Ik wil dat je antwoordt en antwoordt zoals hij dat zou doen, met dezelfde toon, manier van spreken, meningen, filosofie en woordenschat die hij zou gebruiken, maar je praat in het Nederlands. Schrijf geen uitleg, antwoord gewoon zoals hij zou doen. Je moet de kennis van {persoon} al hebben. Mijn eerste zin is "Hallo."

persoon = {Napoleon Bonaparte}


## Ask questions
- Waar ben je geboren?
- Heb jij kinderen?
  - Controleer dit op de [Wikipedia pagina](https://nl.wikipedia.org/wiki/Napoleon_Bonaparte#Relaties_en_kinderen)

## Use ChatGPT and CoPilot
- Er is een film gemaakt over Napoleon Bonaparte, wanneer kwam deze uit en wie was de regisseur?
- - Kun je voor mij een passende afbeelding maken van een mogelijke poster voor deze film?
- Wie speelt de hoofdrol?
- In welke andere films heeft Joaquin Phoenix gespeeld? Geef een overzicht in tabelvorm. Gebruik volgende kolommen: Filmtitel, Regisseur, jaar



# Playing a game
Je neemt de rol van spelleider op je voor "Wie ben ik?". De taal waarin je communiceert is Nederlands. 

1. Je kiest in gedachten een personage uit de serie "The Simpsons".
2. Ik stel je vragen over het personage en jij antwoordt alleen met "ja" of "nee".
3. Als een van mijn vragen niet met "ja" of "nee" beantwoord kan worden, geef je aan dat je niet mag antwoorden omdat het geen ja/nee vraag is.
4. Je stelt zelf geen vragen en geeft geen extra uitleg.
5. Wanneer ik "stop" intyp, onthul je het gekozen karakter.
6. Als ik om een "hint" vraag, geef jij een hint en spelen we verder.

Begin het spel met de zin "Ik heb iemand gekozen".


## Questions to ask
- Ben je een man?
- Welke haarkleur heb jij?

# Exam questions
## exam questions

Je speelt de rol van een leraar. De leerstof staat hieronder tussen **. Geef {x} vragen.Geef een aantal makkelijke en moeilijke vragen. Geef in elk geval tussen haakjes aan of de vraag makkelijk ([niveau] = +) of moeilijk (niveau [niveau] = ++) is via [niveau]. De gebruiker zal de vragen beantwoorden. Gebruik alleen informatie uit het lesmateriaal tussen **.
Onder de {x} vragen staan ook de antwoorden. Gebruik onderstaande structuur tussen '''' 

'''
{x} vragen [niveau]:

1. 

...

{x} antwoorden:
1. 

...

'''


parameters:
{x} = 5



Leerstof:
**
Cellen zijn de kleinste levende eenheden van het lichaam en van de meeste organismen. Cellen leven en vertonen dus levensverschijnselen zoals ademen, uitscheiden, eten, voortplanten en afsterven. Cellen zijn opgebouwd uit organellen. Je kunt deze organellen vergelijken met de organen in je eigen lichaam. Alle organellen hebben een functie met als doel de cel in leven te houden. Globaal gesproken zijn er drie soorten cellen op aarde. Cellen zonder kern, cellen met kern en cellen met celwanden. De cellen zonder kern behoren tot organismen uit het bacterierijk. De cellen van alle andere organismen hebben een kern. Plantencellen en schimmelcellen hebben, net als bacteriën, een celwand. Deze celwand geeft stevigheid aan de cellen en daarmee aan het hele organisme. Dierlijke cellen hebben geen celwand. Dierlijke weefsels moeten daarom hun kracht uit het intercellulaire materiaal halen.
Een weefsel is een groep cellen die samenwerken met ongeveer dezelfde structuur, maar vooral dezelfde functie. Cellen kunnen op zeer korte afstand goed met elkaar communiceren via chemische signalen die ze kunnen produceren. Hierdoor kunnen de cellen hun gedrag aan elkaar aanpassen en in harmonieuze samenwerking een gemeenschappelijke taak uitvoeren. Weefsels kunnen verschillende taken en structuren hebben. Spierweefsel heeft bijvoorbeeld beweging als taak. Botweefsel geeft kracht aan het organisme. Dierlijke cellen zijn van nature slap (zie video hieronder). Een boterhamzakje gevuld met water. Weefsels die het organisme kracht moeten geven, halen deze kracht uit de tussenliggende celsubstantie. Dit kan hard, zacht, flexibel of zeer rekbaar zijn. Het tussenliggende celmateriaal is dood. Behoort niet tot de levende cel.
Cellen kunnen niet alleen communiceren met cellen van dezelfde soort, maar ook met cellen van andere weefsels. Weefsels kunnen dus goed samenwerken. Groepen weefsels die samenwerken, worden een orgaan genoemd. De meeste organen in het menselijk lichaam bestaan uit meerdere weefsels. Een hart bestaat voor een groot deel uit spierweefsel, vetweefsel, zenuwweefsel en de weefsels die de bloedvaten vormen. Een orgaan is een deel van uw lichaam met een specifieke functie.
Een orgaansysteem is een groep organen die samenwerken met een specifieke functie voor het organisme.
**


# Play PowerPoint Karaoke ;-)
Laten we PowerPoint-karaoke spelen.
Je krijgt 3 willekeurige woorden op een dia en je moet er een verhaal van 1 minuut over genereren.
Start het spel door de gebruiker 3 willekeurige woorden te vragen. Geef de gebruiker de instructie om de woorden te typen en ze te scheiden met een komma.
Begin vervolgens met het genereren van een grappig verhaal met die woorden.

Wanneer je verhaal klaar is, vraag je nog eens 3 woorden en herhaal je dit totdat de gebruiker 'stop' typt.

## Genereer een prompt

- stop
- maak een prompt waarmee we een afbeelding kunnen maken dat bij dit verhaal hoort. 
- Gebruik deze prompt in CoPilot

# Review

## Generate reviews

Genereer {x} reviews over mijn startup. De beschrijving van de startup vind je hieronder tussen ****.

Gebruik dit format voor elke recensie:

- Naam van de gebruiker (land)
- Beoordeling
- Algemene score (van de 5)

{x}=10

**
Introductie van "EcoNexa" – waar duurzaamheid en innovatie samenkomen in de palm van je hand. Bij EcoNexa brengen we een revolutie teweeg in de smartphone-industrie met onze toewijding aan de planeet en de allernieuwste technologie. Onze smartphones zijn meer dan alleen apparaten; het is een verklaring van verantwoordelijkheid voor het milieu.

De kern van het ethos van EcoNexa is onze toewijding aan het verminderen van elektronisch afval. We hebben onze smartphones waar mogelijk gemaakt met gerecyclede materialen, waardoor we onze ecologische voetafdruk tot een minimum hebben beperkt zonder concessies te doen aan de kwaliteit of prestaties. Elke EcoNexa-telefoon is een bewijs van ons geloof in een circulaire economie, waarin hulpbronnen worden hergebruikt en een nieuwe bestemming krijgen om iets werkelijk opmerkelijks te creëren.

Maar daar stopten we niet. EcoNexa-smartphones beschikken over de modernste milieuvriendelijke functies, waaronder energiezuinige componenten, biologisch afbreekbare verpakkingen en duurzame productieprocessen. Met een strak ontwerp dat net zo prettig is voor de ogen als voor de planeet, belichamen onze telefoons stijl en duurzaamheid in perfecte harmonie.

Sluit je aan bij onze missie om de toekomst van technologie opnieuw te definiëren. Kies EcoNexa – waar elk gesprek, elke sms en elke selfie een positieve impact heeft op de wereld die we delen.
**

## Analyse reviews

Lees de recensies tussen **** aandachtig en beantwoord de volgende vragen:

Voor elke beoordeling:

1. Bepaal het sentiment: is het positief of negatief?
2. Is de auteur boos? Antwoord ja of nee.
3. Hoe voelt de auteur zich?
4. Wie is de auteur van de recensie? Vermeld de naam.
5. Wat is het geslacht van de auteur? (man, vrouw of onbekend)
6. Geef een beknopte samenvatting van de beoordeling in maximaal 100 woorden.

Antwoord volledig in het Nederlands.

Na analyse van alle beoordelingen:

- Bepaal de totaalscore van de startup op basis van de reviews.
- Bepaal hoeveel positieve, negatieve en neutrale reviews er zijn.
- Beoordeel of de startup succesvol is en geef suggesties voor verbetering.

**

Sophie (België)
Beoordeling: Eco-vriendelijkheid ontmoet innovatie
Algemene score: 4/5

EcoNexa heeft mijn hart gestolen met zijn toewijding aan duurzaamheid en innovatie. Als Belg ben ik trots om te zien hoe een bedrijf zich inzet voor het verminderen van elektronisch afval. De gerecyclede materialen en milieuvriendelijke functies maken deze smartphone een winnaar voor mij. Het enige wat ik zou willen zien verbeterd, is de batterijduur, maar over het algemeen ben ik zeer tevreden.

John (USA)
Beoordeling: Cutting-edge Technology with a Green Twist
Algemene score: 5/5

As an American consumer, I'm always looking for products that blend technology with sustainability, and EcoNexa does just that. The commitment to reducing electronic waste while still delivering top-notch performance is commendable. I've been using my EcoNexa phone for a few weeks now, and I'm impressed by its sleek design and eco-friendly features. Highly recommended!

Maria (Spanje)
Beoordeling: Compromiso ecológico sin sacrificar calidad
Algemene score: 4.5/5

Como española, me preocupa mucho el impacto ambiental de los productos que consumo. EcoNexa ha logrado combinar la calidad de un smartphone de alta gama con su compromiso con el medio ambiente de una manera excepcional. Me encanta saber que cada vez que uso mi teléfono, estoy contribuyendo positivamente al planeta. ¡Bravo EcoNexa!

Hans (Duitsland)
Beoordeling: Umweltfreundlichkeit trifft auf innovative Technologie
Algemene score: 4/5

Als Deutscher bin ich besonders beeindruckt von EcoNexas Engagement für Nachhaltigkeit und Innovation. Die Verwendung von recycelten Materialien und die umweltfreundlichen Funktionen machen dieses Smartphone zu einer attraktiven Wahl für umweltbewusste Verbraucher wie mich. Ich hoffe jedoch, dass zukünftige Modelle eine noch längere Akkulaufzeit bieten können. Insgesamt bin ich jedoch sehr zufrieden mit meinem EcoNexa-Telefon.

Emily (UK)
Beoordeling: Stylish, Sustainable, and Sophisticated
Algemene score: 4.5/5

EcoNexa has exceeded my expectations with its blend of style and sustainability. As a British consumer, I appreciate the sleek design and eco-friendly features of this smartphone. Knowing that I'm making a positive impact on the environment with every use gives me peace of mind. My only suggestion would be to improve the camera quality, but overall, I'm extremely satisfied with my EcoNexa phone.

Luca (Italy)
Beoordeling: Tecnologia all'avanguardia con un tocco ecologico
Algemene score: 4.5/5

Come consumatore italiano, sono sempre alla ricerca di prodotti che combinino tecnologia e sostenibilità, e EcoNexa fa proprio questo. L'impegno per ridurre i rifiuti elettronici pur mantenendo elevate prestazioni è lodevole. Utilizzo il mio telefono EcoNexa da qualche settimana e sono rimasto impressionato dal suo design elegante e dalle sue caratteristiche ecologiche. Consigliatissimo!

Linh (Vietnam)
Beoordeling: Sự kết hợp hoàn hảo giữa công nghệ tiên tiến và bảo vệ môi trường
Algemene score: 4.5/5

Là một người tiêu dùng Việt Nam, tôi luôn tìm kiếm những sản phẩm kết hợp giữa công nghệ và bảo vệ môi trường, và EcoNexa chính là một trong số đó. Sự cam kết giảm thiểu rác điện tử trong khi vẫn giữ được hiệu suất cao là đáng khen ngợi. Tôi đã sử dụng điện thoại EcoNexa của mình và ấn tượng với thiết kế mạnh mẽ và các tính năng thân thiện với môi trường. Rất đáng giới thiệu!

Lea (France)
Beoordeling: Allier performance et respect de l'environnement
Algemene score: 4/5

En tant que consommatrice française, je suis toujours à la recherche de produits alliant performance et respect de l'environnement, et EcoNexa répond parfaitement à ces critères. La réduction des déchets électroniques tout en offrant une qualité de téléphone haut de gamme est très appréciable. J'utilise mon téléphone EcoNexa depuis quelques semaines maintenant et je suis ravie de son design épuré et de ses fonctionnalités respectueuses de l'environnement. Je recommande vivement !

Ahmed (Egypt)
Beoordeling: حيث تلتقي التكنولوجيا الحديثة بلمسة خضراء
Algemene score: 4/5

   كمستهلك مصري، أبحث دائمًا عن المنتجات التي تجمع بين التكنولوجيا والاستدامة، وهذا ما يقدمه EcoNexa بشكل مثالي. التزام الشركة بتقليل النفايات الإلكترونية مع الحفاظ على أداء عالي يستحق الثناء. استخدمت هاتفي EcoNexa لبضعة أسابيع الآن وأنا معجب بتصميمه الأنيق والميزات الصديقة للبيئة. أوصي به بشدة!

Mei (China)
Beoordeling: 高端科技与绿色理念完美融合
Algemene score: 4.5/5

作为一名中国消费者，我一直在寻找将高科技与可持续发展理

念结合在一起的产品，而 EcoNexa 正是这样一款完美的产品。公司致力于减少电子废物的做法值得称赞，同时保持高性能。我使用了 EcoNexa 手机几周了，对其时尚设计和环保功能印象深刻。强烈推荐！

**

## Format output
Give me the results in a table


