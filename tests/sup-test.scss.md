File:      test/sup-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Sup** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    sup {
        @extend %sup;

        content : "@extend %sup;";
    }

Only `sup` selector definitions should be stated.
