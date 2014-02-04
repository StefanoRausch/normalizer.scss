File:      test/td-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Td** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    td {
        @extend %td;

        content : "@extend %td;";
    }

Only `td` selector definitions should be stated.
