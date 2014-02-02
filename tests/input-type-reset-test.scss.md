File:      test/input-type-reset-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Reset** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="reset"] {
        @extend %input[type="reset"];

        content : "@extend %input[type="reset"];";
    }

Only `input[type="reset"]` selector definitions should be stated.
