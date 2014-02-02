File:      test/input-type-search-webkit-search-decoration-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Search Webkit Search Decoration** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="search"]::-webkit-search-decoration {
        @extend %input[type="search"]::-webkit-search-decoration;

        content : "@extend %input[type="search"]::-webkit-search-decoration;";
    }

Only `input[type="search"]::-webkit-search-decoration` selector definitions should be stated.
