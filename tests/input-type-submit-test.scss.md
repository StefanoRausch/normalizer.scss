File:      test/input-type-submit-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Submit** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="submit"] {
        @extend %input[type="submit"];

        content : "@extend %input[type="submit"];";
    }

Only `input[type="submit"]` selector definitions should be stated.
