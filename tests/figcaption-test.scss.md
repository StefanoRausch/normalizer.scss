File:      test/figcaption-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Figcaption** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    figcaption {
        @extend %figcaption;

        content : "@extend %figcaption;";
    }

Only `figcaption` selector definitions should be stated.
