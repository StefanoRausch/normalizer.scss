File:      test/a-active-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **A Active** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    a:active {
        @extend %a:active;

        content : "@extend %a:active;";
    }

Only `a:active` selector definitions should be stated.
