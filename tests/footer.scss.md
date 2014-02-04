File:      test/footer-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Footer** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    footer {
        @extend %footer;

        content : "@extend %footer;";
    }

Only `footer` selector definitions should be stated.
