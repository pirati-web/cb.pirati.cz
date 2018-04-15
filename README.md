# Web ceskobudejovickych Pirátů

Pro psaní článků je třeba umět [markdown](https://cs.wikipedia.org/wiki/Markdown).
Web má [admin rozhraní pro úpravu článků](https://cb.pirati.cz/admin/).

Pro nasledujici plati: vychazet z jiz existujiciho .. :
- dulezite linky se upravuji v souboru [_data/links.yml](_data/links.yml)
- odkazy na propagacni materialy se upravuji v souboru [_data/materialy.yml](_data/materialy.yml)
- akce v cepici se upravuji v souboru [_data/akce_cepice.yml](_data/akce_cepice.yml)
- obecne akce (s cepici nesouvisejici) se upravuji v souboru [_data/akce.yml](_data/akce.yml)

Pro úpravu ostatního je potřeba umět [Jekyll](http://jekyllrb.com/).
A je třeba seznámit se alespoň se základy gitu.

** A nebo dělat pokusy, vychazet z jiz existujiciho. Zas tak slozity to neni :) **

## dale uz pro programatory ...

### Lokální test (pro experty)

V adresaři s repozitářem spustíme příkaz:
`bundle exec jekyll serve --incremental --baseurl '' `
což spustí server s webem a my si ho můžeme prohlédnout.

#### Update zavislosti

```
git submodule update --remote --merge
```

#### init zavislosti

```
git submodule add https://github.com/pirati-web/layouts _layouts
git submodule add https://github.com/pirati-web/partials _includes/shared/
git submodule init
```
