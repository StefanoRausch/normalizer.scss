File:      test/audio-not-controls-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Audio Not Control** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    audio:not([controls]) {
        @extend %audio:not([controls]);

        content : "@extend %audio:not([controls]);";
    }

Only `audio:not([controls])` selector definitions should be stated.
