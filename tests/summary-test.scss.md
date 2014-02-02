File:      test/summary-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Summary** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    summary {
        @extend %summary;

        content : "@extend %summary;";
    }

Only `summary` selector definitions should be stated.
