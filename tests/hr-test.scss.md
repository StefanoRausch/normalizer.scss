File:      test/hr-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Hr** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    hr {
        @extend %hr;

        content : "@extend %hr;";
    }

Only `hr` selector definitions should be stated.
