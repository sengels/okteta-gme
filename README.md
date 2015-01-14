## okteta-gme
[Okteta](https://www.kde.org/applications/utilities/okteta/) tool definitions for the gme file format to make the Hex Editor display details about the Tiptoi pen file format.

## installation of the structure definition in Okteta 
    mkdirs -p ~/.kde/share/apps/okteta/structures/gme/
    cp gme/gme.* ~/.kde/share/apps/okteta/structures/gme/
    
Then in Okteta, in the menu choose "Tool" and enable "Structures". In the Structure-window choose "Settings" and enable "GME Header" under "Structure management".

## useful links
* [Tiptoi Game Format](https://github.com/entropia/tip-toi-reveng/blob/master/GME-Format.md)
* [Okteta structure description (German)](https://docs.kde.org/stable/de/kdesdk/okteta/tools-structures.html)
* [Okteta structure tutorial](https://frinring.wordpress.com/2010/01/16/tutorial-create-your-own-okteta-structure-definitions/)
* [Okteta structure samples](https://projects.kde.org/projects/kde/kdesdk/okteta/repository/revisions/master/show/kasten/controllers/view/structures/examples/okteta/structures)
* [Okteta OSD format XSD](https://projects.kde.org/projects/kde/kdesdk/okteta/repository/revisions/master/entry/kasten/controllers/view/structures/schema/structuredefs.xsd) (albeit incomplete, e.g. misses pointers)
