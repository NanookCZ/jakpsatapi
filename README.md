# Jak psát API

Znáte **[Jak psát web](http://www.jakpsatweb.cz)**, návod na HTML stránky? Toto je **Jak psát API**, návod na webová API.

## Co jsou webová API?

API znamená *application programming interface* a v IT tato zkratka znamená [spoustu věcí](https://cs.wikipedia.org/wiki/API). Všechny ty věci by se daly zhruba shrnout do českého slova *rozhraní*. Je to tedy nějaký způsob, jakým se domlouvají systémy, aplikace, knihovny nebo i jednotlivé objekty mezi sebou.

Webová API jsou souhrnný název pro taková rozhraní, která jsou založená na stejných technologiích, na jakých běží web. Tzn. že jako nosný protokol zpravidla používají HTTP nebo HTTPS a komunikace se většinou odehrává ve formátech jako XML, JSON, apod. Příkladem budiž třeba [API Facebooku](https://developers.facebook.com/docs/graph-api).

Schválně nepoužívám výraz [REST API](https://cs.wikipedia.org/wiki/Representational_state_transfer), protože znamená něco úplně jiného. Nejblíže popisu výše je možná HTTP API, ale označení *webová API* mi přijde o dost lidštější a v angličtině se navíc spojení *web APIs* zcela běžně používá.

## Co má společného Jak psát API s Jak psát web?

Dalo by se říci že nic, protože **Jak psát API** píše úplně jiný člověk a žádné partnerství s **Jak psát web** neexistuje. Název jsem ale nezvolil proto, abych se přiživil na slávě JPW a Yuhůa. Vybral jsem jej proto, že ve webových API vidím velkou budoucnost a věřím, že JPA by mohlo jednou být stejně potřebné, jako dříve JPW.

Doby, kdy si firmy hledaly cestu na Internet (tehdy jednoznačně s velkým I!) a kdy najednou i pekař ve vaší ulici zjisti, že by nejspíš měl mít nějaký web, ty jsou za námi. Čeká nás ale dost podobné období na poli webových API - díky potřebě integrací, mobilních aplikací, [Internet of Things](https://cs.wikipedia.org/wiki/Internet_v%C4%9Bc%C3%AD) aj. trendům brzy i kdejaká menší firma zjistí, že bez API jako kdyby neexistovala.

Navíc věřím tomu, že nejlepší způsob jak psát API je tvořit je stejným způsobem, jakým tvoříme web. Tzn. uplatnit co nejvíce možnosti HTTP, hyperlinků, použitelnosti, atd.

## Obsah

- Dokumentace
- Verzování
- Chyby
- Autorizace a autentikace
- Parametrizace odpovědi
- HTTP
    - Content Negotiation
    - Kešování
    - HTTP 2.0
- REST
    - REST vs. SOAP
- Hypermedia (HATEOAS)
    - Formáty
- JSON
    - Schema
    - PATCH
- Nástroje a knihovny
    - nezávislé na jazyku
    - Python
    - Ruby

## Jak přispívat?

### Písmenka

Pište v [Markdownu](http://daringfireball.net/projects/markdown/) a posílejte [pull requesty](http://help.github.com/send-pull-requests/). Uvítám v [issues](https://github.com/honzajavorek/jakpsatapi/issues) opravy chyb, nové články i nejrůznější polemiky.

### Korunky

Peníze posílejte na 2400293585/[2010](http://www.fio.cz/), nejlépe s nějakou zprávou, podle které je rozliším - např. "JPA".

## Tiráž

### Kontakt

Založte *issue* [zde](https://github.com/honzajavorek/jakpsatapi/issues), nebo pište na <a
href="mailto:mail&#64;honzajavorek.cz">mail&#64;honzajavorek.cz</a>.

### Autor

**Jak psát API** založil a spravuje [Honza Javorek](http://honzajavorek.cz). Honza pracuje pro [Apiary](http://apiary.io), ale tento projekt je jeho soukromou aktivitou. (V zásadě by se dalo říct, že si zde ukládám zajímavé informace a třídím si své myšlenky.)

Chcete-li, aby vám Honza odvyprávěl zde sepsané vědomosti naživo, domluvte se s ním e-mailem na školení nebo přednášce.

### Licence? CC BY-NC-SA

(cc) 2014 Jan Javorek &lt;<a
href="mailto:mail&#64;honzajavorek.cz">mail&#64;honzajavorek.cz</a>&gt;

Toto dílo podléhá licenci [Creative Commons Uveďte autora-Nevyužívejte dílo komerčně-Zachovejte licenci 3.0 Česko](https://creativecommons.org/licenses/by-nc-sa/3.0/cz/).

(*Nevyužívejte dílo komerčně* neznamená, že zde nabyté vědomosti nesmíte použít na svém komerčním API, ale že nesmíte tyto stránky seskládat do knížky a prodávat.)
