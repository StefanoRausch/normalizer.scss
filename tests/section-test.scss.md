File:      test/section-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Section** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    section {
        @extend %section;

        content : "@extend %section;";
    }

Only `section` selector definitions should be stated.
