File:      test/progress-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Progress** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    progress {
        @extend %progress;

        content : "@extend %progress;";
    }

Only `progress` selector definitions should be stated.
