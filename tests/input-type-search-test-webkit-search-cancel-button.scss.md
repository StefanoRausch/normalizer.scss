File:      test/input-type-search-webkit-search-cancel-button-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Search Webkit Search Cancel Button** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="search"]::-webkit-search-cancel-button {
        @extend %input[type="search"]::-webkit-search-cancel-button;

        content : "@extend %input[type="search"]::-webkit-search-cancel-button;";
    }

Only `input[type="search"]::-webkit-search-cancel-button` selector definitions should be stated.
