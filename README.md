# osuny-plugin-news-sitemap


## Installation


### Installer le submodule

`git submodule add https://github.com/osunyorg/osuny-plugin-news-sitemap themes/osuny-plugin-news-sitemap`

### Appeler le plugin

Dans `config/_default/config.yaml` :

```
_merge: deep
theme: 
  - osuny
  - osuny-plugin-news-sitemap
```

Le paramètre `merge: deep` est essentiel pour le bon fonctionnement du site !
