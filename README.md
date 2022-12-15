# Cvičení na vkládání obrázků do stránky

V tomto cvičení si studenti vyzkouší možnosti elementární úpravy obrázků pro vložení do stránky. 

Ve složce /images je k dispozici pokusná fotografie. Na ní se nachází [Kastel de Haar](https://en.wikipedia.org/wiki/De_Haar_Castle) v Nizozemí. (JPEG, 1513x851 px, 422 kB)

Každou vypracovanou část zadání vložte do souboru index.html jako samostatnou sekci. Obrázek před tím zmenšete tak, aby měl šířku 1024px.

## Formáty

Nejprve se podíváme na vhodnost souborových formátů.

### Porovnání velikostí

Při zachování rozlišení se pokuste pomocí https://squoosh.app převést obrázek do formátů JPEG, WEBP a AVIF. Do stránky vložte seznam těchto velikostí a velikostí souborů.

### Ztrátová komprese

Pokuste se obrázek zmenšit tak, aby měl výsledný soubor velikost pod 80 kB ve formátech JPEG, WEBP a AVIF. Všechny tyto verze vložte na stránku s popiskem (figure?), ve kterém bude napsáno o jaký formát jde, jaké jsou parametry komprese a jaká je výsledná velikost.

## Použití ``srcset``

Upravte obrázek na tří šířky: 960px, 768px, 480px

Vložte jej na stránku pomocí atributu srcset tak, aby se pro různé velikosti viewportu ("okna prohlížeče") načítal správný obrázek.

## Alternativní zdroje

Pomocí značky ``<picture>`` vložte na stránku obrázek tak, aby si prohlížeč sám vybral, který formát (JPG, WEBP, AVIF) může použít.

Obzvláště zvědaví/pracovití/nadšení/nadaní studenti mohou předchozí dva body zadání (SRCSET a PICTURE) zkombinovat.

## Výsledek

Výslednou stránku zveřejněte přes GitHub pages.
