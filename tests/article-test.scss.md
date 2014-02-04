File:      test/article-test.scss.md  
License:   MIT — http://opensource.org/licenses/MIT  
Copyright: ( C ) 2014 Stefano F. Rausch < stefano@rausch-e.net >

> **Article** : Single Selector Test  
> <small> see [normalizer.scss](../_normalizer.scss.md) </smalll>

    @import "../normalizer";

    article {
        @extend %article;

        content : "@extend %article;";
    }

Only `article` selector definitions should be stated.
