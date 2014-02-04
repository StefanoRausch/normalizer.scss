File:      test/hgroup-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Hgroup** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    hgroup {
        @extend %hgroup;

        content : "@extend %hgroup;";
    }

Only `hgroup` selector definitions should be stated.
