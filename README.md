[![Latest Stable Version](https://poser.pugx.org/carbon/link/v/stable)](https://packagist.org/packages/carbon/link)
[![Total Downloads](https://poser.pugx.org/carbon/link/downloads)](https://packagist.org/packages/carbon/link)
[![License](https://poser.pugx.org/carbon/link/license)](https://packagist.org/packages/carbon/link)
[![GitHub forks](https://img.shields.io/github/forks/CarbonPackages/Carbon.Link.svg?style=social&label=Fork)](https://github.com/CarbonPackages/Carbon.Link/fork)
[![GitHub stars](https://img.shields.io/github/stars/CarbonPackages/Carbon.Link.svg?style=social&label=Stars)](https://github.com/CarbonPackages/Carbon.Link/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/CarbonPackages/Carbon.Link.svg?style=social&label=Watch)](https://github.com/CarbonPackages/Carbon.Link/subscription)

# Carbon.Link Package for Neos CMS

This package provides some fusion helper for link editor.

## Installation

Most of the time you have to make small adjustments to a package (e.g. configuration in `Settings.yaml`). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under `Packages/Sites/`. To install it correctly go to your theme package (e.g.`Packages/Sites/Foo.Bar`) and run following command:

```bash
composer require carbon/link --no-update
```

The `--no-update` command prevent the automatic update of the dependencies. After the package was added to your theme `composer.json`, go back to the root of the Neos installation and run `composer update`. Et voilà! Your desired package is now installed correctly.

## License

Licensed under MIT, see [LICENSE](LICENSE)
