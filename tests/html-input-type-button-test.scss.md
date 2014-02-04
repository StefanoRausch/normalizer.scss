File:      test/html-input-type-button-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **HTML Input Type Button** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    html {
        @extend %html;
    }

    html input[type="button"] {
        @extend %input[type="button"];

        content : "@extend %input[type="button"];";
    }

Only `html` and `input[type="button"]` selector definitions should be stated.
