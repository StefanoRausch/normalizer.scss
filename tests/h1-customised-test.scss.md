File:      test/h1-customised-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **H1 Customised** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    $normalizer-h1-font-size : 18px;
    $normalizer-h1-margin    : 20px 0;

    @import "../normalizer";

    h1 {
        @extend %h1;

        content : "@extend %h1;";
    }

Only `h1` selector definitions should be stated.
