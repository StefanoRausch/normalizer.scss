File:      test/input-moz-focus-inner-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Moz Focus Inner** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input::-moz-focus-inner {
        @extend %input::-moz-focus-inner;

        content : "@extend %input::-moz-focus-inner;";
    }

Only `input::-moz-focus-inner` selector definitions should be stated.
