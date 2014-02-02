File:      test/input-type-radio-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Radio** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="radio"] {
        @extend %input[type="radio"];

        content : "@extend %input[type="radio"];";
    }

Only `input[type="radio"]` selector definitions should be stated.
