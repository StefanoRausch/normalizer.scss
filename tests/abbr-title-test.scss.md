File:      test/abbr-title-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Abbr Title** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    abbr[title] {
        @extend %abbr[title];

        content : "@extend %abbr[title];";
    }

Only `abbr[title]` selector definitions should be stated.
