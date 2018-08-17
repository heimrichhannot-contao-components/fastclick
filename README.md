# FastClick Contao component
A shim repositoy for [FastClick](https://github.com/ftlabs/fastclick) as [Contao Component](https://github.com/contao-components/installer).

## Install

```
composer require heimrichhannot-contao-components/fastclick
```


## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_fastclick'] = 'assets/fastclick/lib/fastclick.min.js|static';
```

### Contao 3

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_fastclick'] = 'assets/components/fastclick/lib/fastclick.min.js|static';
```

## Internal

Update library: 
* `svn export https://github.com/ftlabs/fastclick.git/trunk/lib`
* minfiy

