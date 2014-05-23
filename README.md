Replex Pages
============

Source of the Replex's login panel and download widget pages.
It adds the ability to notify users about availability of new release.
Otherwise it loads normal grid login page.

In order to change the version update notifications to the users
change line

    var current_version = "1.8.0 (4114)";

to whichever is thelatest version is available on the main site
<http://www.replex.org/>

All of the work is done on "gh-pages" branch so that the pages can be
served from Githb pages.

Login page: <http://replex-viewer.github.io/pages/login/>
