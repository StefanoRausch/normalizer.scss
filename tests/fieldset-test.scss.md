File:      test/fieldset-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Fieldset** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    fieldset {
        @extend %fieldset;

        content : "@extend %fieldset;";
    }

Only `fieldset` selector definitions should be stated.
