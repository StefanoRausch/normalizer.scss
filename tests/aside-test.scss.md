File:      test/aside-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Aside** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    aside {
        @extend %aside;

        content : "@extend %aside;";
    }

Only `aside` selector definitions should be stated.
