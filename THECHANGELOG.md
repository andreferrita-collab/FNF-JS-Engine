V1.49.0-prerelease;

NOTE: This is a pre-release version of 1.49.0. certain features might not be fully finished.
also i didn't really do much for this update, due to lack of motivation to do coding here as well as personal issues.

Removals:

    Fast Note Spawning
    Note Recycling (for now, making a new instance every time is believed to save on RAM usage.)
    macOS no longer uses the ingame updater, due to issues.
    Some redundant code has been removed, making the source easier to navigate, and reducing the amount of code in each function.
    A few (no longer used) variables around the code have also been removed.
    9 options (and 1 gameplay changer) have been removed due to either being recreatable in LUA, or not being needed.

Changes:

    The legacy memory counter (that accurately tracks memory usage) has been re-added.
    The LUA backend has been completely rewritten (courtesy of @moxie-coder). it's mostly untested, but it MOSTLY works. some scripts might be broken, so be sure to point those out!
    The font for lua traces has been changed.
    More botplay texts have been added.
    The engine was internally updated to use the V-Slice hxcpp instead, adding more optimization.
    Notes now have a multAlpha variable, allowing you to change the alpha of a note without having to make 50 different spritesheets. (i'm looking at you, TheTrueAccount.)

Bug-fixes:

    Fixed the engine crashing when attempting to load a chart made in Psych Engine 1.0
    Fixed menu items being rendered behind the menu in the Character Editor
    EditorPlayState got a small update
    Fixed the updater incorrectly saying that you had to update JS Engine, even on pre-release versions.
    Fixed health icons having.. weird cropping.

