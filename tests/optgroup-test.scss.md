File:      test/optgroup-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Optgroup** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    optgroup {
        @extend %optgroup;

        content : "@extend %optgroup;";
    }

Only `optgroup` selector definitions should be stated.
