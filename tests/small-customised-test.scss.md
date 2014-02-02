File:      test/small-customised-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Small Customised** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    $normalizer-small-font-size : 16px;

    @import "../normalizer";

    small {
        @extend %small;

        content : "@extend %small;";
    }

Only `small` selector definitions should be stated.
