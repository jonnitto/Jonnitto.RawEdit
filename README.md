[![Latest Stable Version](https://poser.pugx.org/jonnitto/iframe/v/stable)](https://packagist.org/packages/jonnitto/rawedit)
[![Total Downloads](https://poser.pugx.org/jonnitto/rawedit/downloads)](https://packagist.org/packages/jonnitto/rawedit)
[![License](https://poser.pugx.org/jonnitto/rawedit/license)](https://packagist.org/packages/jonnitto/rawedit)
[![GitHub forks](https://img.shields.io/github/forks/jonnitto/Jonnitto.RawEdit.svg?style=social&label=Fork)](https://github.com/jonnitto/Jonnitto.RawEdit/fork)
[![GitHub stars](https://img.shields.io/github/stars/jonnitto/Jonnitto.RawEdit.svg?style=social&label=Stars)](https://github.com/jonnitto/Jonnitto.RawEdit/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/jonnitto/Jonnitto.RawEdit.svg?style=social&label=Watch)](https://github.com/jonnitto/Jonnitto.RawEdit/subscription)
[![GitHub followers](https://img.shields.io/github/followers/jonnitto.svg?style=social&label=Follow)](https://github.com/jonnitto/followers)
[![Follow Jon on Twitter](https://img.shields.io/twitter/follow/jonnitto.svg?style=social&label=Follow)](https://twitter.com/jonnitto)

# Jonnitto.RawEdit

Raw content Helper for [Neos CMS](https://www.neos.io):

This package provides some helper if you want to serve your content in the "Raw Content Mode".

## Installation

Most of the time you have to make small adjustments to a package (e.g. configuration in Settings.yaml). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under Packages/Sites/. To install it correctly go to your theme package (e.g.Packages/Sites/Foo.Bar) and run following command:

```
composer require jonnitto/rawedit --no-update
```

The --no-update command prevent the automatic update of the dependencies. After the package was added to your theme composer.json, go back to the root of the Neos installation and run composer update. Et voilà! Your desired package is now installed correctly.

## License

Licensed under MIT, see [LICENSE](LICENSE)
