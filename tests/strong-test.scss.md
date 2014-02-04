File:      test/strong-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Strong** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    strong {
        @extend %strong;

        content : "@extend %strong;";
    }

Only `strong` selector definitions should be stated.
