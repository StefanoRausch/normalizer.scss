File:      test/pre-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Pre** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    pre {
        @extend %pre;

        content : "@extend %pre;";
    }

Only `pre` selector definitions should be stated.
