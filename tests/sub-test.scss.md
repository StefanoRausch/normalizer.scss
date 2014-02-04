File:      test/sub-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Sub** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    sub {
        @extend %sub;

        content : "@extend %sub;";
    }

Only `sub` selector definitions should be stated.
