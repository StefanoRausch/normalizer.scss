File:      test/kbd-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Kbd** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    kbd {
        @extend %kbd;

        content : "@extend %kbd;";
    }

Only `kbd` selector definitions should be stated.
