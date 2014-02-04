File:      test/html-customised-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **HTML Customised** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    $normalizer-html-font-family : "Helvetica Neue", Helvetica, sans-serif;

    @import "../normalizer";

    html {
        @extend %html;

        content : "@extend %html;";
    }

Only `html` selector definitions should be stated.
