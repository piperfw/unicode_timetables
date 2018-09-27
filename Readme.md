## Unicode timetables

- Basic template made using Mark Lodato's avaScript Unicode box drawing demo:  https://github.com/MarkLodato/
- This was then copied and tweaked in Sublime Text 3 to construct tables of different spacing.

### Tips
- When editing timetables in sublime text, turn off word wrap and make use of multiple selections (Alt+Shift+Up/Down or Ctrl+Mouse Click on Linux). 
- To fill in the timetable, use overtype instead of insert mode (INS).
- Ctrl + Left/Right will jump to the next slot of the timetable.
- Save your timetable to a file, for example, `my_timetable`, and use `cat my_timetable` or `more my_timetable` to print the timetable to the console. Consider defining a `timetable` alias in bash with this command.
- `cat` may be used to display multiple timetables in one go.
- Your terminal emulator should support unicode.

### Note
On the Github preview the tables appear broken. They are not - just open the files (or copy to a blank file) in an editor without word wrapping.
