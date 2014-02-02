File:      test/input-type-search-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Search** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="search"] {
        @extend %input[type="search"];

        content : "@extend %input[type="search"];";
    }

Only `input[type="search"]` selector definitions should be stated.
