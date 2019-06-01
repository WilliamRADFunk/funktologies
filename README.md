# funktologies
Contains the ontology files, repeatedly used models and utility functions for a number of data scraping modules.

Also serves as dependency module for the larger [factbook](https://github.com/WilliamRADFunk/factbook.git), [cia-world-leaders](https://github.com/WilliamRADFunk/cia-world-leaders.git), [all-airports](https://github.com/WilliamRADFunk/all-airports.git), and [data-glutton](https://github.com/WilliamRADFunk/data-glutton.git) modules, which culminates data from multiple locations and bridges them under a universal ontology.

***

## Using Funktologies

### 1. Install

Run `npm install --save funktologies`.

### 2. Import any of the utility methods or models directly

* `import { entityMaker } from 'funktologies';`
* `import { entityRefMaker } from 'funktologies';`
* `import { getRelation } from 'funktologies';`
* `import { hasProp } from 'funktologies';`
* `import { CountryReference } from 'funktologies';`
* `import { EntityContainer } from 'funktologies';`
* `import { EntityListWrapper } from 'funktologies';`
* `import { Entity } from 'funktologies';`
* `import { FlatEntity } from 'funktologies';`

### 3. Ontology Location

For `.schema.jsonld` format --> `node_modules/funktologies/dist/ontology/jsonld/`
For `.rdf` format --> `node_modules/funktologies/dist/ontology/owl/`

### 4. You want more?

There is a project at [data-glutton](https://github.com/WilliamRADFunk/data-glutton.git) that coordinates between multiple data scrapers like this one to create a uniform, ontologically defined, store of rich linked data.

Try it out.
