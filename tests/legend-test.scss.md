File:      test/legend-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Legend** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    legend {
        @extend %legend;

        content : "@extend %legend;";
    }

Only `legend` selector definitions should be stated.
