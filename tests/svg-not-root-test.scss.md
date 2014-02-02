File:      test/svg-not-root-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Svg Not Root** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    svg:not(:root) {
        @extend %svg:not(:root);

        content : "@extend %svg:not(:root);";
    }

Only `svg:not(:root)` selector definitions should be stated.
