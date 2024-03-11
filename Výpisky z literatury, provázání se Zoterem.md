# Výpisky z literatury, provázání se Zoterem

Důležitou součástí [[Metoda zettelkasten]] je právě pořizování výpisků z literatury a jiných zdrojů. Za tímto účelem je vhodné si vytvořit systém pojmenovávání a strukturování poznámek, podobný například [[@2021_Ahrens]]. 

![[@2021_Ahrens]]

## Zásady
Za důležité zde považuji
1. Odlišení od ostatních poznámek pomocí **@**, souhrnné poznámky k autorům například pomocí **&**.
2. Jednoznačný citační klíč (možno řadit dle roku nebo autora, uvést zkrácený název publikace; volba závisí na osobní preferenci, ale je třeba dodržovat systém).
3. Uvedení základních bibliografických dat.
4. Použití hashtagu pro grafické odlišení.
5. Označování strany. Buď pomocí nadpisu jako je v ukázce, nebo pomocí **^** na řádku pod odstavcem. Např.
^zasady-biblio

Výhodný je tento systém nejen kvůli zpětnému dohledávání v literatuře, ale také kvůli možnosti přesnějšího odkazování - [[#^zasady-biblio]], [[#Zásady]].

## Zotero
[Zotero](https://www.zotero.org/)

Zotero je program pro správu zdrojů podobný Citacím PRO, Mendeley a jiným. Jedná se o open-source nástroj s možností bezplatné synchronizace. Umožňuje vkládání zdrojů pomocí pluginu pro webové prohlížeče a také pomocí běžných identifikátorů (DOI, ISBD apod.). Podobně jako v případě [[Obsidian]], databáze se ukládá lokálně.

V souvislosti s Obsidianem jsou důležité možnosti pluginu [Better Bibtex](https://retorque.re/zotero-better-bibtex/), který umožňuje zdrojům fixovat citační klíč (uživatelé $\LaTeX u$ vědí). 

Celou databázi je možné exportovat (a udržovat synchronizovanou) jako *CSL-JSON*. Tuto exportovanou databázi je následně možné procházet pomocí [citačního pluginu pro Obsidian](https://github.com/hans/obsidian-citation-plugin).