File:      test/body-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Body** : Single Selector Test  
> <small> see [normalizer.scss](../normalizer.scss.md) </smalll>

    @import "../normalizer";

    body {
        @extend %body;

        content : "@extend %body;";
    }

Only `body` selector definitions should be stated.
