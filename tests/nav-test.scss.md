File:      test/nav-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Nav** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    nav {
        @extend %nav;

        content : "@extend %nav;";
    }

Only `nav` selector definitions should be stated.
