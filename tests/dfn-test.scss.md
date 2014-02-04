File:      test/dfn-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Dfn** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    dfn {
        @extend %dfn;

        content : "@extend %dfn;";
    }

Only `dfn` selector definitions should be stated.
