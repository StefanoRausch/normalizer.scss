File:      test/audio-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Audio** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    audio {
        @extend %audio;

        content : "@extend %audio;";
    }

Only `audio` selector definitions should be stated.
