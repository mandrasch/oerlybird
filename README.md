# OERlybird
Low budget infrastructure concept for sharing Open Educational Resources (OER) across institutions and based on modern web standards.

No funding? No problem!

## Goals
1. OERlybird showroom = Provide a low budget alternative to repository software for OER projects and institutions starting with a few OERs 
2. OERlybird index = Provide a low budget search index to index all the oerlybird-instances (showrooms) to let users search across instances

## Principles
1. Keep it simple!
2. Keep it as flexible as possible!
3. Keep it maintainable!
4. Use the open web, schema.org and XML sitemaps!
5. No APIs!

## Concept

### 1. OERly bird showroom(s)

1. Setup wordpress
2. Install metabox.io plugin
3. Install oerlybird-wp
4. Install Google XML sitemaps

#### Setup an OERly bird showroom with Wordpress for your institution
Institutions or projects simply setup a standard Wordpress instance, e.g. at oer.university-x.org. 

##### Add metadata editing capability to Wordpress
Wordpress has many features, but there is no easy way to add OER metadata (Authors, License, Subject, etc.) to posts and pages. Therefore a lightweight plugin is needed, based on the already existing Open Source Wordpress Plugin Metabox (https://metabox.io/).

Boilerplate: OERly-bird-WP, COMING SOON
first alpha: https://github.com/programmieraffe/oerbox-highered-de

Example: Create page with OER about X

To enhance the possibilities, Pods (https://de.wordpress.org/plugins/pods/) can be considered as well. E.g. if you want to have a customizable projects directory.

##### Add sitemaps xml

Install the following plugin
https://de.wordpress.org/plugins/google-sitemap-generator/ (Thanks to Arne Brachhold)

Other CMS can be considered as well of course. 

### 2. OERly bird index

Yeah, this gets a bit tricky and nerdy now. 

#### Setup a search crawler and index with PHP/MySQL and ElasticSearch

- SaaS: Appbase (rate limited, but free start package), Stackhero (fixed pricing, but no free instance)
- First Prototype: https://github.com/programmieraffe/oerhoernchen20

### DEMO

- Submit your instance
