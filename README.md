# Rodokmen

*English version below → [English](#english)*

**Nástroj pro bádání v matrikách a rodinný web pro české a moravské rodokmeny.**

Každý údaj nese míru jistoty a odkaz na konkrétní snímek matriky. Web ukazuje rodinu jako
interaktivní rodokmen, vějíř předků, mapu, časovou osu na pozadí dějin a stránku pro každého
člověka i každý matriční zápis. Žijící lidi chrání pravidlo, které se kontroluje při každém
sestavení webu, ne slib, na který je potřeba myslet.

**[Prohlédněte si živou ukázku →](https://rodokmen-demo.pages.dev)**

> Ukázka i obrázky představují **vymyšlenou rodinu**: 379 lidí ve třinácti generacích, asi 600
> matričních zápisů latinsky, německy a česky, náhrobky, příběhy a otevřené otázky. Skutečné jsou
> jen obce (Vysočina).

![Úvodní stránka / Home page](docs/images/home.png)

## Co umí

| | |
|---|---|
| **Jistota u každého údaje** | Pět stupňů, od „přečteno na snímku matriky nebo na náhrobku“ až po „neznámo“. Člověk je tak jistý, jak jistý je nejslabší údaj, který ho určuje. |
| **Matriční zápisy** | Přepis v původním jazyce, český překlad, archivní citace a přímý odkaz na snímek. Samotné snímky se nikdy nezveřejňují. |
| **Rodokmen** | Předkové nahoře, potomci dole, kdokoli uprostřed; přibližování, posun, tisk. |
| **Vějíř předků** | Tolik generací, kolik údaje sahají; každá rodová linie má svou barvu. |
| **Mapa** | Narození, sňatky a úmrtí podle obcí, s čarami, kam se lidé stěhovali. |
| **Časová osa** | Životy předků na pozadí válek, epidemií a reforem českých dějin. |
| **Příběhy a linie** | V údajích se samy najdou náměty na příběhy (dlouhé životy, velké rodiny, epidemie, jeden dům po generace); každá rodová linie může mít svůj příběh. |
| **Ochrana soukromí** | U žijících lidí jen jméno a rok narození; zápisy mladší než zákonná lhůta zůstanou skryté; když by cokoli uniklo, web se nezveřejní. |
| **Soukromý ve výchozím stavu** | Skutečný rodinný web je za přihlášením jen pro rodinu; vyhledávače ho neindexují. |
| **Hledání a tisk** | Fulltextové hledání na každé stránce; rodokmen k vytištění na jeden list. |

## Obrázky / Pictures

| | |
|---|---|
| ![Rodokmen](docs/images/chart.png) | ![Vějíř předků](docs/images/fan.png) |
| Rodokmen kolem jednoho člověka<br>*Family chart around one person* | Vějíř předků<br>*Fan of ancestors* |
| ![Mapa](docs/images/map.png) | ![Časová osa](docs/images/timeline.png) |
| Kde rodina žila<br>*Where the family lived* | Životy na pozadí dějin<br>*Lives against history* |
| ![Stránka osoby](docs/images/person.png) | ![Matriční zápis](docs/images/record.png) |
| Člověk se zdroji a údaji z matrik<br>*A person with sources and register details* | Matriční zápis: přepis a překlad<br>*A register entry: transcription and translation* |
| ![Příběhy](docs/images/stories.png) | |
| Příběhy nalezené v údajích<br>*Stories found in the data* | |

## Na čem je postavený

Nástroj v Pythonu s přísným datovým modelem, kontrolou souladu údajů a ochrany soukromí, a statický
web (Astro) s interaktivními pohledy. Žádné sledování návštěvníků; jediný vnější požadavek jsou
mapové podklady.

## Podobný rodokmen pro vaši rodinu?

Bádání v matrikách i web jako v ukázce lze připravit na zakázku.
Kontakt najdete na **[svobodamartin.dev](https://svobodamartin.dev)**.

---

Tento repozitář je jen ukázka; zdrojový kód není veřejný. © Všechna práva vyhrazena.

---

<a id="english"></a>

# English

**A genealogy engine and family website for Czech and Moravian parish-register research.**

Every fact carries its evidence level and a citation down to the register image. The site shows the
family as an interactive chart, a fan of ancestors, a map, a timeline against history, and a page
for every person and every register entry. Living people are protected by a rule the build checks,
not a promise someone has to remember.

**[See the live demo →](https://rodokmen-demo.pages.dev)**

> The demo and the pictures show an **invented family**: 379 people across thirteen generations,
> about 600 register entries in Latin, German and Czech, gravestones, stories and open questions.
> Only the villages (Vysočina region) are real. The site's interface is in Czech.

## What it does

| | |
|---|---|
| **Evidence on every fact** | Five levels, from "read on the register image or a gravestone" down to "unknown". A person is as sure as the weakest fact that identifies them. |
| **Register entries** | Transcription in the original language, Czech translation, archive citation and a deep link to the scan. Scans themselves are never published. |
| **Family chart** | Ancestors above, descendants below, any person in the centre; zoom, pan, print. |
| **Fan of ancestors** | As many generations as the data reaches, each family line in its own colour. |
| **Map** | Births, marriages and deaths by village, with lines showing where people moved. |
| **Timeline** | Life bars of the ancestors over wars, epidemics and reforms of Czech history. |
| **Stories and lines** | Candidate stories are found in the data (long lives, large families, epidemics, one house over generations); each family line can carry its own story. |
| **Privacy** | Living people show only name and birth year; register text younger than the legal embargo stays out; nothing is published if anything leaks. |
| **Private by default** | The real family site sits behind a sign-in for the family only; nothing is indexed by search engines. |
| **Search and print** | Full-text search on every page; a printable one-sheet pedigree. |

## Pictures

See [the pictures above](#obrázky--pictures) (captions in both languages).

## Built with

A Python engine with a strict data model, consistency and privacy checks, and a static website
(Astro) with interactive views. No tracking; the map tiles are the only outside request.

## A family tree like this for your family?

Research in the parish registers and a website like the demo can be made to order.
Get in touch via **[svobodamartin.dev](https://svobodamartin.dev)**.

---

This repository is a showcase only; the source code is not public. © All rights reserved.
