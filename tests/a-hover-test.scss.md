File:      test/a-hover-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **A Hover** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    a:hover {
        @extend %a:hover;

        content : "@extend %a:hover;";
    }

Only `a:hover` selector definitions should be stated.
