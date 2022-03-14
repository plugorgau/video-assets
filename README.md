# PLUG Video Assets

This repository contains video assets used to produce recordings of
[Perth Linux User Group][1] talks.

## Opening and Closing Titles

The `./opening` and `./closing` directories contain [Pitivi][2]
projects for the opening and closing titles. The graphical elements
are SVG files created in [Inkscape][3].

The XGES project format includes absolute paths to assets, so it is
likely that Pitivi will complain about missing assets when you open
the project (see [GES issue #6][4]). Once you give the location of an
asset, Pitivi should be able to load the project.

The SVG files embed the outlines of the text, so there should be no
rendering issues for the project. The fonts used are:

 * [Ubuntu Titling][5] is used in the PLUG logo
 * [ProFont][6] is used in the closing titles (I used the "ProFont ttf (older version)" download).

## Backdrop

The `./backdrop` directory contains an SVG background to be used with
[bbb-render][7]. When opened with Inkscape, it has guides to help
determine which areas will be visible when the slides and webcam video
are overlaid.

[1]: https://www.plug.org.au/
[2]: https://pitivi.org/
[3]: https://inkscape.org/
[4]: https://gitlab.freedesktop.org/gstreamer/gst-editing-services/-/issues/6
[5]: https://www.fontsquirrel.com/fonts/Ubuntu-Titling
[6]: https://tobiasjung.name/profont/
[7]: https://github.com/plugorgau/bbb-render
