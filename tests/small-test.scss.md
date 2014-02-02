File:      test/small-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Small** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    small {
        @extend %small;

        content : "@extend %small;";
    }

Only `small` selector definitions should be stated.
