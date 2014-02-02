File:      test/mark-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Mark** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    mark {
        @extend %mark;

        content : "@extend %mark;";
    }

Only `mark` selector definitions should be stated.
