# How to put a MiniSlice G-code file into the Toybox app or website

This guide is not from Toybox. It describes the steps as Toybox's public help pages
describe them. Toybox can change its screens at any time, so if a button is in a
different place, look for the Import option.

## What Toybox says it supports

- Toybox's help center says the Creator Space can import STL, OBJ, and G-code files
  through its Import feature.
- Toybox's FAQ says you can print from the website, www.make.toys/toys, as long as
  you are logged in to the same account as the printer.

## Steps

1. Make your model in MiniSlice.
   Press **Slice**. Check the preview and the status line.
2. Press **Save G-code**.
   - On the web version, the file should download as `something.gcode`.
   - If your browser or the preview saves it as `.txt`, rename it to `.gcode`.
3. Open the Toybox app, or go to www.make.toys/toys and sign in to the account that
   is linked to your printer.
4. In the Creator Space, tap **Import**, then choose your `.gcode` file.
5. Look at the preview. Make sure the model is on the plate and not cut off.
6. Start the print and stay with the printer for the first few layers.

## If something goes wrong

- **The file is too big to import.** One reviewer found a G-code file too large to
  import. Try Draft quality (0.3 mm layers), fewer walls, or a smaller model.
- **The printer does not show up.** Check that the printer is on, connected to the
  internet, and logged in to the same account.
- **The model is in the wrong place.** Check that everything is inside the plate
  (MiniSlice warns you before it slices). Press **Center** or **Arrange all**.
- **Test first.** Print a small cube before a moving part or a large model.

## Safety

- Keep the printer in sight while it heats and prints.
- Check the first layers. Stop the print if the model lifts off the plate or the
  filament stops coming out.
- Do not change the temperature limits in MiniSlice unless you know what your
  printer and filament need.
