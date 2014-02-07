# normalizer.scss

The [normalize.css][] library for [Sass][].

## Introduction

There are many attempts to convert [normalize.css][] to `Sass` to be found on GitHub — do a [search](https://github.com/search?q=normalize&source=c) and you will find simple ones to quite nice ( complex ) implementations for reducing the rules load.

Trying out the different approaches available I did not find an elegant library suiting me — until today! Instead of decomposing [normalize.css][] and rebuilding it, why not just modify and enhance the library as little as possible to achieve the goal?

## Meet the Placeholder Selectors

Every `selector` in [normalize.css][] is a `%selector` in normalizer.scss.

> With this approach you only need to `@extend` a required ( normalising ) placeholder selector, avoiding any unnecessary output in the final `CSS`. Sweet!

Caveat : The `[hidden]` attribute can not be converted to a placeholder selector and hence I have to revert to the standard approach for inclusion / exclusion. An acceptable trade off.

Have a look at the [Literate Source Code][] **[version](_normalizer.scss.md)** as well as at the resulting clean `Sass` counterpart. For the more sceptical guys : check out the ( simple ) test files and let me know, if you find any flaws.

Happy Normalizing!

## Acknowledgements

Without [Nicolas Gallagher][] and [Jonathan Neal][] as well as all the tireless contributors to [normalize.css][] this mental exercise would not have been possible. Thanks guys!

## License

Except where explicitly stated otherwise, all documents / documentation and ( future ) translations in this repository are licensed under the <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_GB">Creative Commons Attribution 3.0 Unported License</a>. ( Source ) Code is licensed under [The MIT License](LICENSE.md).

Based on a work at <https://github.com/StefanoRausch/normalizer.scss>.

## Changelog

### 4.0.0-alpha.1 : 2014-02-07

- Removed the additional customisation features `$normalizer-html-font-family`, `$normalizer-h1-font-size`, `$normalizer-h1-margin` and `$normalizer-small-font-size` to comply with the primary goal of normalizer.scss to allow the reduction of the rules load ( which already is minimal ) in the final `CSS` output file.
- Removed the respective customised tests.

- Updated the documentation to reduce duplication of the headers.

### 3.0.0 : 2014-02-03

- Initial commit.

[Jonathan Neal]: https://github.com/jonathantneal
[Literate Source Code]: https://github.com/StefanoRausch/Literate-Source-Code
[Nicolas Gallagher]: https://github.com/necolas
[normalize.css]: https://github.com/necolas/normalize.css
[Sass]: http://sass-lang.com
