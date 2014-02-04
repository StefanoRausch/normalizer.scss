File:      test/canvas-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Canvas** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    canvas {
        @extend %canvas;

        content : "@extend %canvas;";
    }

Only `canvas` selector definitions should be stated.
