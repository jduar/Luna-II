# Luna II

This plasmoid displays the current phase of the moon.

If you click on it, a dialog appears which shows the dates of the important moon
phases in the same month (last new moon, first quarter, full moon, third quarter
and next new moon).

The format in which these dates are shown can be customized.

You can navigate to previous or future moon phases by clicking the arrow buttons or by
pressing the arrow keys. Clicking the middle button or pressing the "Home" key
returns to the current dates.

This is a port to Plasma 6 of:

* Luna QML
* Version 1.4
* <https://store.kde.org/p/1002036/>

## Installation

Currently, the existing installation tools need updating.

Alternatively, you can copy the contents of the `package` directory to `$HOME/.local/share/plasma/plasmoids/org.kde.userbase.plasma.luna-ii/`.

## Development

In order to test the applet during development, install the `plasma-sdk` package.

Then, run the applet with:

```
$ plasmoidviewer -a <path-to-repository>/package/ -l topedge -f horizontal
```
