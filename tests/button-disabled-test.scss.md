File:      test/button-disabled-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Button Disabled** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    button[disabled] {
        @extend %button[disabled];

        content : "@extend %button[disabled];";
    }

Only `button[disabled]` selector definitions should be stated.
