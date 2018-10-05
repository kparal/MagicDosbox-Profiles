# Civilization (1991) Magic DosBox profile

This is the Magic DosBox profile for [Civilization (1991)] game. Read the
[overall README] for some basic information and introduction.

This profile has been created for *Google Nexus 7* device. I don't know how
well it will display on other devices. You can always adjust the button
placement manually, though.

## Screenshots
![screenshot 1][screen1]

![screenshot 2][screen2]

## Controls

Most buttons are self-explanatory. `Orders` and `Extra` are containers for more
buttons. Some buttons deserve an additional note:
* `Improve agriculture` is equivalent to pressing `i` (intended for Settlers).
* `Improve industry` is equivalent to pressing `m` (intended for Settlers).
* `Help` is equivalent to pressing `Alt+h` and only works in menus with
  *"Help available"* note.
* `Manual` and `Tech tree` show up game manual and a technology tree diagram,
  but only work if you download the documents. More on that in a separate
  section.
* `Center` button in the middle of the virtual joystick centers your map on
  your currently active unit.
* `Move` section of the virtual joystick (the outside of the inner circle) is
  used for moving the current unit into 8 different directions. You do that by
  tapping the gray area outside of the circle. Do not try to move the compass
  arrow, that doesn't work.
* `Scroll` changes the `Move` joystick into a `Scroll` joystick. As long as it
  is active, it will scroll the map instead of moving the units.
* `Toggle UI` is helpful when the virtual joystick covers a link you want to
  click in the Civilopedia.

*Scrolling the map* is also possible by tapping the screen anywhere to center
on that location (uses the mouse cursor) or by swiping your finger into 4
different directions (the next tap after swiping is ignored, because it was
otherwise causing issues).

*Right mouse button* is configured to a long press (useful e.g. for help about
a terrain or in the city building menu).

There are overlays on each of the top menu items that make pressing them
easier (otherwise the menus like to detect a double tap and disappear
immediately). However, the `Game` menu overlay is shifted to the right,
because there is a single screen in the game (*Complete Civilopedia*) where
you might need to tap in the top left corner. So if showing the `Game` menu
doesn't work reliably, tap more into the right. Vice versa, if the the `More`
button in *Complete Civilopedia* doesn't work well, tap more into the left.

## Help documents

It's useful to be able to show game manual and the technology tree diagram
directly in the game without needing to switch apps. However, the exported
profile can't contain extra documents, so if you want to use this extra help,
you need to download the `html/` directory provided in this repo and place it
in your game directory. Then, you'll also probably need to enter the `Add
virtual buttons` mode, edit the buttons and configure the path to those
HTML documents (I haven't tested this, but the paths inside the profile seem
to be stored as absolute paths, and not relative to the game directory, so
I'm quite confident the edit will be needed). Alternatively, you can try to
store them at `Games/Civ1/html/` on your internal storage and it might just
work (that's the same path as I use).

## Credits

The HTML manual has been retrieved from [CivFanatics]. It is most probably
copyrighted.
The tech tree diagram has been retrieved from [My Abandonware]. It might be
copyrighted.

[Civilization (1991)]: https://www.mobygames.com/game/dos/sid-meiers-civilization
[overall README]: ../README.md
[screen1]: screen1.png
[screen2]: screen2.png
[CivFanatics]: https://www.civfanatics.com/civ1/manuals/
[My Abandonware]: https://www.myabandonware.com/game/sid-meier-s-civilization-1nj
