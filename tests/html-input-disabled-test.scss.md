File:      test/html-input-disabled-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **HTML Input Disabled** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    html {
        @extend %html;
    }

    html input[disabled] {
        @extend %input[disabled];

        content : "@extend %input[disabled];";
    }

Only `html` and `input[disabled]` selector definitions should be stated.
