---
title: gPodder
subtitle: Media aggregator and [podcast](https://en.wikipedia.org/wiki/Podcast) client
logo: gpodder.png
---

gPodder is a simple, open source podcast client written in Python using GTK+. In development since 2005 with a proven, mature codebase.

{% assign version = site.data.gpodder.version %}
The latest version is {{version}}, released {{site.data.gpodder.date}}. Read the [release notes](http://blog.gpodder.org/).

### Get it

-   Windows: [gPodder {{site.data.windows.version}}][win] (also as [ZIP][win-zip])<br>
    <small>You also need to install [32-bit Python {{site.data.windows.pythonVersion}}][win-python] and [PyGTK {{site.data.windows.pygtkVersion}}][win-gtk]</small>
-   macOS: [gPodder {{site.data.macos.version}}][mac]<br>
    <small>Already includes Python and PyGTK</small>
-   Linux/BSD: Install via the package manager<br>
    <small>Available in most distributions (Debian, Ubuntu, Fedora, ...)</small>
-   Source code: [github.com/gpodder/gpodder](https://github.com/gpodder/gpodder)

### Get help

Ask on the [mailing list](http://www.freelists.org/list/gpodder), report problems at the [issue tracker](https://github.com/gpodder/gpodder/issues) or read the [wiki](https://github.com/gpodder/gpodder/wiki).

[win]: http://sourceforge.net/projects/gpodder/files/windows/gpodder-{{site.data.windows.version}}-setup.exe/download
[win-zip]: http://sourceforge.net/projects/gpodder/files/windows/gpodder-{{site.data.windows.version}}-win32.zip/download
[win-python]: https://www.python.org/ftp/python/{{site.data.windows.pythonVersion}}/python-{{site.data.windows.pythonVersion}}{{site.data.windows.pythonPatch}}.msi
[win-gtk]: http://ftp.gnome.org/pub/GNOME/binaries/win32/pygtk/{{site.data.windows.pygtkVersion}}/pygtk-all-in-one-{{site.data.windows.pygtkVersion}}{{site.data.windows.pygtkPatch}}.win32-py{{site.data.windows.pythonVersion}}.msi
[mac]: https://sourceforge.net/projects/gpodder/files/macosx/gPodder-{{site.data.macos.version}}{{site.data.macos.patch}}.zip/download