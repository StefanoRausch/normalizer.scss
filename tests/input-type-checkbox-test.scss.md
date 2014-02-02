File:      test/input-type-checkbox-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Checkbox** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="checkbox"] {
        @extend %input[type="checkbox"];

        content : "@extend %input[type="checkbox"];";
    }

Only `input[type="checkbox"]` selector definitions should be stated.
