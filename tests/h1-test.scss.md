File:      test/h1-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **H1** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    h1 {
        @extend %h1;

        content : "@extend %h1;";
    }

Only `h1` selector definitions should be stated.
