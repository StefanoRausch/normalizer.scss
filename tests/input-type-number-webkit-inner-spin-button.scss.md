File:      test/input-type-number-webkit-inner-spin-button-test.scss.md
License:   MIT — http://opensource.org/licenses/MIT
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Input Type Number Webkit Inner Spin Button** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    input[type="number"]::-webkit-inner-spin-button {
        @extend %input[type="number"]::-webkit-inner-spin-button;

        content : "@extend %input[type="number"]::-webkit-inner-spin-button;";
    }

Only `input[type="number"]::-webkit-inner-spin-button` selector definitions should be stated.
