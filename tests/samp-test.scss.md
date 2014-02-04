File:      test/samp-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Samp** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    samp {
        @extend %samp;

        content : "@extend %samp;";
    }

Only `samp` selector definitions should be stated.
