# normalizer.scss

The [normalize.css][] library for [Sass][].

## Introduction

There are many attempts to convert [normalize.css][] to `Sass` to be found on GitHub — do a [search](https://github.com/search?q=normalize&source=c) and you will find simple ones to quite nice ( complex ) implementations for reducing the rules load.

Trying out the different approaches available I did not find an elegant library suiting me — until today!

<small>**Food for Thoughts** : Every day I learn new ways how to use `Sass` and I am relieved that sometimes the most simple solution is the best one. Instead of trying to decompose [normalize.css][] and to rebuild it, why not just modify and enhance the library as little as possible to achieve the goal?</small>

## Meet the Placeholder Selectors

Every `selector` in [normalize.css][] is a `%selector` in normalizer.scss.

> With this approach you only need to `@extend` the placeholder in discussion. Sweet!

One caveat : the `[hidden]` attribute can not be converted to a placeholder selector and hence I have to revert to the standard approach for inclusion / exclusion of this attribute in the final `CSS` output. An acceptable trade off.

Have a look at the [Literate Source Code][] [version](_normalizer.scss.md) — watch out for the hidden gems — as well as the resulting clean `Sass` counterpart. For the more sceptical guys : check out the ( simple ) test files and let me know, if you find any flaws.

Happy Normalizing!

## Acknowledgements

Without [Nicolas Gallagher][] and [Jonathan Neal][] as well as all the tireless contributors to [normalize.css][] this mental exercise would not have been possible. Thanks guys!

## License

Except where explicitly stated otherwise, all documents / documentation and ( future ) translations in this repository are licensed under the <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_GB">Creative Commons Attribution 3.0 Unported License</a>. ( Source ) Code is licensed under [The MIT License](LICENSE.md).

Based on a work at <https://github.com/StefanoRausch/normalizer.scss>.

## Changelog

### 3.0.0 : 2014-02-03

- Initial commit.

[Jonathan Neal]: https://github.com/jonathantneal
[Literate Source Code]: https://github.com/StefanoRausch/Literate-Source-Code
[Nicolas Gallagher]: https://github.com/necolas
[normalize.css]: https://github.com/necolas/normalize.css
[Sass]: http://sass-lang.com