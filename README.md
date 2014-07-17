# inuit-starter-kit

    $ bower install --save inuit-starter-kit

The `inuit-starter-kit` simply ties together a few key dependencies that are
usually the starting point for any new project. The `inuit-starter-kit`
specifically contains some inuitcss default variables and mixins, as well as
[Nicolas Gallagher](https://twitter.com/necolas)’s
[Normalize.css](https://github.com/necolas/normalize.css) and global
`box-sizing` rules. These must be imported in the following order:

    @import "bower_components/inuit-defaults/settings.defaults";

    @import "bower_components/inuit-functions/tools.functions";
    @import "bower_components/inuit-mixins/tools.mixins";

    @import "bower_components/inuit-normalize/generic.normalize";
    @import "bower_components/inuit-box-sizing/generic.box-sizing";

    @import "bower_components/inuit-page/base.page";
