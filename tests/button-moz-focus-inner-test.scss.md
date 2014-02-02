File:      test/button-moz-focus-inner-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Button Moz Focus Inner** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    button::-moz-focus-inner {
        @extend %button::-moz-focus-inner;

        content : "@extend %button::-moz-focus-inner;";
    }

Only `button::-moz-focus-inner` selector definitions should be stated.
