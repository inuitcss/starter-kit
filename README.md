# inuit-starter-kit

    $ bower install --save inuit-starter-kit

The `inuit-starter-kit` simply ties together a few key dependencies that are
usually the starting point for any new project. The `inuit-starter-kit`
specifically contains some inuitcss default variables and mixins, as well as
[Nicolas Gallagher](https://twitter.com/necolas)’s
[Normalize.css](https://github.com/necolas/normalize.css) and global
`box-sizing` rules.

To start using, simply add to the start of your styles:

    @import "bower_components/inuit-starter-kit/inuit-starter-kit";

Which will import, in order:

    @import "../inuit-defaults/settings.defaults";

    @import "../inuit-functions/tools.functions";
    @import "../inuit-mixins/tools.mixins";

    @import "../inuit-normalize/generic.normalize";
    @import "../inuit-box-sizing/generic.box-sizing";

    @import "../inuit-page/base.page";
